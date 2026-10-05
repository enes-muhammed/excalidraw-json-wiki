# Açık araştırma konuları

Bu sürümde çekirdek tipler çıkarıldı. Aşağıdakiler ayrıca kaynak koddan
incelenmeli:

1.  `restore.ts` içindeki eksik/default alanların nasıl tamamlandığı.
2.  `cleanAppStateForExport()` tarafından export edilen AppState
    alanlarının tamamı.
3.  Renk paletinin tüm değerleri.
4.  `lineHeight` için tüm runtime hesaplama kuralları.
5.  Sticky note text fitting ve `baseFontSize` davranışının ayrıntıları.
6.  Elbow arrow `fixedSegments` geometrisinin üretim kuralları.
7.  Image crop ve scale'in tüm restore/render davranışı.
8.  Frame/magicframe'in scene/export ilişkisi.
9.  Iframe/embeddable URL ve güvenlik davranışları.
10. Fractional index üretim kuralları.
11. Element creation helper'larının hangi alanları hangi varsayılanlarla
    ürettiği.
12. Export/import sırasında hangi alanların zorunlu, hangilerinin
    restore edilebilir olduğu.

Bu liste özellikle AI üreticisinin "geçerli JSON" ile "runtime'da
gerçekten düzgün çalışan JSON" arasındaki farkı kapatmak için tutulur.
