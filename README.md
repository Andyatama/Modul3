###### Nama      : Achmad Setiawan Andyatama
###### Kelas     : XII-RPL 1
###### No. Absen : 05

# Modul 3 
# Routing

Routing adalah suatu proses pada paket yang meneruskan jaringan dari satu jaringan ke jaringan lainnya melalui internet.

sebelum mengerjakan tugas. pertama-tama mari menganal tentang apa itu route dengan aksi controller

Route ini saat ketika saat dijalankan akan mengakses controller yang disebutkan pada
parameter kedua.

Untuk menjalankan route ini buatlah satu controller dengan menggunakan perintah artisan sebagai berikut:

```
php artisan make:controller BarangController
```

Jalankan perintah artisan diatas pada terminal. Perintah artisan diatas
akan menghasilkan satu file baru bernama BarangController.php yang terletak pada folder app\Http\Controller. buka file controllernya dan tambahkan satu fungsi bernama index seperti pada contoh skrip dibawah ini:

![image](https://user-images.githubusercontent.com/109930523/182102548-c09a6e57-dfbe-4d9b-a20b-0ff2367d25ba.png)

setelah itu pada file web.php yang ada pada folder routes/web.php tambahkan satu route baru dengan code seperti berikut

![image](https://user-images.githubusercontent.com/109930523/182103270-9b82bdb6-a2f6-444d-8bc8-eb634d22a828.png)

## Soal Nomor 1

### Buatlah Route yang menuju kehalaman Kategori!!!

### Langkah Pertama 

Buatlah Controller Kategori terlebih dahulu

![image](https://user-images.githubusercontent.com/109930523/182094376-d37df892-5c75-4f5a-a750-135c04750e87.png)

```
php artisan make:controller KategoriController
```
### Langkah Kedua

setelah membuat KategoriController. Isi Folder nya dengan code seperti di Bawah ini!

![image](https://user-images.githubusercontent.com/109930523/182094823-a3009d1d-9c4d-4c6c-b1c6-914bbcbd8468.png)

hasilnya akan jadi seperti ini

![image](https://user-images.githubusercontent.com/109930523/182104143-f61e7108-2f13-441f-8fa6-13fe52dc170a.png)

## Soal Nomor 2

### Buatlah halaman tambah data di setiap route!!!

tambahkan kode berikut di folder web.php yang terdapat pada folder routes untuk membuat halaman tambah data di setiap route:

![image](https://user-images.githubusercontent.com/109930523/182105346-bdf16bfa-d467-4c84-a51e-2990cbe2d4a1.png)

hasilnya akan jadi seperti berikut:

![image](https://user-images.githubusercontent.com/109930523/182105543-fd5a1035-e396-4e84-bcdd-f34906acdd6a.png)
