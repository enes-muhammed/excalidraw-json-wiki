# `.excalidraw` dosya formatı

## Temel yapı

``` json
{
  "type": "excalidraw",
  "version": 2,
  "source": "https://excalidraw.com",
  "elements": [],
  "appState": {},
  "files": {}
}
```

## Alanlar

### `type`

Normal Excalidraw dosyasında `"excalidraw"`.

### `version`

Güncel kaynakta `VERSIONS.excalidraw = 2`.

Bu, element versiyonu değildir. Dosya şemasının sürümüdür.

### `source`

Dosyayı üreten kaynağı belirtir. Excalidraw kendi export akışında bunu
üretir.

### `elements`

Çizimin tüm elementlerini içeren dizi.

### `appState`

Editör durumu. Export sırasında temizlenmiş bir alt küme kullanılabilir.
AI tarafından rastgele doldurulmamalıdır.

### `files`

Görsel gibi binary dosyaların verileri. Görsel elementinin `fileId`
değeriyle ilişkilidir.

## Kaynak

`packages/excalidraw/data/types.ts` içindeki `ExportedDataState`.
`packages/common/src/constants.ts` içindeki `VERSIONS`.
