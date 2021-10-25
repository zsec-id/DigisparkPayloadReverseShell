# Make BAD USB to Reverse Shell with Arduino Digispark **(recommended with attiny85)**

## Cara Pakai
**Pastikan Anda telah menginstal Driver Digispark dan mengonfigurasi Arduino IDE Anda sebelum mencoba script ini.**
1. Ganti IP & Port sesuai dengan target netcat kamu di 'reversescript.PS1'
2. Upload reversescript.PS1 ke Pastebin/Paste eviltwin , raw dan salin link tersebut. 
3. Ganti 'REMOTESCRIPTURL' dengan link raw paste yang kamu salin tadi di line 37 didalam 'yamano.ino'
4. Buka dan upload 'yamano.ino' via Arduino IDE untuk digispark milikmu.
5. Buatlah netcat target . `nc -v -n -l -p PORT`
6. Apabila sudah jalankan script ter

## Apa yang dilakukan
- Menonaktifkan Windows Defender untuk memungkinkan koneksi Reverse Shell antara korban dan server.
- Membuat koneksi Reverse Shell menggunakan script Powershell yang dihosting secara online.
- Bypass UAC
- Tersembunyi dari bilah tugas dan tidak membuka jendela yang terlihat.
- Menghapus riwayat run box dari registry.

## Thanks for Daniel J Lawson
