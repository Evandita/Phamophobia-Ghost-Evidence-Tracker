# Phasmophobia Ghost Evidence Tracker

Ghost Evidence Tracker adalah sebuah perangkat yang terinspirasi dari game Phasmophobia untuk membantu aktivitas berburu `ghost`. Terdapat 24 jenis ghost yang memungkinkan, dan tugas kita adalah untuk mencari jenis apa ghost yang sedang diselidiki dengan bantuan bukti-bukti yang dimiliki. Terdapat 7 macam bukti yang dapat dicari, yakni Spirit Box, Fingerprint, Ghost Writing, EMF level 5, Freezing Temperature, Ghost Orb, dan DOTS Projector. Dari 7 bukti tersebut, setiap ghost dipastikan hanya membutuhkan 3 bukti untuk di identifikasi jenisnya.

Ghost Evidence Tracker merupakan perangkat yang mempermudah pengguna untuk melacak jenis ghost berdasarkan bukti-bukti yang didapat. Terdapat juga fitur timer untuk memberitahu kapan ghost mulai agresif.

## Perangkat Utama

![](/img/device.png)

Pada perangkat tersebut, dapat dilihat bahwa ada sebuah button untuk melakukan start/reset. Ketika button tersebut ditekan, maka timer 5 menit akan mulai untuk menandakan interval sebelum ghost yang diinvestigasi menyerang. Disebelahnya, terdapat juga button selector untuk memilih jenis ghost yang diinginkan berdasarkan bukti yang didapat. Tampilan 7-Segment Display Counter digunakan untuk menampilkan jumlah ghost yang memungkinkan berdasarkan bukti yang didapat.

Untuk mencatat bukti yang ditemukan, maka tombol `Evidence` yang sesuai ditekan. Apabila LED **hijau** menyala pada bagian `Evidence`, maka bukti sudah tercata. Sedangkan apabila LED **merah** menyala pada bagian `Evidence`, maka bukti tersebut tidak akan dicatat.

Bagian `Ghost Type` digunakan untuk menampilkan jenis-jenis ghost yang mungkin berdasarkan bukti yang tercatat pada perangkat. Apabila LED **merah** menyala pada sebuah jenis ghost, maka hal itu menandakan bahwa jenis ghost tersebut bukan yang sedang diinvestigasi. Sedangkan, apabila LED **kuning** menyala pada sebuah jenis ghost, maka hal itu menandakan bahwa jenis ghost tersebut memiliki kemungkinan yang sedang diinvestigasi. Lampu LED **hijau** menandakan jenis ghost yang telah dipilih oleh pemain, dan dapat dipindah menggunakan button `selector`.

Sebagai contoh, berikut merupakan hasil simulasi saat pemain menemukan `evidence` berupa:

- Spirit Box
- Ghost Writing
- EMF Level 5

![](/img/simulation.png)

Perangkat memberikan informasi bahwa jenis ghost yang sedang diinvestigasi yang memungkinkan adalah `spirit`, sehingga selector diarahkan ke `spirit` untuk memenangkan game.

## Rangkaian

Berikut merupakan macam-macam rangkaian dibalik perangkat Ghost Evidence Tracker yang digunakan:

### Main Engine

![](/img/main.png)

### Selector Engine

![](/img/selector.png)

### Timer Engine

![](/img/timer.png)

### Counter Engine

![](/img/counter.png)