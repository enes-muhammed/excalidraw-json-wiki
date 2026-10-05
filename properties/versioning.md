# `version` ve `versionNonce`

## `version`

Element değiştikçe artırılan sürüm sayısıdır.

``` json
"version": 1
```

## `versionNonce`

Değişikliklerde yeniden üretilen rastgele sayıdır.

``` json
"versionNonce": 123456789
```

Bunlar dosya şema sürümü değildir.

Kaynak kod bunları işbirliği, reconciliation ve güncelleme takibi için
kullanır.

AI tarafından yeni bir çizim üretilirken tutarlı değerler üretmek
önemlidir, ancak bu alanların tam runtime güncelleme davranışı `restore`
ve element mutation koduyla birlikte ele alınmalıdır.

Kaynak: `packages/element/src/types.ts`.
