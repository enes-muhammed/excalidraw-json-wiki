# Elbow arrows

`arrow` elementinin `elbowed: true` olması, elbow arrow davranışını
belirtir.

Ek alanlar:

``` json
{
  "elbowed": true,
  "fixedSegments": null,
  "startIsSpecial": null,
  "endIsSpecial": null
}
```

`fixedSegments` her segment için başlangıç, bitiş ve index bilgisi
taşıyabilir:

``` json
{
  "start": [0, 0],
  "end": [100, 0],
  "index": 0
}
```

`startIsSpecial` ve `endIsSpecial`, bazı bağlı elbow arrow
geometrilerinde geçici segment davranışını belirtir.

Kaynak: `packages/element/src/types.ts`.
