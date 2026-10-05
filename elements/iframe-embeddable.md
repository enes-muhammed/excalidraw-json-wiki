# Iframe ve Embeddable

## `embeddable`

``` json
"type": "embeddable"
```

Ortak base alanlarına ek zorunlu alanı yoktur.

## `iframe`

``` json
"type": "iframe"
```

Iframe elementinde AI-specific generation bilgisi
`customData.generationData` altında bulunabilir.

Generation durumları: - `pending` - `done` + `html` - `error` + `code`,
opsiyonel `message`

Bu alanı üretirken yalnızca gerçekten iframe/AI generation
kullanılıyorsa kullanmak gerekir.

Kaynak: `packages/element/src/types.ts`.
