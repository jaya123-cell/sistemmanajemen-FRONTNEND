# Kostanversi2 - Frontend Only

Project ini hanya berisi frontend React + Vite.

## Menjalankan di VS Code
1. Buka folder `kostanversi2-frontend` di VS Code.
2. Buka Terminal.
3. Jalankan:
   `npm install`
4. Setelah selesai jalankan:
   `npm run dev`
5. Buka alamat localhost yang ditampilkan Vite (biasanya http://localhost:5173).

Catatan: frontend masih memiliki service API yang mengarah ke `http://localhost:5000/api`. Jadi tampilan frontend dapat dijalankan tanpa folder backend, tetapi fitur yang mengambil/menyimpan data melalui API (login, kamar, keuangan, penghuni, dll.) memerlukan backend yang sesuai.
