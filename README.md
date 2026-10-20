# Dawns Geometri

Game HTML5 orisinal bergaya neon geometric runner. Dibuat dengan HTML Canvas, CSS, dan JavaScript tanpa CDN, font eksternal, atau API.

## Mainkan lokal
1. Unduh repository.
2. Buka `index.html` di browser modern.
3. Untuk offline PWA, buka lewat HTTPS (misalnya GitHub Pages) sekali saat online agar service worker dapat menyimpan file.

## Publish ke GitHub Pages
1. Upload file repository ke GitHub.
2. Buka Settings → Pages.
3. Source: Deploy from a branch.
4. Branch `main`, folder `/(root)`, Save.
5. Tunggu deployment. URL akan berupa `https://USERNAME.github.io/NAMA-REPO/`.

## Build APK gratis lewat GitHub Actions
Workflow `.github/workflows/android.yml` berjalan pada push ke `main` atau bisa dijalankan manual:
1. Tab Actions.
2. Pilih Build Dawns Geometri APK.
3. Klik Run workflow jika perlu.
4. Buka hasil run yang centang hijau.
5. Unduh artifact `Dawns-Geometri-APK` (ZIP), ekstrak, lalu instal `app-debug.apk`.

APK debug untuk pengujian, bukan rilisan Play Store. Aktifkan izin instalasi dari sumber tersebut hanya jika kamu percaya file build milikmu sendiri.

## Kontrol
- HP: ketuk area game untuk melompat.
- Komputer: Space / Arrow Up / W.
- Pause: tombol `Ⅱ` atau Escape.
- Suara opsional dari tombol `♪`.

## Fitur
- Tiga level dengan kecepatan dan warna berbeda.
- Rintangan duri, blok, garis finish.
- Efek partikel, animasi, skor dan best score lokal.
- Canvas responsif dan kontrol sentuh.
- Service worker untuk cache offline pada versi web yang disajikan melalui HTTPS.
