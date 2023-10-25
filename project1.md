## 1.1 Latar Belakang

Disini saya akan membuat website bisnis yang bertemakan CoffeeShop. Alasan saya membuat website ini agar pelanggan dapat melihat informasi seputar coffeeshop tersebut, menu dan produk apa saja yang tersedia, maupun lokasinya.

     
Proses Pembangunan Teknologi Informasi secara umum mengikuti Web Development Life Cycle :


   - Analysis

     Analisis adalah tahapan ketika kita mencoba menganalisa website seperti apa akan dibuat

   -	Design

    	Setelah itu saya akan mencoba mendesain sketsa dari website saya, kemudian didesain lebih jelas menggunakan Figma

   -	Development
     Setelah desain dan menentukan teknologi apa saja yang akan digunakan, kemudian saya akan mencoba mengaplikasikan desain tadi ke kodingan. Mulanya saya akan membuat struktur dasar menggunakan HTML, kemudian diberikan style menggunakan CSS, dan terakhir untuk fitut atau interaksi pengguna menggunakan JavaScript.

   - Testing & Review

     Setelah ketiga tahapan tadi, website yang sudah hamper selesai ditest terlebih dahulu, diperiksa semuanya dan dicari kesalahannya bila ada. Setelah itu saya mencoba meminta review ke orang lain untuk memberikan pendapat dan kritik mereka.

   - Deployment

     Setelah website saya dipastikan sempurna dan tidak ada kesalahan, juga sudah mendapatkan review yang baik, maka saya akan upload websitenya di akun github saya, yang kemudian akan saya hosting ke internet. Sehingga website saya bisa diakses melalui internet.

   - Maintenance

     Setelah berhasil mengupload websitenya, sekarang tinggal tahapan maintenance. Setelah mendeploy website untuk beberapa hari, saya akan mencoba cek apakah ada kerusakan atau pun kesalahan ketika mengakses website saya dari internet browser.


## 1.2. Deksripsi Teknologi Informasi

Didalam website ini akan terdapat homepage tentang landing page café saya, menu yang disajikan, product yang bisa dibeli, dan info seputar café saya dan lokasinya. Selain itu pengguna bisa menggunakan fitur seperti navbar, search, add to cart, dll. 

Fitur tersebut dapat kita dapatkan menggunakan bahasa JavaScript.

## 1.3. Branding

Pada tahap ini kita akan mengeksplorasi branding dari system yang dibuat. Branding meliputi :

•	Merk = Dracoffee (terinspirasi dari nama rasi bintang “Draco”)

•	Tagline = “ Behind every great day is a cup of coffee “

•	Campaign = Bagaimana membuat website yang menyediakan info bagi pembeli tentang bisnis dracoffee, maupun melakukan transaksi secara online agar memudahkan pembeli

•	Target User :

    o	Usia 15+
    
    o	Orang yang senang minum kopi
    
    o	Orang yang ingin melihat referensi coffeeshop
    
    o	Orang yang suka membeli barang (khususnya kopi) secara online
    
    o	Orang yang sering mengeksplor coffeeshop
    
    o	Orang yang ingin melihat menu sebelum datang ke coffeeshopnya
    
    •	User Experience :
    
    o	Mudah
    
    o	Menarik
    
    o	Sederhana
    
    o	Menginspirasi
    
    o	Warna : warna kopi (coklat), background hitam

- Inspirasi Desain :

<img width="425" alt="image" src="https://github.com/anandanovianshaf/dracoffee/assets/144409312/e7430299-146f-4784-9ce8-c536ccbc0ade">


<img width="550" alt="image" src="https://github.com/anandanovianshaf/dracoffee/assets/144409312/fd32d28b-e2cb-4174-a7eb-8a7ba3421883">


## 2. User Story

Sebagai | Saya ingin bisa | Sehingga | Prioritas
---|---|---|---
Pengguna | Mengklik Search | Bisa mencari produk yang diinginkan | ⭐⭐⭐⭐
Pengguna | Mengklik "add to cart" | Bisa menambahkan produk ke shopping cart | ⭐⭐⭐⭐⭐
Pengguna | Mengklik Navigation Bar di ukuran kecil | Lebih rapih dan tidak berantakan | ⭐⭐⭐
Pengguna | Mengklik Detail Product | Bisa memunculkan modal box yang berisi detail product | ⭐⭐⭐⭐⭐


## 3. Struktur Data

Cara membuat aneka macam bentuk grafik menggunakan mermaid.js bisa lihat di [https://mermaid.js.org/syntax/entityRelationshipDiagram.html](https://mermaid.js.org/syntax/entityRelationshipDiagram.html) 

```mermaid
erDiagram
    RUJAK ||--o{ SAYUR : tersusun
    PEMBELI ||--|{ RUJAK : beli
```

## 4. Arsitektur Sistem

Masih pake mermaid.js juga bisa lihat flowchart di [https://mermaid.js.org/syntax/flowchart.html](https://mermaid.js.org/syntax/flowchart.html)

## 5. Teknologi, Library, dan Framework

bla bla bla

## 6. Desain User Experience dan User Interface
- Ini adalah link figma saya
  https://www.figma.com/file/2Q3f3SrSDHTnylwDSUJnJl/dracoffee-design?type=design&mode=design&t=ByOMLVuTpahXCXyJ-1
  
1. Ini adalah desain ui page website saya

<img width="512" alt="image" src="https://github.com/anandanovianshaf/dracoffee/assets/144409312/35d185f4-d9f0-4f66-b3fb-73ba26f1fb66">


 Ketika search di klik, akan keluar search bar
 
   <img width="416" alt="image" src="https://github.com/anandanovianshaf/dracoffee/assets/144409312/33315e01-20f9-4062-b504-43440711b930">




2. Tampilan page sudah responsive, dibawah adalah gambar page di ukuran smartphone.

     Navigation bar akan berpindah ke dalam navbar menu, ketika di klik akan memunculkan navbar

     <img width="404" alt="image" src="https://github.com/anandanovianshaf/dracoffee/assets/144409312/a8729978-ff5a-4c4b-b4c4-68841dfa809d">



3. Dibawah tampilan page di bagian product

  - Ketika button mata di klik, akan muncul modal box yang menampilkan detail product
   
     <img width="557" alt="image" src="https://github.com/anandanovianshaf/dracoffee/assets/144409312/e14f9452-213c-46d5-a810-9f8403825ea6">

  - Ketika icon shopping cart di navbar di klik, akan muncul produk yang sudah ditambahkan ke shopping cart
   
      <img width="490" alt="image" src="https://github.com/anandanovianshaf/dracoffee/assets/144409312/498ac68c-c0c7-4bd0-91e9-96375de532af">





## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini
