### Tugas pertemuan 4

# Mata Kuliah Pemrograman Aplikasi Bergerak

Nama: Adella Putri

NIM: 2409116006

Kelas : A Sistem Informasi 2024

## EKSPERIMEN 5: Test Cart Operations

## 1. Tampilan Awal Aplikasi

<img height="500"  alt="iPhone-14-Plus-localhost (4)" src="https://github.com/user-attachments/assets/04b09ebc-f7f3-42ee-90c4-3e5c38e53b3b" />

Pada tampilan awal aplikasi, pengguna langsung disuguhkan halaman utama yang menampilkan daftar produk yang tersedia untuk dibeli. Produk ditampilkan dalam bentuk grid dengan informasi singkat seperti nama produk, harga, serta tombol Add di bagian bawah setiap kartu produk.

Tombol Add berfungsi untuk menambahkan produk yang dipilih ke dalam keranjang belanja (cart). Selain itu, pada bagian pojok kanan atas terdapat ikon keranjang yang dilengkapi dengan indikator jumlah item. Indikator ini akan menampilkan angka sesuai jumlah produk yang telah dimasukkan ke dalam keranjang.

Tampilan awal ini dirancang agar pengguna dapat dengan mudah melihat dan memilih produk yang diinginkan sebelum melanjutkan ke proses berikutnya.

---

### Add Product 3x

<img height="500" alt="iPhone-14-Plus-localhost (2)" src="https://github.com/user-attachments/assets/be8d707d-fe53-4727-95a0-db579cc535bb" />

Ketika tombol Add ditekan pada salah satu produk, misalnya Laptop Gaming, maka sistem akan langsung menambahkan produk tersebut ke dalam keranjang.

Setiap kali tombol Add ditekan:

- Angka indikator pada ikon keranjang di pojok kanan atas akan bertambah secara otomatis.

- Jika produk yang sama ditambahkan sebanyak tiga kali, maka indikator pada ikon keranjang akan menunjukkan angka 3.

- Sistem akan menghitung jumlah produk yang sama sebagai penambahan kuantitas, bukan sebagai item baru yang berbeda.

Hal ini menunjukkan bahwa sistem telah mampu mengelola penambahan kuantitas produk secara akurat dan real-time.

<img height="500" alt="iPhone-14-Plus-localhost (3)" src="https://github.com/user-attachments/assets/273ee94f-61a6-4f97-abc7-dfd3d1608fae" />

Ketika ikon keranjang ditekan, pengguna akan diarahkan ke halaman keranjang. Pada halaman ini akan terlihat daftar produk yang telah dimasukkan. Dalam contoh ini, terlihat bahwa produk Laptop Gaming memiliki jumlah sebanyak 3 item, sesuai dengan jumlah tombol Add yang ditekan sebelumnya.

---

## 2. Add Different Products

<img height="500" alt="iPhone-14-Plus-localhost (5)" src="https://github.com/user-attachments/assets/22f2fe70-6cb7-4dea-9628-eb9711aacc88" />

Selain menambahkan produk yang sama, pengguna juga dapat menambahkan beberapa jenis produk yang berbeda ke dalam keranjang.

Sebagai contoh, saya menambahkan:

- Smartphone Pro
- Smart Watch
- Wireless Headphones

Dalam kondisi ini:

- Ikon keranjang akan menampilkan angka sesuai total seluruh item yang telah dimasukkan.
- Sistem mampu menyimpan lebih dari satu jenis produk dalam satu transaksi.
- Setiap produk akan tercatat secara terpisah di dalam keranjang.

<img height="500" alt="iPhone-14-Plus-localhost (6)" src="https://github.com/user-attachments/assets/e8123525-87bb-4efa-8bfa-28e7c1e7a2dc" />

Pada halaman keranjang, seluruh produk yang telah dipilih akan ditampilkan lengkap dengan jumlah masing-masing. Hal ini membuktikan bahwa sistem dapat menangani berbagai variasi produk sekaligus tanpa terjadi kesalahan pencatatan.

Fitur ini penting karena dalam transaksi nyata, pengguna hampir selalu membeli lebih dari satu jenis produk dalam satu waktu.

---

## 3. Increase Quantity

<img height="500" alt="iPhone-14-Plus-localhost (7)" src="https://github.com/user-attachments/assets/9cce39de-368c-4bc8-b5cc-512e6a689d80" />


Pengguna juga diberikan fleksibilitas untuk menambah jumlah produk langsung dari halaman keranjang. Fitur ini tersedia melalui tombol "+" yang terdapat di samping setiap produk.

