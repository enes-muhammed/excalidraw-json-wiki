# `boundElements`

Bir elemente bağlı başka elementlerin listesidir.

``` json
"boundElements": [
  {
    "id": "arrow123",
    "type": "arrow"
  },
  {
    "id": "text123",
    "type": "text"
  }
]
```

`type` yalnızca `arrow` veya `text` olabilir.

Bağlama ilişkisi iki taraflı düşünülmelidir: container tarafında
`boundElements`, text tarafında `containerId`, arrow tarafında
`startBinding` / `endBinding` bulunabilir.

Kaynak: `packages/element/src/types.ts`.
