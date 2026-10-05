# `updated` ve `created`

İkisi de epoch milliseconds tabanlı zaman değerleridir.

``` json
"updated": 1791208869586,
"created": 1791208822873
```

`created` kaynak tipinde `number | null` olabilir.

`updated`, son element güncellemesinin zamanını temsil eder.

`created`, element yaşam süresi boyunca korunur ve sıralama saati
değildir.

Kaynak: `packages/element/src/types.ts`.
