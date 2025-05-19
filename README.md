# Reflection

## Original Code and How It Runs

![First Image](./images/first-image.jpg)

Untuk menjalankan server dan klien, kita dapat melakukan _step-step_ berikut:

1. Buka 4 terminal terpisah.

2. Atur direktori saat ini ke direktori proyek untuk semua terminal.

3. Pada terminal pertama, jalankan server dengan mengetik `cargo run --bin server`.

4. Pada 3 terminal lainnya, jalankan klien dengan mengetik `cargo run --bin client`.

Ketika sebuah pesan diketik dan dikirim melalui klien, server akan menerima pesan tersebut, lalu mencetaknya dan menyiarkan pesan tersebut ke semua klien. Semua klien kemudian akan menerima pesan tersebut dan mencetaknya ke terminal.