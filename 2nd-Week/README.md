# Writing Test
2nd-Week

## JavaScript - Scope & Function
### Scope
Scope merupakan konsep dalam flow data variabel yang menentukan suatu variabel dapat diakses atau tidak pada cakupan tertentu. 
Di dalam scope ada yang namanya blocks, blocks ini merupakan barisan code yang beradda di dalam kurung kribo ( { } ). Scope ini dibagi menjadi 2 jenis yakni Global scope dan Local scope.
* #### Global Scope
  Global scope merupakan variabel yang bisa diakses dimanapun di dalam suatu file. Variabel yang dapat dikatakan sebagai global scope adalah variabel yang dideklarasikan diluar blocks.  
  ![Global-Scope](/2nd-Week/globalScp.PNG)
* #### Local Scope
  Local scope merupakan variabel yang dideklarasikan di dalam sebuah blocks, seperti function, conditional dan looping.  
  ![Local-Scope](/2nd-Week/localScp.PNG)

### Function
Function merupakan baris-baris kode dalam suatu grup untuk menyelesaikan satu tugas yang sama. Misalnya, jika terdapat banyak sekali kasus yang sama namun menggunakan satu metode penyelesaian yang sama, kita dapat menggunakan function untuk membuat code yang kita buat menjadi efisien. Di dalam function ada yang namanya para meter dan argumen.
* #### Parameter
  Parameter merupakan nilai inputan dari function pada saat function pertama kali didefinisikan.
* #### Argumen
  Argumen merupakan nilai inputan dari functioon pada saat function tersebut dipanggil. 
  ![Parameter&Argumen](https://miro.medium.com/max/640/1*BEB4cNegRTEZemNdnlqBhQ.png)  
   

## Javascript - Data Type
Di dalam javascript terdapat berbagai macam tipe data yakni :
* String adalah tipe data yang menampilkan data berupa text.
* Number adalah tipe data yang menampilkan data berupa angka.
* Boolean adalah tipe data yang menampilkan dua data berupa true dan false.
* Null adalah tipe data yang menampilkan data berupa null atau kosong.
* Undefined adalah tipe data yang tidak memiliki nilai atau belum didefinisikan.
* Object adalah tipe data yang berisi koleksi data-data yang saling berhubungan dan dapat menyimpan data dengan tipe data yang berbeda. Di dalam tipe data ini ada key dan value.



## DOM
DOM adalah singkatan dari Document Object Model, merupakan sebuah interface yang memungkinkan pembuat website memanipulasi halaman web dari segi struktur,tampilan hingga konten agar lebih dinamis. Dengan DOM, kita bisa memanipulasi berbagai macam elemen HTMl dan CSS di dalam sebuah website.
Dengan DOM,kita dapat mengambil, menghapus,mengubah, menambah elemen di dalam HTML.
Berikut beberapa perintah yang digunakan di dalam DOM untuk memanipulasi HTML:
* ### Mengambil sebuah element
  * getElementById
  * getElementsByClassName
  * getElementsByTagName
  * querySelector
  * querySelectorAll    
  
  ![getElement](/2nd-Week/getElement.PNG)
* ### Mengubah konten HTML
  * innerHTML
  * innerText
  
  ![edit](/2nd-Week/editCnt.PNG)
* ### Menambah dan menghapus elemen
  * createElement
  * .append
  * .remove()    
  
  ![addAndRemove](/2nd-Week/addAndRemove.PNG)

### Event
Dengan DOM kita juga dapat membuat event. Event merupakan kegiatan atau interaksi antara web dengan pengguna yang hasil dari even tersebut bisa disimpan atau bahkan tidak.  

![Event](/2nd-Week/event.PNG)




Source :  
https://skilvul.com/  
https://www.w3schools.com/  
https://medium.com/@igorwojda/parameter-vs-argument-1741acab53ec    
https://www.niagahoster.co.id/blog/apa-itu-dom/#Apa_itu_DOM_JavaScript  