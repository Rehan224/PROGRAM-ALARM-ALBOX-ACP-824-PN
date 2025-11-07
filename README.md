**PROGRAM-ALARM-ALBOX-ACP-824-P-N**
```markdown
> Default Master Code : 123456
> Default User Code : 147258
> Masuk Program : "ENTER" "Master_Code" "OK"
> Keluar Program : "ABC" "EXIT 3X"
> Lupa Master Code :
   - Pindahkan posisi Dipswitch 1 pada
     panel alarm ke posisi ON
   - Masuk Program, "ENTER" "000000" OK
   - Ubah Master Code di program 08
   - Setelah selesai, ubah kembali
     posisi Dipswitch ke 1
```
- Cara Mengganti Master Code
  - Masuk Program
  - [08]
  - Tekan OK
  - Isi Master Code baru (6 digit)
  - Tekan OK (untuk simpan program)
    
- Cara Membuat/Mengganti User Code
  - Masuk Program
  - [09]
  - Tekan OK
  - Isi User Code baru (Min. 6 digit)
  - Tekan OK (untuk simpan program)
    
- Cara Mengatur Zona
  ```
  Note:
  Jika ingin program zona, pertama
  harus diketahui, rencana ingin
  menggunakan zona apa,
  
  Contoh:
  Zona 1, Zona Delay,
  Zona 2 dan 3, Zona 24 jam,
  Zona 4, 5, dan 6, Zona Instant,
  Zona 7 dan 8, Zona 24 jam,

  - Kosongkan program [16],
  dengan cara [16] "OK" "#" "OK"
  - Jika ada zona 24 jam, jangan
  masukkan ke Program [15], jadi zona
  yg dimasukkan di Program [15], zona
  delay & instant, kecuali zona 24 jam
  - Jika pada saat sedang mendaftarkan
  zona di Program [15], tetapi zona
  tersebut masih terdaftar di Program
  [16], otomatis zona tersebut tidak
  akan bisa terdaftar di Program [15],
  jadi disarankan sebelum mendaftarkan
  zona ke Program [15], harus mengosongkan
  zona di Program [16]
  
  ```
  Berikut Program Zona Berdasarkan contoh:
  - Periemter Zone (Zona bagian luar,
    jika alarm mode stay/home)
    - Masuk Program 
    - [16]
    - Tekan OK
    - #
    - Tekan OK (untuk simpan program)
      
  - Global Zone Kecuali Zona 24 jam
    - Masuk Program
    - [15]
    - Tekan OK
    - Masukkan Zona (1456), kecuali zona 24 jam
    - Tekan OK (untuk simpan program)

  - Delay Zone
    - Masuk Program
    - [18]
    - Tekan OK
    - Masukkan Zona delay (1)
    - Tekan OK (untuk simpan program)

  - Aktifkan Zona Instant
    - Masuk Program
    - [24]
    - Tekan OK
    - 1 (untuk aktif zona instant, jika
      ingin mematikan zona instant, isi 3)
    - 0 (matikan deteksi kesalahan
      saluran telpon)
    - Tekan OK (untuk simpan program)

- Cara Mengatur Waktu Sirine
  - Masuk Program
  - [10]
  - Tekan OK
  - Isi durasi sirine (2 digit) dalam satuan menit
  - Tekan OK (untuk simpan program)

- Cara Mengatur Entry Delay
  - Masuk Program
  - [14]
  - Tekan OK
  - Isi durasi Entry Delay (2 digit)
    (satuan detik di kali 3, contoh
    01 berarti 3 detik)
  - Tekan OK (untuk simpan program)

- Cara Mengatur Exit Delay
  - Masuk Program
  - [13]
  - Tekan OK
  - Isi durasi Exit Delay (2 digit)
    (satuan detik di kali 3, contoh
    01 berarti 3 detik)
  - Tekan OK (untuk simpan program)

- Cara Menambahkan Nomor HP
  - Masuk Program
  - [01]
  - Tekan OK
  - Isi Nomor HP
  - Tekan OK (untuk simpan program)
    ```
    Note:
    > Untuk Menambahkan nomor HP bisa sampai 6 nomor HP
    > Ganti code [01] jadi [02], [03], [04], [05], [06]
    > Jadi nanti urutannya,
    [01] untuk nomor pertama
    [02] untuk nomor kedua
    [03] untuk nomor ketiga
    [04] untuk nomor keempat
    [05] untuk nomor kelima
    [06] untuk nomor keenam
    ```
---
- Pengetesan Alarm
  - Cara Mengaktifkan Alarm
    - Tekan tombol gembok terkunci 🔒
      
  - Cara Mematikan alarm
    - Tekan tombol gembok terbuka 🔓
    - Masukkan User_Code
    - Tekan OK
    - Tekan EXIT 2x
      
  - Cara Mematikan Sirine
    - Tekan tombol gembok terbuka 🔓
    - Masukkan User_Code
    - Tekan OK
    - Tekan EXIT 2x
      
  - Cara Hapus Ter-memori
    - Tekan tombol gembok terbuka 🔓
    - Masukkan User_Code
    - Tekan OK
    - Tekan EXIT 2x
---
```markdown
KETERANGAN:
CF = Alarm tidak aktif
BF = Alarm aktif
PA = Alarm Darurat (tombol Panic Alarm
     tekan 3x untuk mengaktifkan)
P1 - P8 = Angka sesuai zona yg trigger
PB = Temper keypad 
```
