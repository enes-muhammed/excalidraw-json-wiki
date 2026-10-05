# FreeDraw

Tip:

``` json
"type": "freedraw"
```

Özel alanlar:

``` json
{
  "points": [[0,0], [2,1], [5,4]],
  "pressures": [0.4, 0.5, 0.7],
  "simulatePressure": true,
  "strokeOptions": {
    "variability": "variable",
    "streamline": 0.5
  }
}
```

## `variability`

-   `constant`
-   `variable`

## `streamline`

Sayısal smoothing değeridir.

FreeDraw stroke width normal elementlerden farklı ölçeklenir. Detay için
`properties/stroke-width.md`.

Kaynak: `packages/element/src/types.ts`.
