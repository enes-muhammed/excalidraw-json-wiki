# `autoResize`, `lineHeight`, `labelPosition`, `baseFontSize`

## `autoResize`

`true` ise text genişliği metne uyum sağlar. `false` ise text mevcut
genişliğe göre satır kırar.

## `lineHeight`

Birimless line-height değeridir.

``` json
"lineHeight": 1.25
```

Piksel yüksekliği fontSize ile çarpılarak elde edilir.

## `labelPosition`

Linear elemente bağlı text için yol üzerinde normalize edilmiş `0–1`
konumudur.

## `baseFontSize`

Özellikle sticky note label düzeninde kullanılır. Diğer textlerde
çoğunlukla `null`dır.

Kaynak: `packages/element/src/types.ts`.
