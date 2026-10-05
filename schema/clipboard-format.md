# Clipboard JSON formatı

Excalidraw clipboard verisi normal `.excalidraw` dosyasından farklıdır.

``` json
{
  "type": "excalidraw/clipboard",
  "elements": [],
  "files": {}
}
```

## Önemli fark

Clipboard formatında normal dosyadaki `version`, `source` ve `appState`
alanları zorunlu değildir.

MIME türü:

`application/vnd.excalidraw.clipboard+json`

Kaynakta export veri tipi:

`excalidraw/clipboard`

Bu format, kopyala-yapıştır akışı için uygundur. Kalıcı `.excalidraw`
üretimi için normal dosya formatı tercih edilir.

## Kaynak

`packages/excalidraw/data/types.ts` `packages/common/src/constants.ts`
