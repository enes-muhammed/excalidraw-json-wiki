# Text font alanları

## `fontSize`

JSON'da sayı olarak tutulur.

Kaynakta temel UI boyutları:

-   `sm` → 16
-   `md` → 20
-   `lg` → 28
-   `xl` → 36

Örneğin:

``` json
"fontSize": 28
```

## `fontFamily`

Sayısal font ID'sidir:

    ID Font
  ---- -----------------
     1 Virgil
     2 Helvetica
     3 Cascadia
     5 Excalifont
     6 Nunito
     7 Lilita One
     8 Comic Shanns
     9 Liberation Sans
    10 Assistant

`4` tarihsel sebeple boş bırakılmıştır.

Kaynak: `packages/common/src/constants.ts`.
