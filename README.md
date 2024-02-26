### **💡 Tentang Aplikasi**

---

![Preview Image](-- FOTO REVIEW --)

> Aplikasi POS atau point of sales adalah aplikasi yang digunakan untuk mengelola transaksi pada sebuah toko atau oleh kasir. Aplikasi ini dibuat menggunakan Laravel v5.8 dan minimal PHP v7.1 jadi apabila pada saat proses instalasi atau penggunaan terdapat error atau bug kemungkinan karena versi dari PHP yang tidak support.

### **🙇 Anggota Magang:**

---

-   Anhar Mukhlis 
-   Danu Adiwidya Brahmantara
-   Agung Dwi Firmansyah

### **📝 To-Do List**

---

-   [ ] Manajemen Bank Data
-   [ ] Manajemen Dokumen Data Center
-   [ ] Manajemen Admins
-   [ ] Manajemen Users
-   [ ] Tampilan Profiles
-   [ ] Tampilan Bank Data
-   [ ] Tampilan Data Center Keseluruhan

### **🕙 Instalasi & Kolaborasi**

---

1. Clone repository
    
    ```bash
    git clone https://github.com/anharsaja/Data-Center-Wuluhan
    ```

2. Masuk ke folder repository
    
    ```bash
    cd Data-Center-Wuluhan
    ```

3. Install dependency
    
    ```bash
    composer update
    composer install
    ```

4. Copy file `.env.example` menjadi `.env`
    
    ```bash
    cp .env.example .env
    ```

5. Generate key
    
    ```bash
    php artisan key:generate
    ```

6. Buat database baru dengan nama `datacenter` (sesuaikan dengan nama database yang ada di file `.env`) melalui phpmyadmin atau terminal
    
    ```bash
    mysql -u root -p
    create database datacenter;
    exit;
    ```

7. Migrasi database
    
    ```bash
    php artisan migrate
    ```
    
8. Lakukan seeding data
    
    ```bash
    php artisan db:seed
    ```

9. Jalankan server
    
    ```bash
    php artisan serve
    ```

10. Buka browser dan akses `http://localhost:8000`

11. Buat perubahan
12. Tambahkan perubahan ke repository
    
    ```bash
    git add .
    ```

13. Commit perubahan
    
    ```bash
    git commit -m "pesan commit"
    ```

14. Push ke repository
    
    ```bash
    git push origin main
    ```

15. Lakukan Sync dengan Repository Utama
    
    ```bash
    git pull
    ```

### **🗒 Catatan :**

---

-   Jika ada perubahan pada repository utama, maka lakukan langkah 5 untuk mengambil perubahan tersebut.
-   Jika ada konflik pada langkah 5, maka selesaikan konflik (Diskusikan di Grup)