# `roundness`

Köşe yuvarlama bilgisidir.

`null` olabilir:

``` json
"roundness": null
```

Veya:

``` json
"roundness": {
  "type": 3
}
```

Güncel algoritma tipleri:

-   `1` → `LEGACY`
-   `2` → `PROPORTIONAL_RADIUS`
-   `3` → `ADAPTIVE_RADIUS`

Kaynakta `ADAPTIVE_RADIUS` dikdörtgenler için güncel varsayılan
algoritmadır. Linear elementler ve diamond için proportional algoritma
kullanılır.

Kaynak: `packages/element/src/types.ts`,
`packages/common/src/constants.ts`.
