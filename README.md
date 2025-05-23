# Laporan
## Library yang digunakan
awesome_notifications: ^0.10.1 - Digunakan package awesome_notifications dengan versi keluaran terbaru dikarenakan terjadi error dengan versi yang lama di mana tidak diciptakannya namespace sehingga tidak kompatibel dengan versi fluter yang saya gunakan

## Arsitektur aplikasi
Saya menggunakan struktur aplikasi model, service, screens untuk mempermudah pengembangan dan debugging error serta menunjang modularitas. Pada screens terdapat hanya dua screens yaitu: 1) HomeScreen dan 2) SecondScreen. HomeScreen berfungsi sebagai landing page saat user membuka aplikasi di mana HomeScreen akan berisi beberapa komponen button dengan fungsionalitas yang berbeda-beda. SecondScreen berguna untuk menjadi laman yang akan ditampilkan ketika menekan action button notification. 

Pada services class NotificationService yang secara umum memiliki beberapa fungsi yaitu fungsi untuk menciptakan notification (createNotification) dan beberapa fungsi-fungsi lain untuk handle listeners. 

## Jenis Notifications
Terdapat beberapa jenis notifications yang saya gunakan. 1) Default notification - notification kosong default, 2) Notification with summary -  notification dengan isian singkat, 3) progress bar notification - notification dengan tampilan suatu bar untuk menunjukan progress (contoh: loading), 4) Message notification - berisi pesan yang bisa dicustom, 5) Big image notification - yang dapat menampilkan gambar bukan tulisan, 6) Action button notification - notification dengan tombol yang pada kasus kita akan membawa user ke SecondScreen, dan 7) Scheduled notification - terdapat parameter interval untuk menampilkan notification berdasarkan selang waktu yang ditentukan.

## Tampilan

![image](https://github.com/user-attachments/assets/bc3b5140-4bbd-490a-801a-a15f1013ea0c)

![image](https://github.com/user-attachments/assets/ba763895-b8f4-40be-92f5-f6e3d768a38b)

![image](https://github.com/user-attachments/assets/bc9155a0-625b-4714-b29d-ce47d39a7638)

![image](https://github.com/user-attachments/assets/1ffd79a8-0832-4688-9b2a-3b41e1c17af9)

![image](https://github.com/user-attachments/assets/db44e8f6-90bc-41c8-b27b-f76bc98e1ab1)




