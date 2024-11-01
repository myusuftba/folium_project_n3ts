# folium_project_n3ts
Interactive Choropleth Map for N3Ts - Geography Project

![colab](https://miro.medium.com/v2/resize:fit:1400/0*XuBHZzSmxp8sKmHC.png)

Untuk mengakses data shapefile administrasi Kelurahan/Desa Indonesia dapat mengunjungi link berikut:
https://drive.google.com/drive/folders/1qyrevPmljtV4j8phJ5xhifij5R7LoZ5A?usp=sharing

Buatlah Shortcut/Pintasan folder tersebut ke Drive Saya/MyDrive

Tutorial Interaktif Map:

1. Buka link Github: https://github.com/ajiahmed95/folium_project_n3ts/tree/main
dan folium_practice_template lalu open in colab, salin ke drive masing-masing.

![aef463525c6e5cd070e38857b8d459d1](https://github.com/user-attachments/assets/aefdc330-f354-4481-b2ec-7b354b64ab33)

2. Buat shortcut/pintasan dari folder drive di atas.

   ![afa3684155adf14cfbab8b3d87511e60](https://github.com/user-attachments/assets/b237b9e9-de71-4cfa-9ceb-790380857504)

3. Untuk memulai pembuatan peta, lakukan run setiap code block dari atas.

   ![30178aec2dc3f7d6cea4187739222da1](https://github.com/user-attachments/assets/aa126e34-627c-4ea4-965f-adf97eef9990)

4. Pilih wilayah Kabupaten/Kota yang akan kalian pilih dan ganti pada Text 'Kota Tangerang Selatan'.
   *Pastikan sudah membuat shortcut folder drive pada akun gmail kalian (step nomor 2).
   ![ebf3a30059755c1195f03fb4ddaaa72c](https://github.com/user-attachments/assets/e1aa1d76-2e40-46a2-b023-ab1ab2ffc87a)

5. Upload data jumlah penduduk/KK per kelurahan yang diperoleh dari BPS / satudata dalam bentuk .csv
  (jika file dibuat dengan kolom pada cell 1 dan delimited default, maka pada variable csv_data, cukup ditulis (csv_path) dan hapus dari ',' header dan delimiter nya.
   ![5c393184b080f2ab344ff9d08077b975](https://github.com/user-attachments/assets/44c0f1df-0b10-4cb7-8017-8088ac99dc6f)

6. Sesudah upload csv, pastikan penamaan list seperti 'Kelurahan' atau 'Jumlah_KK' sudah sesuai dengan data yang kalian upload,
   jika belum maka ubah sesuai dengan judul kolom tabel csv yang kalian upload.
   
7. Jika sudah maka lakukan run code block untuk melakukan join/merge data shp dengan data csv
8. Jika join sudah berhasil, lanjut ke code block selanjutnya. Ubah koordinat sesuai dengan titik pusat wilayah yang kalian pilih. Serta sesuaikan penamaan list seperti pada proses penamaan diproses join/merge.
   ![825f1cf5a6ce520f58ffde69843b0c86](https://github.com/user-attachments/assets/45ac84e9-9716-440b-8b39-b8ce749afe8f)

9. Jalankan code dan peta akan ditampilkan seperti berikut:
    ![d032b3ed603fdd7b63115d99d5e3a961](https://github.com/user-attachments/assets/2e70921a-d662-4f4a-b8c7-c4015058864c)



