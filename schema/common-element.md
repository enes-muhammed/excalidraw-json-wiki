# Ortak Element Şeması

Excalidraw elementlerinin büyük bölümünde ortak temel alanlar bulunur.

``` json
{
  "id": "...",
  "type": "rectangle",
  "x": 100,
  "y": 100,
  "strokeColor": "#1e1e1e",
  "backgroundColor": "transparent",
  "fillStyle": "solid",
  "strokeWidth": 2,
  "strokeStyle": "solid",
  "roundness": null,
  "roughness": 1,
  "opacity": 100,
  "width": 200,
  "height": 100,
  "angle": 0,
  "seed": 123456,
  "version": 1,
  "versionNonce": 123456,
  "index": "a0",
  "isDeleted": false,
  "groupIds": [],
  "frameId": null,
  "boundElements": null,
  "updated": 0,
  "created": 0,
  "link": null,
  "locked": false
}
```

## Ortak alanlar

`id`, `x`, `y`, `strokeColor`, `backgroundColor`, `fillStyle`,
`strokeWidth`, `strokeStyle`, `roundness`, `roughness`, `opacity`,
`width`, `height`, `angle`, `seed`, `version`, `versionNonce`, `index`,
`isDeleted`, `groupIds`, `frameId`, `boundElements`, `updated`,
`created`, `link`, `locked`.

`customData` isteğe bağlıdır.

Element tipine göre ek alanlar bu temel yapıya eklenir.

## Kaynak

`packages/element/src/types.ts`, `_ExcalidrawElementBase`.
