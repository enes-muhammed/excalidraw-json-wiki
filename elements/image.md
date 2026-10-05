# Image element

Temel özel alanlar:

``` json
{
  "type": "image",
  "fileId": "image-file-id",
  "status": "saved",
  "scale": [1, 1],
  "crop": null
}
```

## `fileId`

`files` nesnesindeki binary dosyanın kimliğine bağlanır.

`null` olabilir.

## `status`

-   `pending`
-   `saved`
-   `error`

## `scale`

İki eksen için ölçek:

``` json
"scale": [1, 1]
```

Kaynak, değerleri `-1` ile `1` arasında tanımlar ve eksen çevirmeyi de
destekler.

## `crop`

Kırpma yoksa `null`. Varsa `x`, `y`, `width`, `height`, `naturalWidth`,
`naturalHeight` alanları vardır.

Kaynak: `packages/element/src/types.ts`.
