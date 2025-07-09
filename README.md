# EVM-Wallet-Generator

Proyek EVM Wallet Generator ini adalah sebuah utilitas berbasis Python yang dirancang untuk menghasilkan pasangan kunci publik-privat yang kompatibel dengan jaringan Ethereum Virtual Machine (EVM). Tujuannya adalah untuk menyediakan cara yang cepat dan terotomatisasi dalam membuat alamat wallet baru beserta private key-nya.

Aplikasi ini memecahkan masalah kebutuhan akan pembuatan wallet dalam jumlah besar, yang mungkin diperlukan untuk berbagai keperluan seperti pengujian dApps, riset blockchain, atau kebutuhan pengembangan lainnya. Proses pembuatan wallet dilakukan secara lokal dan deterministic, memastikan keamanan private key selama proses generation.

Pengguna utama dari proyek ini adalah developer, peneliti, atau siapa saja yang membutuhkan kemampuan untuk menghasilkan multiple EVM wallets secara efisien tanpa interaksi manual dengan wallet interface konvensional.

## Features

*   **Fast Wallet Generation:** Menghasilkan pasangan kunci publik-privat secara cepat dan efisien.
*   **EVM Compatibility:** Wallet yang dihasilkan kompatibel dengan semua jaringan Ethereum Virtual Machine.
*   **Deterministic Generation:** Memastikan pembuatan wallet yang deterministik untuk reproduksi yang konsisten.
*   **Local Operation:** Operasi sepenuhnya lokal, tidak ada kunci yang dikirim ke server eksternal.

## Getting Started

Petunjuk berikut akan membantu Anda menyiapkan dan menjalankan proyek ini di lingkungan lokal Anda.

### Requirements

Pastikan Anda memiliki software berikut terinstal di sistem Anda:

*   Python 3.6 atau versi yang lebih baru
*   pip (Python package installer), biasanya sudah termasuk dalam instalasi Python

### Installation

Ikuti langkah-langkah ini untuk menginstal proyek:

1.  Clone repository ini ke mesin lokal Anda menggunakan git clone:

    ```bash
    git clone https://github.com/BlocksCrew/EVM-Wallet-Generator.git
    ```
2.  Masuk ke direktori proyek:

    ```bash
    cd EVM-Wallet-Generator
    ```
3.  Instal dependensi yang diperlukan menggunakan pip install dengan file requirements.txt:

    ```bash
    pip install -r requirements.txt
    ```

## Run

Setelah instalasi selesai, Anda dapat menjalankan skrip untuk mulai menghasilkan wallet.

Jalankan skrip utama index.py dari root directory proyek:

```bash
python index.py
```

Output akan menampilkan daftar alamat wallet dan private key yang dihasilkan.
