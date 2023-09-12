# Todo Apps

## Config
Silahkan buat file `.env` yang di ambil dari `.env.example` kemudian isi sesuai keadaan device masing-masing

## Database Postgres
Buat lah database dahulu sesuai yang di atur di `.env`. Setelah itu jalankan migrate dengan cara mengganti pada bagian `.env` seperti berikut:
```env
ENV=migration
```

Setelah itu ketikkan perintah berikut:
```bash
make dev
```

Jika sudah ubah menjadi berikut:
```env
ENV=dev
```

## Run Project
Untuk menjalankan project silahkan pilih apps sesuai sistem operasi teman-teman `windows`, `linux` atau `darwmin`. 
Contoh device teman teman menggunakan `linux`:
```bash
./todo_app_linux_amd64
```

Setelah berhasil berjalan akses `swagger` di halaman berikut:
```
/api/v1/swagger/index.html#/
```