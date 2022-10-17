# Writing Test
4th-Week
## Javascript - Asynchronous - Fetch & async await
Fetch adalah kegiatan untuk meminta/request layanan ke endpoint/letak url yang akan menerima request pada website secara local maupun public, untuk mengambil sumber daya berupa data berformat json yang biasa dilakukan untuk membangun website yang membutuhkan data dari website lain didalamnya.  
Berikut contoh penggunaan API:
````javascript
fetch('https://pokeapi.co/api/v2/pokemon/ditto')
.then(res => res.json())
.then(data => console.log(data))
.catch(err => console.log(err))
````
Async/await adalah sebuah syntax khusus yang digunakan untuk menangani Promise agar penulisan code lebih efisien dan rapih. 
Sebuah async function bisa tidak berisi await sama sekali atau lebih dari satu await. Keyword await hanya bisa digunakan didalam async function, jika digunakan di luar async function maka akan terjadi error.  
Berikut contoh penggunaan async:
````javascript
async function tesAsyncAwait() {
  return "Fulfilled";
}
console.log(tesAsyncAwait());
````
## Git & Github lanjutan
Git adalah aplikasi yang dapat melacak setiap perubahan yang terjadi pada suatu folder atau file. Git biasanya digunakan oleh para programmer sebagai tempat penyimpanan file pemrograman mereka, karena lebih efektif.  
Github adalah sebuah layanan cloud yang berguna untuk menyimpan dan mengelola project-project yang dinamakan dengan repository.
### Membuat branch
Menambahkan branch pada github bisa melalui webnya dengan meng-klik dibagian branch pada repository yang ingin di tambahkan branch baru, contohnya seperti pada gambar berikut:
![Git-branch](/4th-Week/git-branch.PNG)
### Cloning di github
Untuk mendownload atau memindahkan suatu repository dari remote menuju lokal ktia bisa menggunakan yang namanya git clone dengan cara meng-klik tombol "code" pada repository yang ingin di clone atau download lalu copy link dari repository tersebut, contohnya seperti berikut:
![Git-clone01](/4th-Week/git-clone1.PNG)
lalu setelah itu bisa dilanjutkan dengan membuka terminal gitbash pada folder atau tempat kita akan mendownload repository tersebut, contohnya seperti pada gambar berikut:
![Git-clone02](/4th-Week/git-clone02.PNG)
### Merge pada github
Ketika kita ingin menggabungkan dua branch kita bisa menggunakan git merge.     
```
git merge nama-branch
```

## Responsive web dan Bootstrap
Responsive web adalah sebuah metode yang membuat web tetap dapat diakses melalui berbagai device seperti pc, smartphone ataupun tablet. Untuk di setiap browser biasanya sudah terdapat tools yang dapat mempermudah dalam development website, contohnya nama tools pada google chrome yakni Chrome Dev Tools. Untuk di sistem operasi wwindows kita bisa menekan gabungan dari tombol "Ctrl + Shift + J".
Agar kita dapat membuat website menjadi responsive kita dapat menggunakan beberapa cara:
* Viewport
Agar dapat berjalan, viewport ini harus berada di dalam tag `<head>`.
````HTML
<meta name="viewport" content="width=device-width, initial-scale=1.0">
````
* Media Query
Media query biasanya digunakan untuk membuat beberapa styles pada website tergantung pada jenis devicenya.
Berikut contoh coding dari media query:
![media-query](/4th-Week/media-query.PNG)
* Satuan relative CSS
Seperti namanya yakni satuan relatif css, satuan ini membuat ukuran dari suatu elemen menjadi relatif terhadap sesuatu seperti ukuran dari viewport.
![relative-css](/4th-Week/relative-css.PNG)
* flexbox
Flexbox hanya dapat mengatur arah pada satu arah saja yakni secara horizontal atau vertikal. Berikut contoh penggunaan flexbox
````HTML
<html>
<head>
<style>
.flex-container {
  display: flex;
  background-color: DodgerBlue;
}

.flex-container > div {
  background-color: #f1f1f1;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
}
</style>
</head>
<body>
<h1>Create a Flex Container</h1>
<div class="flex-container">
  <div>1</div>
  <div>2</div>
  <div>3</div>  
</div>
</body>
</html>
````
* grid
Sedangkan untuk grid, dapat mengatur arah dari dua arah yakni secara verikal dan horizontal.
````HTML
<html>
<head>
<style>
.item1 { grid-area: header; }
.item2 { grid-area: menu; }
.item3 { grid-area: main; }
.item4 { grid-area: right; }
.item5 { grid-area: footer; }

.grid-container {
  display: grid;
  grid-template-areas:
    'header header header header header header'
    'menu main main main right right'
    'menu footer footer footer footer footer';
  gap: 10px;
  background-color: #2196F3;
  padding: 10px;
}

.grid-container > div {
  background-color: rgba(255, 255, 255, 0.8);
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
}
</style>
</head>
<body>
<h1>Grid Layout</h1>
<div class="grid-container">
  <div class="item1">Header</div>
  <div class="item2">Menu</div>
  <div class="item3">Main</div>  
  <div class="item4">Right</div>
  <div class="item5">Footer</div>
</div>
</body>
</html>
````

Bootstrap adalah sebuah framework HTML, CSS dan Javascript yang membantu developer dalam mendesain dan membuat website dengan cepat dan mudah juga  responsive. Bootstrap diciptakan oleh developer dari Twitter, yakni Mark Otto dan Jacob Thornton, yang pada awalnya diberi nama Twitter Blueprint.  
Untuk peggunaan bootstrap cukup mudah, kita tinggal buka website bootstrap lalu buka bagian dokumentasi setelah otu kita bisa membaca atau mencari apa yang ingin kita gunakan di dalam website yang kita buat. 
Contohnya yakni layout, di dalam layout bootstrap ini ada point penting salah satunya yakni Grid. Grid adalah sistem yang digunakan Bootstrap untuk mengatur tata letak (layout). Sistem ini terdiri dari 12 kolom dan 6 breakpoint.Satu kolom penuh panjangnya adalah 12. Jika kolom dibagi dua maka panjangnya akan menjadi 6.
Breakpoint adalah ukuran lebar yang menentukan tampilan responsif terhadap ukuran viewport perangkat tertentu. Saat ini Bootstrap memiliki 6 ukuran Breakpoint, yakni none, sm, md, lg, xl, dan xxl.  

Source:  
https://getbootstrap.com/  
https://skilvul.com/  
https://medium.com/  