# Aplikasi Mengidentifikasi status bencana banjir

Banjir bisa menjadi bencana yang bisa di bilang biasa ataupun bencana yang paling berbahaya, namun terkadang untuk mengidentifikasi bahaya pada banjir masih tergolong membingungkan. Kelas ini menyediakan metode untuk mengidentifikasi status banjir denganmenggunakan tinggi banjir dalam metode `main`. Dokumentasi ini akan menjelaskan cara menggunakan kelas Status_Banjir dan memberikan informasi tentang struktur kode

## Penggunaan
untuk menggunakan kelas `Status_Banjir`, anda dapat mengikuti langkah-langkah berikut :

1. **Menjalankan Aplikasi** : Buat objek `Status_Banjir` dengan menyediakan nilai dari tinggi banjir.
    ```java
    Status_Banjir floodStatus = new Status_Banjir(height);
    ```

    Gantilah nilai `height` dengan angka yang mengindikasikan tinggi banjir saat ini.

2. **Indikasikan Status Banjir** : Panggil metode `check_status()` yang telah dibuat untuk memasukkan status yang sesuai dengan tinggi banjir.
    ```java
    floodStatus.check_status();
    ```
    Atribut status akan berubah sesuai dengan tinggi banjir.

3. **Menampilkan Hasil** : kita dapat menampilkan hasil status dengan memanggil metode `show_attributes` yang telah dibuat dalam kelas `Status_Banjir` dan tampilan perintahnya seperti berikut :
    ```java
    System.out.println("Flood height is : " + flood_height);
    System.out.println("Status is : " + status);
    ```

## Contoh Penggunaan 
Misalnya, jika kita menjalankan program ini dan memasukkan tinggi banjir 30, maka akan mendapatkan hasil :

    Input flood height : 30
    Flood height is : 30
    Status is : Alert level 1

hasil itu menunjukkan bahwa tinggi banjir adalah 30 dan statusnya adalah "Alert Level 1", sesuai dengan kriteria yang telah ditentukan dalam kelas `Status_Banjir`.

## Lisensi

Proyek ini dilisensikan di bawah [Lisensi MIT](LICENSE).