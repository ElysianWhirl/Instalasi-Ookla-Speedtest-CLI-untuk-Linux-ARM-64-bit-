# Instalasi Ookla Speedtest CLI untuk Linux (ARM 64-bit)

Ini adalah panduan untuk mengunduh dan menginstal Ookla Speedtest CLI pada sistem Linux dengan arsitektur ARM 64-bit.

## Langkah-langkah

1. Unduh Ookla Speedtest CLI menggunakan wget:
    ```bash
    wget --no-check-certificate https://install.speedtest.net/app/cli/ookla-speedtest-1.1.1-linux-aarch64.tgz -O /tmp/speedtest.tgz
    ```

2. Ekstrak arsip yang telah diunduh ke dalam direktori `/usr/bin/`:
    ```bash
    tar -xzvf /tmp/speedtest.tgz -C /usr/bin/
    ```

3. Berikan izin eksekusi pada file speedtest:
    ```bash
    chmod +x /usr/bin/speedtest
    ```

4. Jalankan perintah speedtest di terminal untuk memulai pengujian kecepatan.

## Catatan

Pastikan untuk menjalankan perintah-perintah di atas sebagai pengguna dengan hak akses sudo atau sebagai pengguna root.
