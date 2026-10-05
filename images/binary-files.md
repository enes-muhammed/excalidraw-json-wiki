# `files` ve BinaryFileData

Image elementleri dosya verisini `fileId` ile referanslar.

Bir binary file:

``` json
{
  "id": "image-file-id",
  "mimeType": "image/png",
  "dataURL": "data:image/png;base64,...",
  "created": 1791208869586
}
```

Opsiyonel: - `lastRetrieved` - `version`

Desteklenen yaygın image MIME türleri: - `image/svg+xml` - `image/png` -
`image/jpeg` - `image/gif` - `image/webp` - `image/bmp` -
`image/x-icon` - `image/avif` - `image/jfif`

`dataURL` gerçek binary veriyi taşıdığı için AI üretiminde gereksiz yere
büyük görseller gömmemek gerekir.

Kaynak: `packages/excalidraw/types.ts`,
`packages/common/src/constants.ts`.
