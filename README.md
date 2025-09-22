# 🚀 ditzz Ultimate RDP Workflow - Selamat Datang di Versi 7!

Lupakan semua yang Anda tahu tentang versi sebelumnya. Ini bukan sekadar pembaruan; ini adalah **lompatan kuantum**. Dari skrip v4 yang fungsional namun kaku, kita telah berevolusi menjadi sebuah platform RDP dinamis yang memberikan **kendali penuh** di tangan Anda.

Versi 7 mengubah alur kerja ini dari sekadar "skrip" menjadi "layanan pribadi" Anda untuk membuat lingkungan Windows berperforma tinggi sesuai permintaan, tepat seperti yang Anda inginkan, setiap saat.

---

## 🔥 Evolusi dari v4 ke v7: Sebuah Lompatan Besar

Jika Anda datang dari versi lama, Anda akan merasakan perbedaannya secara dramatis. Mari kita lihat perubahannya:

| Fitur | Versi Lama (v4.x & Sebelumnya) | ✨ Versi 7 (Revolusioner) ✨ |
| :--- | :--- | :--- |
| **Konektivitas** | Ngrok (TCP Tunneling publik) | **Tailscale** (Jaringan pribadi P2P yang aman & stabil) |
| **Kustomisasi** | Statis. Harus edit kode untuk ganti wallpaper/spek. | **Sepenuhnya Dinamis!** Pilih tema, aplikasi & wallpaper dari menu. |
| **Instalasi Software** | Tidak ada. Hanya OS Windows kosong. | **Otomatis!** Pilih untuk menginstal Steam, OBS, Chrome, dll. |
| **Keamanan** | Password di-set di dalam kode (kurang aman). | **Sangat Aman.** Menggunakan GitHub Secrets & kata sandi dibuat otomatis. |
| **Pengalaman Pengguna**| Log teks biasa. Info koneksi di akhir log. | **Antarmuka Keren.** Log berwarna, header bergaya & **halaman ringkasan** rapi. |
| **Fleksibilitas** | Satu ukuran untuk semua. | **Dibuat Sesuai Pesanan.** Butuh sesi ringan tanpa aplikasi? Bisa. Butuh workstation lengkap? Siap! |

---

## ✨ Fitur Unggulan Versi 7

-   **Kendalikan Sesi Anda:** Dengan input `workflow_dispatch`, Anda adalah sutradaranya. Tentukan tema, aplikasi, dan wallpaper bahkan sebelum sesi dimulai.
-   **Konektivitas Tingkat Lanjut dengan Tailscale:** Ucapkan selamat tinggal pada alamat Ngrok yang canggung. Dapatkan IP pribadi yang stabil dan koneksi yang lebih aman serta andal.
-   **Pilih Arsenal Digital Anda:** Cukup centang sebuah kotak untuk menginstal perangkat lunak penting secara otomatis—Steam, OBS Studio, Google Chrome, dan lainnya—diinstal dengan rapi melalui `winget`.
-   **Bangun Desktop Impian Anda:** Tempelkan URL gambar apa pun dan saksikan desktop RDP Anda hidup dengan wallpaper pilihan Anda, secara otomatis.
-   **Kinerja Brutal, Otomatis:** Debloating cerdas, aktivasi Power Plan "Ultimate Performance", dan tweak mouse kini menjadi standar untuk memastikan sesi Anda responsif dan gegas.
-   **Mode Siluman (Stealth Mode) Disempurnakan:** Penyamaran info sistem yang lebih baik untuk membantu melewati deteksi lingkungan virtual yang ketat.

## 🚀 Cara Menggunakan (Lebih Mudah Dari Sebelumnya)

1.  **Fork Repositori Ini:** Jadikan mahakarya ini milik Anda.
2.  **Dapatkan Kunci Autentikasi Tailscale:**
    *   Masuk ke [dasbor Admin Tailscale](https://login.tailscale.com/admin/settings/keys) Anda.
    *   Buat **Auth key** baru (disarankan `Reusable` dan `Ephemeral`).
    *   **Salin kunci tersebut.** Anda hanya akan melihatnya sekali!
3.  **Atur GitHub Secret:**
    *   Di repositori hasil fork Anda, buka **Settings > Secrets and variables > Actions**.
    *   Buat secret baru bernama `TAILSCALE_AUTH_KEY` dan tempelkan kunci Tailscale Anda.
4.  **Jalankan Keajaiban:**
    *   Buka tab **Actions**.
    *   Pilih **ditzz RDP (The Ultimate Build)** dan klik **Run workflow**.
    *   **Ini bagian terbaiknya:** Sebuah menu akan muncul!
        *   Pilih tema **Dark** atau **Light**.
        *   Tentukan apakah Anda ingin **menginstal aplikasi tambahan**.
        *   Tempelkan **URL wallpaper** favorit Anda.
    *   Klik **Run workflow** untuk memulai penciptaan!
5.  **Hubungkan & Nikmati:**
    *   Dalam beberapa menit, buka tab **Summary** dari alur kerja yang berjalan.
    *   Semua detail akses (IP Tailscale, Username, Password) disajikan dengan indah, siap untuk Anda gunakan.

## ⚠️ Peringatan Penting

-   Ini adalah lingkungan sementara (ephemeral). **JANGAN SIMPAN DATA PENTING DI SINI.** Sesi akan hancur total saat alur kerja selesai.
-   Gunakan kekuatan ini dengan bertanggung jawab dan patuhi Ketentuan Layanan GitHub.

Ini bukan lagi sekadar alat. Ini adalah pengalaman. Selamat menikmati kebebasan dan kekuatan **ditzz Ultimate RDP Workflow v7**!
