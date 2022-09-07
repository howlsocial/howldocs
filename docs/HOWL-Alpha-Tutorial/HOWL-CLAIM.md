## Pasca Instalasi
Selanjutnya Anda harus memastikan validator Anda menyinkronkan blok. Anda dapat menggunakan perintah di bawah ini untuk memeriksa status sinkronisasi
console
sourced status 2>&1 | jq .SyncInfo
## Membuat Wallet
Untuk membuat dompet baru Anda dapat menggunakan perintah di bawah ini. Jangan lupa simpan mnemonicnya
console
sourced keys add wallet
(OPSIONAL) Untuk memulihkan dompet Anda menggunakan frase seed
console
sourced keys add wallet --recover
Untuk mendapatkan daftar dompet saat ini
console
sourced keys list
