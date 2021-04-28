# Tutorial-Git
Cara menggunakan git dengan CLI (Command Line Interface)



* Apabila ingin membuat repositori baru 

1) git init --> dengan perintah ini akan menginisiasi folder biasa menjadi repositori dan membuat sub direktori 
   yang bernama .git yang menyimpan semua perubahan yang kita lakukan.

3) git add README.md --> sebuah file yang berisi penjelasan umum terkait project yang kita buat.

5) git commit -m "Pesan commit pertama" --> menyimpan perubahan yang kita lakukan. -m artinya adalah messages.

7) git branch -M main --> -M artinya move, sehingga dengan perintah itu akan mengubah cabang ke main. 

8) git remote add origin <link repo github> --> untuk meremote repositori yang berada di server. 
   Note : sebelum kita melakukan remote, kita harus membuat repositori di layanan github dulu.
   
9) git push -u origin main --> dengan perintah ini akan mengirimkan semua file dan perubahan yang kita lakukan di repo lokal
   ke layanan github.
