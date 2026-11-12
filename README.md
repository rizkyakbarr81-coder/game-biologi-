# BioMonster Dunia untuk Android

Proyek ini membungkus game BioMonster Dunia (file `app/src/main/assets/index.html`) menjadi aplikasi Android.
Game berjalan offline. Kemajuan tersimpan di penyimpanan aplikasi.

## Cara A: Android Studio (di komputer)
1. Instal Android Studio, lalu pilih File > Open dan buka folder ini.
2. Tunggu sinkronisasi Gradle selesai.
3. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
4. Klik "locate" untuk menemukan `app-debug.apk` di `app/build/outputs/apk/debug/`.

## Cara B: GitHub Actions (tanpa instal apa pun)
1. Buat repositori baru di GitHub, lalu unggah seluruh isi folder ini, termasuk folder `.github`.
2. Buka tab Actions, jalankan "Build APK" (otomatis jalan setelah unggah).
3. Setelah selesai, unduh artefak `BioMonster-Dunia-APK` dari halaman hasil build.

## Memasang di HP
1. Kirim `app-debug.apk` ke HP.
2. Buka file itu. Jika diminta, izinkan pemasangan dari sumber ini.
3. Pasang, lalu buka "BioMonster Dunia".

APK debug sudah bertanda tangan otomatis, jadi bisa dipasang langsung. Untuk Google Play, buat APK rilis dengan keystore milikmu sendiri.
