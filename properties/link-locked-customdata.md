# `link`, `locked`, `customData`

## `link`

Elemente bağlı URL veya bağlantı.

``` json
"link": null
```

veya bir string.

## `locked`

Elementin kilitli olup olmadığını belirtir.

``` json
"locked": false
```

## `customData`

Uygulamaya özel JSON verisi eklemek için opsiyonel alan.

``` json
"customData": {
  "myFeature": "value"
}
```

Tip: `Record<string, any>`.

Excalidraw'ın anlamını bilmediği uygulama verilerini burada taşımak
mümkündür, fakat üretici sistem kendi şemasını ayrıca
belgelendirmelidir.

Kaynak: `packages/element/src/types.ts`.
