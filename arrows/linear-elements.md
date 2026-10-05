# Linear elements

`line` ve `arrow`, ortak linear element yapısını paylaşır.

Ortak özel alanlar:

``` json
{
  "points": [[0, 0], [200, 0]],
  "startBinding": null,
  "endBinding": null,
  "startArrowhead": null,
  "endArrowhead": null
}
```

`line` ek olarak:

``` json
"polygon": false
```

`arrow` ek olarak:

``` json
"elbowed": false
```

Kaynak: `packages/element/src/types.ts`.
