# Arrow bindings

Bir arrow'ın bir şekle bağlanması için:

``` json
"startBinding": {
  "elementId": "box1",
  "fixedPoint": [0.5, 0],
  "mode": "orbit"
},
"endBinding": {
  "elementId": "box2",
  "fixedPoint": [0.5, 1],
  "mode": "orbit"
}
```

## `fixedPoint`

`[xRatio, yRatio]` biçimindedir.

Her iki oran da `0.0–1.0` aralığında bound elementin lokal koordinatını
temsil eder.

Örneğin: - `[0, 0]` → sol üst - `[0.5, 0]` → üst orta - `[1, 0.5]` → sağ
orta - `[0.5, 1]` → alt orta

## `mode`

-   `inside`
-   `orbit`
-   `skip`

Kaynak: `packages/element/src/types.ts`.
