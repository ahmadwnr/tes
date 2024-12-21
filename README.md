README: Radio Indonesia untuk Euro Truck Simulator 2

Panduan ini menyediakan daftar stasiun radio Indonesia yang sudah diuji dan bekerja di Euro Truck Simulator 2 (ETS2). Stasiun-stasiun ini telah diuji dan dikonfirmasi kompatibel dengan sistem radio dalam game. Ikuti petunjuk di bawah untuk menambahkan stasiun-stasiun ini ke dalam game Anda.

Stasiun Radio yang Tersedia

Berikut adalah stasiun radio yang telah dikonfirmasi berfungsi:

Trax FM
Genre: Top Hits
URL Stream: http://202.147.199.99:8000/stream
Deskripsi: Stasiun populer yang menampilkan lagu-lagu hits terbaru dari Indonesia dan dunia.

FeMale Radio
Genre: Female Hits
URL Stream: http://202.147.199.101:8000/stream
Deskripsi: Stasiun yang dirancang untuk wanita, dengan campuran musik pop, R&B, dan easy listening.

Hard Rock FM
Genre: Lifestyle dan Hiburan
URL Stream: http://202.147.199.100:8000/stream
Deskripsi: Stasiun trendi yang menampilkan campuran musik dan talk show gaya hidup.

Cara Menambahkan Stasiun Radio ke ETS2
Temukan File live_streams.sii
Buka folder: Documents/Euro Truck Simulator 2.
Buka file bernama live_streams.sii menggunakan editor teks seperti Notepad.
Cadangkan File Asli
Sebelum membuat perubahan, buat salinan file live_streams.sii sebagai cadangan.
Tambahkan Stasiun Radio
Salin dan tempel baris berikut ke dalam file:

stream_data[0]: "http://202.147.199.99:8000/stream|Trax FM|Top Hits|ID|128|0"
stream_data[1]: "http://202.147.199.101:8000/stream|FeMale Radio|Female Hits|ID|128|0"
stream_data[2]: "http://202.147.199.100:8000/stream|Hard Rock FM|Lifestyle|ID|128|0"

Pastikan indeks stream_data[X] unik dan tidak bertabrakan dengan entri lain dalam file.
Simpan Perubahan
Simpan file dan tutup editor teks.

Uji di Dalam Game
Jalankan ETS2 dan buka menu radio untuk memastikan stasiun-stasiun baru muncul dan dapat diputar.

Pemecahan Masalah
Jika stasiun tidak muncul dalam game, periksa kembali format file live_streams.sii.

Uji URL menggunakan VLC Media Player untuk memastikan streaming aktif dan kompatibel.
Jika masalah tetap terjadi, hapus file live_streams.sii dan biarkan ETS2 membuat ulang file baru sebelum menambahkan kembali stasiun-stasiun.

Tentang Daftar Ini
Daftar ini dibuat berdasarkan kompatibilitas URL yang telah dikonfirmasi dengan ETS2. Jika Anda menemukan stasiun radio Indonesia lain yang bekerja di ETS2, jangan ragu untuk membagikannya dengan komunitas!