Sebagai contoh:

Produk Smart Watch yang awalnya berjumlah 1 dapat ditingkatkan menjadi 2 dengan menekan tombol "+".

Setiap kali tombol "+" ditekan:

- Jumlah produk akan bertambah satu.
- Total harga keseluruhan akan otomatis diperbarui.
- Perubahan terjadi secara dinamis tanpa perlu memuat ulang halaman.

Fitur ini menunjukkan bahwa sistem telah menerapkan perhitungan harga secara otomatis berdasarkan perubahan kuantitas produk.

---

## 4. Decrease to 1

<img height="500" alt="iPhone-14-Plus-localhost (8)" src="https://github.com/user-attachments/assets/1d5a3cf3-de26-498d-903e-a6f040de5c82" />

Untuk mengurangi jumlah produk, pengguna dapat menekan tombol "-" pada produk yang diinginkan.

Sebagai contoh:

Tablet Pro yang sebelumnya memiliki jumlah lebih dari satu dapat dikurangi hingga tersisa 1 item.

<img height="500" alt="iPhone-14-Plus-localhost (9)" src="https://github.com/user-attachments/assets/d3fd2425-50f0-47a0-b483-878f7c944a70" />

Setiap kali tombol "-" ditekan:

- Jumlah produk akan berkurang satu.
- Total harga akan diperbarui secara otomatis sesuai jumlah terbaru.
- Sistem tetap menjaga konsistensi data di dalam keranjang.

Fitur ini memberikan kontrol penuh kepada pengguna untuk menyesuaikan jumlah pembelian sebelum melakukan transaksi.

---

## 5. Decrease to 0

<img height="500" alt="iPhone-14-Plus-localhost (10)" src="https://github.com/user-attachments/assets/eb17fc9e-0578-4f41-ab56-f4e41e2a32f3" />


Jika tombol "-" terus ditekan hingga jumlah produk mencapai angka 0, maka sistem akan secara otomatis menghapus produk tersebut dari daftar keranjang.

Dengan kata lain:

- Tidak diperlukan tombol hapus terpisah untuk setiap produk.
- Produk akan langsung terhapus ketika kuantitasnya mencapai 0.
- Tampilan keranjang akan diperbarui secara otomatis.

Fitur ini memudahkan pengguna dalam mengelola isi keranjang secara praktis dan efisien.

---

## 6. Clear All Items

<img height="500" alt="iPhone-14-Plus-localhost (12)" src="https://github.com/user-attachments/assets/ffb5144e-e230-4f48-8670-304606bdd560" />

Aplikasi juga menyediakan fitur untuk menghapus seluruh isi keranjang sekaligus melalui ikon tong sampah yang terletak di pojok kanan atas halaman keranjang.

Langkah-langkahnya sebagai berikut:

1. Tekan ikon tong sampah.
2. Akan muncul dialog konfirmasi sebagai bentuk validasi tindakan.
3. Pilih Cancel jika ingin membatalkan.
4. Pilih Clear jika ingin menghapus seluruh isi keranjang.

<img height="500" alt="iPhone-14-Plus-localhost (10)" src="https://github.com/user-attachments/assets/eb17fc9e-0578-4f41-ab56-f4e41e2a32f3" />

Setelah tombol Clear dipilih:

- Semua produk yang ada di dalam keranjang akan terhapus.
- Indikator jumlah pada ikon keranjang akan kembali kosong.
- Ikon tong sampah tidak lagi muncul karena tidak ada item yang dapat dihapus.
- Halaman keranjang akan kembali ke kondisi kosong.

Fitur konfirmasi ini bertujuan untuk mencegah penghapusan data secara tidak sengaja.

---

## 7. Navigate Back

<img height="500"  alt="iPhone-14-Plus-localhost (4)" src="https://github.com/user-attachments/assets/04b09ebc-f7f3-42ee-90c4-3e5c38e53b3b" />

Pada halaman keranjang juga tersedia tombol Continue Shopping yang memungkinkan pengguna kembali ke halaman utama untuk melanjutkan proses pemilihan produk.

Jika sebelumnya keranjang telah dikosongkan:

- Indikator jumlah pada ikon keranjang tidak akan menampilkan angka.
- Sistem kembali ke kondisi awal.
- Pengguna dapat memulai kembali proses pemilihan produk dari awal tanpa gangguan.

Fitur navigasi ini memastikan pengalaman pengguna tetap nyaman dan fleksibel selama menggunakan aplikasi.
