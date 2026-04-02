Tugas Laporan Praktikum : Modul 4 
Deadline : Selasa, 7 April 2026, Pukul 23.59WIB

Encapsulation
SOAL CERITA
Dalam game Mobile Legends: Bang Bang, setiap hero memiliki kemampuan bertarung yang berbeda. Sebuah tim developer ingin membuat sistem sederhana untuk melakukan simulasi pertarungan antar hero. Namun, ditemui beberapa masalah seperti :
    • Banyak programmer sebelumnya mengubah Helath Point (HP) dan mana secara langsung, 
    • HP bisa tiba-tiba negative
    • Mana dan HP bisa melebihi batas
    • Hero yang sudah kalah (HP = 0) masih bisa menyerang.
Untuk menjaga konsistensi sistem:
    • Data awal hero harus diinisialisasi melalui constructor
    • Dan perubahan data hanya boleh melalui method (encapsulation)
TUGAS MAHASISWA
    1. Buat class Hero dengan atribut: nama (String) , hp (int) , mana (int) , damage (int), semua atribut harus bersifat private.
    2. Memastikan setiap hero memiliki nilai awal yang valid saat dibuat.
        a. Hp minimal 0 maksimal 100
        b. Mana minimal 0 maksimal 100
        c. Damage minimal 0 maksimal 15
    3. Mengatur bagaimana hero bisa “menyerang” dengan ketentuan :
        a. Saat seorang hero menyerang hero lain damage yang diberikan berasal dari nilai damage dasar hero tersebut 
        b. HP musuh akan berkurang sesuai damage 
        c. HP tidak boleh kurang dari 0 
    4. Mengatur bagaimana hero bisa “menggunakan skill” dengan ketentuan :
        a. Skill adalah serangan khusus yang lebih kuat, tetapi Menggunakan sejumlah mana sebanyak 25 
        b. Damage yang diberikan lebih besar dari serangan biasa sebesar 2× damage
    5. Mengatur bagaimana hero bisa “heal/regen” dengan ketentuan :
        a. Menambah HP sebanyak 15
        b. Jika HP sudah maksimum tidak bisa melakukan regen
    6. Hero dapat menimpilkan status atribut dan ada keterangan DEAD ketika HP = 0 dan ALIVE ketika HP > 0
    7. Tidak boleh ada setter untuk: hp,mana, damage sedangkan nama tidak boleh diubah setelah object dibuat.

Deadline : Selasa, 7 April 2026, Pukul 23.59WIB
