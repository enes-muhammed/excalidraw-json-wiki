# Excalidraw JSON Wiki

Kaynak kod temelli, dosya dosya düzenlenmiş Excalidraw JSON teknik
sözlüğü.

## Amaç

Bu proje, eğitimsel içerikten doğrudan geçerli `.excalidraw` JSON üreten
sistemler için kalıcı bir referans oluşturmaktır.

Temel zincir:

`PDF / metin → içerik analizi → Excalidraw JSON üretimi → .excalidraw → Excalidraw`

Bu wiki prompt değildir. Her özellik ayrı bir dokümanda tanımlanır.

## Kaynak

Ana kaynak: Excalidraw GitHub deposunun güncel `master` kaynak kodu.

Özellikle: - `packages/element/src/types.ts` -
`packages/excalidraw/data/types.ts` - `packages/excalidraw/types.ts` -
`packages/common/src/constants.ts` - `packages/common/src/colors.ts` -
`packages/excalidraw/data/restore.ts`

## Durum

`v0.1` çekirdek JSON şeması ve element alanlarıdır. Kaynak kod
değiştikçe bu wiki yeniden doğrulanmalıdır.

## Tasarım ilkesi

Bir alan için: 1. kaynak koddaki gerçek tip bulunur, 2. JSON karşılığı
belirlenir, 3. geçerli değerler kaydedilir, 4. minimal örnek verilir, 5.
AI üretiminde hangi durumlarda kullanılacağı belirtilir.

Kaynak kodun söylemediği bir davranış "kesin" kabul edilmez.
