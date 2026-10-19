# Changelog — Gacor Mode

## v3.1 (19 Okt 2026) — hasil audit QA
- Badge GPS jujur: "GPS LOCKED" hanya untuk fix satelit beneran; fix tower/WiFi ditulis "LOKASI JARINGAN"
- Alarm koneksi anti false-positive: hanya bunyi bila beneran tidak ada internet sama sekali (cek ulang 3 detik, bukan cuma karena WiFi putus)
- "Aplikasi Prioritas" jadi "Pengingat Prioritas": toggle diakui sebagai pengingat saja, ketuk baris untuk buka pengaturan sistem
- "Jaga Koneksi" diganti "Monitor Koneksi": nama sesuai fungsi (monitor + peringatan, bukan penjaga sinyal)
- Peringatan bila pilih >2 aplikasi ojol: makin banyak dibebaskan, makin boros + rebutan GPS
- Jarak sesi hanya dari fix GPS beneran (tutup lubang phantom distance dari fix jaringan)
- Pilih aplikasi ojol kini opsional: tombol mode bisa dinyalakan tanpa memilih
- Mode Tampilan Gelap/Terang di layar Tema (kombinasi 4 warna aksen x 2 mode)
- Lebih ringan: notifikasi tidak di-rebuild tiap 5 detik, daftar satelit di-throttle, ikon aplikasi di-load di background
- Channel alarm dibuat sekali saja (tidak me-reset settingan user tiap bunyi)
- Menu Bantuan diperbarui: semua perubahan fungsi + Q&A baru soal pilih banyak aplikasi

## v2.9 (16 Okt 2026)
- Reset A-GPS kini kontekstual: tidak jalan bila GPS sudah bagus (< 15 m)
- Ping keep-alive ganti ke endpoint resmi Android (tembus semua operator)
- Tombol refresh: animasi putar + popup "Sudah diperbarui ✓"

## v2.8 (16 Okt 2026)
- Perbaiki alarm koneksi palsu: hasil ping basi diabaikan, alarm hanya setelah 2x gagal berturut-turut

## v2.7 (16 Okt 2026)
- Deteksi GPS "stuck": panduan "coba ke area terbuka" + coba ulang otomatis
- Reset A-GPS punya fallback untuk HP yang memblokir perintah sistem (mis. MIUI)
- Tombol refresh (⟳) di header

## v2.6 (16 Okt 2026)
- Layar Bantuan: 14 penjelasan fitur (akses via baris "Bantuan" / ikon "?")

## v2.5 (16 Okt 2026)
- Jaga Koneksi: ping keep-alive + alarm koneksi putus
- Reset A-GPS sekali ketuk
- Peta Langit Satelit (radar satelit)

## v2.4 (16 Okt 2026)
- Toggle DND menjadi saklar manual yang mandiri (lepas dari tombol mode)

## v2.2 (16 Okt 2026)
- Multi aplikasi ojol (checklist)
- Filter anti-drift untuk jarak sesi

## v2.1 (16 Okt 2026)
- Badge LIVE mengikuti status mode yang sebenarnya
- Warna tema berlaku ke seluruh tampilan

## v2.0 (16 Okt 2026)
- Rebrand: "GPS OJOL - GACOR MODE"
- Dashboard dark baru, pilih tema (Hijau/Oranye/Biru/Merah)
- Setup wizard 4 langkah, badge GPS LOCKED, grid statistik, strip sesi harian

## v1.3
- GPS via LocationManager (tanpa Play Services) — stabil, tidak crash

## v1.1 – v1.2
- Perbaikan tombol mode, loading daftar aplikasi, status GPS live, toggle DND

## v1.0
- Rilis awal: tombol mode kerja + GPS + DND
