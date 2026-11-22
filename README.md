# progresskelompok
progressk6
# Progress PBL – Pengujian Pemisahan Akses Antar Tenant

**Nama:** Bias Seftian Saputra  
**NIM:** 2407421026

Pada progress kali ini, saya melakukan pengujian terhadap pengaturan hak akses pada sistem Private Cloud Storage yang telah dikonfigurasi menggunakan Nextcloud. Pengujian ini dilakukan untuk memastikan bahwa setiap tenant tidak dapat mengakses data maupun folder milik tenant lainnya. Selain itu, pengujian juga dilakukan terhadap akun TU untuk melihat batasan akses yang diterapkan pada akun tersebut.

Pengujian pertama dilakukan dengan mencoba mengakses folder penyimpanan dari tenant lain menggunakan akun tenant yang berbeda. Dari pengujian tersebut, dilakukan pengecekan apakah pengguna dapat melihat maupun membuka folder yang bukan menjadi bagian dari tenantnya. Pengujian ini bertujuan untuk memastikan bahwa pembagian akses folder yang telah dikonfigurasi dapat berjalan sesuai dengan rancangan, sehingga data antar tenant tetap terpisah.

Selanjutnya, saya melakukan pengujian pada akun TU melalui browser. Pengujian ini dilakukan dengan melihat apakah akun TU dapat melihat atau mengakses akun tenant lain yang berada di dalam sistem. Dalam pengujian tersebut, akun TU hanya dapat melihat akun tenant yang sesuai dengan username TU yang digunakan, sedangkan akun tenant lainnya tidak dapat ditampilkan atau diakses melalui akun tersebut.

Pengujian ini dilakukan untuk mengetahui apakah pengaturan akses yang diterapkan sudah membatasi visibilitas akun dan data sesuai dengan pembagian yang telah dibuat. Dengan adanya pembatasan tersebut, diharapkan setiap tenant dapat menggunakan layanan penyimpanan tanpa dapat melihat atau mengakses data milik kelompok lain, serta akun TU memiliki batasan akses sesuai dengan konfigurasi sistem.

Dari pengujian yang telah dilakukan, pembatasan akses antar tenant dan visibilitas akun pada akun TU telah diperiksa sesuai dengan skenario yang diterapkan. Pengujian ini menjadi bagian dari penerapan keamanan pada sistem Private Cloud Storage dengan arsitektur multi tenant, khususnya dalam menjaga pemisahan data dan membatasi akses pengguna.

Untuk tahap selanjutnya, pengujian akan dilanjutkan dengan mencoba aktivitas upload dan download file pada setiap tenant, serta memastikan bahwa file yang disimpan hanya dapat diakses oleh pengguna yang memiliki hak akses terhadap folder tersebut.
