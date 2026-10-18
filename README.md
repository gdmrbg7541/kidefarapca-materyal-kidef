# Kidef Arapça — sunu deposu

kidefarapca.com'daki Kidef Arapça 2. baskı sayfa çevirmeli kitabının **sunuları ve
videoları**. Ana site GitHub Pages'in 1 GB sınırında olduğu için ayrı depoda (sınıfların
materyal depoları gibi). Kitabın kendisi (sayfalar, çekirdek, veri, belgeler) ana sitede:
`kitap/kidef-arapca-2-baski/` — akıllı tahta yansıtma, telefon kumanda ve girişe bağlı
"İndir" kitabın sitenin içinde açılmasını gerektiriyor.

- `kidef-arapca-2-baski/05_sunumlar/<deste>/sunu.pdf` — 15 ders sunusu
- `kidef-arapca-2-baski/05_sunumlar/*.mp4` — Mazi dersinin 2 videosu
- `kidef-arapca-2-baski/05_sunumlar/<deste>/NNN.webp` — slayt resimleri (yedek gösterici)
- `sunu/<deste>.pdf` — 19 oyun/etkinlik sunusu (hafifler asıl PDF; ağırlar her slayt
  1600×900 resim). Hepsi "hızlı web görünümü"nde (qpdf --linearize).

Hazırlayan: sitenin `_kaynak/uretici/kidefSunuPdf.py`, `kidefSunuYerlestir.py`, `kidefKabukGeri.py`.
Gönderme: GitHub klasöründeki `gonder.command`.
