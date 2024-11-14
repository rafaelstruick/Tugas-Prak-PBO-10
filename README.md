1.	Tambahkan fitur Ubah PIN
    a.	Tambahkan opsi “Ubah PIN” pada menu utama:
    ![Cuplikan layar 2024-11-14 224333](https://github.com/user-attachments/assets/15495a6e-6171-488b-9f6c-efeb77b1c7bb)

    b.	Buat mdeo dalam kelas Account untuk mengubah PIN, yaitu: changePin()
    ![Cuplikan layar 2024-11-14 224333](https://github.com/user-attachments/assets/6daef39e-665a-4c3a-b49e-765a7fb6c71f)

    c.	Dalam method tersebut lakukan hal berikut:
    i.	Verifikasi PIN lama
    ii.	Minta nasabah memasukkan PIN baru dua kali
    iii.	Validasi bahwa kedua input PIN baru cocok
  	iv.	Perbarui PIN jika validasi berhasil
  	![Cuplikan layar 2024-11-14 224333](https://github.com/user-attachments/assets/6daef39e-665a-4c3a-b49e-765a7fb6c71f)
  	![image](https://github.com/user-attachments/assets/fddb5e55-8316-475c-b69a-effbe18b5086)
    Hasil run	![image](https://github.com/user-attachments/assets/940abc7a-e8a3-4fee-9f3a-0cce03fea12e)
    Penjelasan: Penjelasan : Hasil runningnya merupakan hasil dari menambahkan fitur Ubah Pin pada menu utama dan juga membuat method ChangePin() pada class Account yang di dalamnya terdapat fitur verifikasi pin lama, dan untuk menginput pin baru serta mengonfirmasi pin baru.
   
2.	Validasi Saldo Minimal pada saat penarikan
    a.	Modifikasi fitur penarikan sehingga nasabah harus menyisakan saldo minimal setelah penarikan dilakukan. Misal, saldo minial adalah Rp50,000-
  	b.	Langkah-langkah:
        i.	Tentukan saldo minimal, tambahkan konstanta MINIMUM_BALANCE dalam kelas Account
        ii.	Modifikasi methode execute() dalam kelas Withdrawal untuk memeriksa apakah saldo setelah penarikan tidak kuran dari saldo minimal
        iii.	Jika saldo tidak mencukupi, tampilkan pesan kesalahan  	
  	    ![image](https://github.com/user-attachments/assets/53004917-27d4-491a-ac73-9684c9a0d218)
  	    ![image](https://github.com/user-attachments/assets/1eff2489-d555-456c-94dc-9c72cf185e10)
  	    Run: ![image](https://github.com/user-attachments/assets/ab2993a9-ceb3-45df-83c6-71febcc9af2c)
  	    Penjelasan : Hasil runningnya merupakan hasil dari memodifikasi fitur penarikan dengan menambahkan public static final double MINIMUM_BALANCE dalam class Account dan memodifikasi method execute() dalam class Withdrawal untuk mendetect agar saldo pada rekening tidak habis, atau menyisakan 50000 saldo.

    

