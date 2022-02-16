# TodoApp

Repo ini berisi test assignment untuk calon Back-End Engineer

## Struktur Repo dan Dokumen Tambahan

| path                                                                                                                     | content             | description                                 |
| ------------------------------------------------------------------------------------------------------------------------ | ------------------- | ------------------------------------------- |
| ./todo-app                                                                                                               | compiled angular FE | Web tampilan sebagai sarana validasi test   |
| [API Requirement Docs](https://docs.google.com/document/d/1HD9JKbH0g4XKj3wChmH9O6o-qv3bqeaLGLLjyB8glm8/edit?usp=sharing) | Google Docs Link    | Docs berisi Kriteria API yang harus di buat |

## Tentang Assignment

1. Buat aplikasi Back-End sesuai kriteria [API Requirement Docs](https://docs.google.com/document/d/1HD9JKbH0g4XKj3wChmH9O6o-qv3bqeaLGLLjyB8glm8/edit?usp=sharing) dengan Framework sesuai preferensi masing-masing.
2. Test Jalan API yang sudah di buat di local dengan menggunakan Web yang ada di repo ini. ( cara installasi dan running ada di bawah )
3. Batas waktu pengerjaan 3 hari, setelah itu kirim Email ke: anon@email.com berisi :

   Subject :

   ```
   NAMA - POSISI - HASIL TEST
   ```

   Isi :

   ```
   Nama : Anon
   Posisi : Back-End 1
   Repo : https://github.com
   Keterangan : ( Penjelasan singkat tentang Framework yang di pakai, db yang dipakai, atau teknologi lain yang di pakai, dll )

   ```

   Attachment

   ```
   - Diagram struktur DB
   - dll
   ```

## Running Web Tampilan di Local

Note : Web memerlukan API sesuai ketentuan untuk bisa berjalan.

Step instalasi :

1. Pertama perlu set-up Node.JS di local machine [Link Download Node.JS](https://nodejs.org/en/download/) jika belum ada.
2. Lalu install [lite-server](https://github.com/johnpapa/lite-server) sebagai web server dengan command :

```
# run on command prompt/terminal

npm install --global lite-server
```

3. Lalu buka file "./todo-app/assets/project_config.json" dan ganti value "Main_Url" sesuai url root API kalian

```
{
    "Main_URL": YOUR API URL HERE
}
```

5. Setelah selesai, buka command prompt, set lokasi command prompt di root folder repository dan jalankan command :

```
# run on command prompt/terminal

lite-server --baseDir="./todo-app"
```

4. Ketika selesai eksekusi web akan terbuka otomatis di browser default. Kalian bisa jalankan API yang sudah di buat dan mulai test dengan web ini.
