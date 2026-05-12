# nurasandi

## Setup Firebase Realtime Database

Project ini sekarang sudah siap sinkron data ke Firebase (config undangan, ucapan, RSVP).

1. Buka `index.html` dan `admin.html`.
2. Cari objek `firebaseConfig`.
3. Ganti semua value placeholder:
   - `GANTI_API_KEY`
   - `GANTI_PROJECT_ID`
   - `GANTI_SENDER_ID`
   - `GANTI_APP_ID`
4. Di Firebase Console, aktifkan **Realtime Database** (mode test dulu untuk development).
5. Deploy ulang ke hosting kamu.

Kalau placeholder belum diganti, aplikasi otomatis fallback ke `localStorage` seperti sebelumnya.
