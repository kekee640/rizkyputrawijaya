Nama : M.Rizky Putra Wijaya

Kelas : SKU3A

NIM : 09011382530139


# Tugas 1 Sistem Operasi: Tutorial Instalasi Ubuntu Linux

**Nama:** M. Rizky Putra Wijaya  
**NIM:** 09011382530139  
**Kelas:** SKU3A

## Tutorial Install Ubuntu Linux

Dokumentasi ini menjelaskan langkah-langkah menginstal Ubuntu Linux menggunakan **Rufus** dan **flashdisk bootable**, berdasarkan *Tugas 1 Sistem Operasi*.

## Persiapan

Sebelum instalasi, siapkan:

1. **File ISO Ubuntu Linux**, unduh melalui [situs resmi Ubuntu](https://ubuntu.com/download/desktop).

   ![Gambar 1](01-download-ubuntu.png)

2. **Rufus versi Portable**, unduh melalui [situs resmi Rufus](https://rufus.ie/id/).

   ![Gambar 2](02-download-rufus.png)

3. **Flashdisk minimal 16 GB**.
4. **Koneksi internet**.

## Langkah-Langkah Instalasi

### 1. Membuat partisi untuk Ubuntu

Buka **Disk Management** pada Windows, kemudian buat partisi tambahan untuk penyimpanan Ubuntu. Pada dokumen tugas, disarankan membuat partisi **minimal 15 GB**.

![Gambar 3](03-disk-management.png)

Setelah selesai, akan muncul partisi tambahan seperti pada gambar berikut.

![Gambar 4](04-hasil-partisi.png)

### 2. Menyiapkan flashdisk installer dengan Rufus

Buka **Rufus**, lalu:

1. Pilih flashdisk yang akan digunakan sebagai installer.
2. Masukkan **file ISO Ubuntu** pada bagian **Boot selection**.
3. Isi nama flashdisk pada bagian **Volume label**.

![Gambar 5](05-pengaturan-rufus.png)

### 3. Memulai pembuatan bootable USB

Pastikan file ISO dan perangkat penyimpanan tujuan telah dipilih dengan benar, kemudian klik **Start** pada Rufus.

### 4. Menunggu proses Rufus

Tunggu hingga Rufus selesai mengekstrak dan menyalin berkas Ubuntu ke flashdisk yang dipilih.

### 5. Masuk ke BIOS/UEFI

Setelah proses selesai, **restart** laptop atau komputer. Saat perangkat mulai menyala, tekan tombol akses BIOS/UEFI, misalnya **F2** atau **F4**. Tombol yang digunakan dapat berbeda tergantung merek dan model perangkat.

### 6. Mengubah prioritas boot

Pada menu BIOS/UEFI, ubah urutan boot agar **flashdisk bootable Ubuntu** digunakan sebagai perangkat boot utama, bukan Windows.

### 7. Mengikuti proses instalasi Ubuntu

Simpan pengaturan boot, lalu ikuti instruksi pada layar instalasi Ubuntu hingga masuk ke tampilan awal Linux.

### 8. Mengikuti pengaturan awal Ubuntu

Setelah proses instalasi, Ubuntu akan menampilkan informasi dan pengaturan awal sistem.

### 9. Menyelesaikan konfigurasi

Lanjutkan konfigurasi dengan membuat atau mengisi akun pengguna, mengunduh aplikasi bawaan yang diperlukan, mengatur Wi-Fi, dan menyelesaikan preferensi personal lainnya.

### 10. Selesai

Jika semua langkah berhasil, Ubuntu siap digunakan dan akan menampilkan desktop seperti berikut.

![Gambar 6](06-tampilan-ubuntu.png)

## Catatan Penting

> **Tambahan untuk keamanan:** Membuat USB bootable menggunakan Rufus dapat menghapus data pada flashdisk. Pastikan data penting telah dicadangkan dan perangkat tujuan dipilih dengan benar. Mengubah partisi juga berisiko terhadap data, sehingga sebaiknya lakukan pencadangan sebelum memulai.
>
> Angka minimal 15 GB untuk partisi di atas mengikuti dokumen tugas; kebutuhan ruang penyimpanan sebenarnya dapat bergantung pada versi Ubuntu dan aplikasi yang dipasang.

## Sumber

Dokumen asli: **Tugas 1 Sistem Operasi — Tutorial Install Ubuntu Linux** (M. Rizky Putra Wijaya, kelas SKU3A). Seluruh tangkapan layar pada panduan ini diambil dari dokumen tersebut.
