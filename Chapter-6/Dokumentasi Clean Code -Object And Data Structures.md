# Introduction 

Dalam dunia pemrograman, bagaimana kita mendesain objek dan struktur data memegang peranan penting terhadap kualitas dan keberlanjutan kode. Pembahasan Object dan Data Structures disini menekankan pentingnya pemisahan tanggung jawab antara objek (yang berfokus pada perilaku/behavior) dan data (yang berfokus pada representasi/informasi). Kita diajak memahami kapan sebaiknya menggunakan objek, kapan sebaiknya menggunakan struktur data, dan bagaimana membuat keduanya saling mendukung, bukan saling membebani.

---

# Paradigma Pemrograman

Paradigma pemrograman adalah model atau pendekatan dalam menulis dan mengatur kode program. Paradigma pemrograman mencerminkan filosofi tertentu dalam menyusun logika, struktur data, dan interaksi antar bagian program.

## Apa Itu Paradigma Pemrograman?

Paradigma pemrograman merupakan pendekatan atau gaya dalam menulis dan menyusun kode dalam bahasa pemrograman. Paradigma ini menentukan bagaimana instruksi diberikan ke komputer, bagaimana struktur program dibuat, dan bagaimana pengembang menyelesaikan suatu masalah menggunakan kode.

![test](Picture1.png)

---
## Mengapa Perlu Memahami Paradigma Pemrograman?

- **Memahami Cara Kerja Bahasa Pemrograman**
	Setiap bahasa pemrograman memiliki pendekatan dan fitur bawaan yang mendukung paradigma tertentu, seperti OOP, deklaratif, atau fungsional. Dengan memahami paradigma, developer bisa lebih mudah memahami bagaimana bahasa tersebut mengatur alur logika, struktur data, dan interaksi antarkomponen.

- **Membantu memilih solusi terbaik untuk suatu masalah.**
    Setiap paradigma memiliki keunggulan dalam situasi tertentu. Misalnya, paradigma fungsional cocok untuk perhitungan matematis yang kompleks, sedangkan OOP lebih cocok untuk sistem yang kompleks dan modular. Memahami paradigma memungkinkan kita memilih pendekatan yang paling efektif dan efisien.

- **Meningkatkan fleksibilitas dan efektivitas dalam menulis kode.**
    Developer yang menguasai berbagai paradigma dapat menulis kode dengan gaya yang lebih adaptif. Ini memungkinkan pengembangan fitur yang lebih cepat, pengurangan kode duplikat, dan solusi yang lebih elegan terhadap masalah yang kompleks.

- **Menyesuaikan gaya coding dengan teknologi atau framework tertentu.**
    Setiap platform, termasuk OutSystems, memiliki paradigma dominan yang didukungnya. Memahami paradigma membantu developer menggunakan framework atau tool sesuai dengan tujuan desainnya dan menghasilkan aplikasi yang lebih natural dan efisien.

- **Memudahkan kolaborasi tim dan perawatan jangka panjang kode.**
    Ketika semua anggota tim memiliki pemahaman paradigma yang sama, mereka dapat menyusun kode dengan pola yang konsisten. Ini memudahkan siapa pun dalam tim untuk membaca, memperbaiki, atau melanjutkan pengembangan kode di masa depan tanpa kebingungan.

---
## Jenis-jenis Paradigma Pemrograman

Paradigma pemrograman adalah cara atau pendekatan dalam menulis dan menyusun kode program, yang didasarkan pada prinsip, pola pikir, dan aturan tertentu. Setiap paradigma menawarkan cara berbeda dalam memecahkan masalah dan mengelola struktur program.

1. **Imperative**
    Paradigma imperative adalah cara menulis program dengan menguraikan urutan instruksi detail secara eksplisit kepada komputer, fokus pada proses (how), bukan sekadar hasil akhirnya.
    
    Memberikan Instruksi Eksplisit : lakukan X kemudian  Y ~ untuk mendapatkan Z (Bagaimana)
    
    **Contoh:** Fungsi getArea menerima panjang dan lebar, lalu langsung mengembalikan hasilnya tanpa mengubah apa pun di luar fungsi. Nilai-nilai yang digunakan juga tidak bisa diubah karena ditulis dengan **const**.
	
	![test](Picture2.png)
    
    Cara ini membuat kode jadi lebih mudah dibaca, tidak rumit, dan bisa digunakan kembali untuk hitung luas lain.

  

2. **Declarative**
    Paradigma deklaratif adalah cara menulis program dengan menyatakan apa yang ingin dicapai (what), bukan bagaimana mencapainya secara detail. Dalam paradigma ini, kamu fokus pada hasil akhir, bukan pada langkah-langkah atau prosesnya. 
    
    Mendeskripsikan Tujuan Akhir; Berikan Saya Z ~ Menggunakan X dan Y (Apa)
    
    Contoh: pada gambar menunjukkan cara deklaratif untuk menghitung luas persegi panjang. Kita cukup membuat fungsi getArea yang menerima panjang dan lebar, lalu mengembalikan hasil perkaliannya. Setelah itu, kita panggil fungsi tersebut dengan memberikan nilai panjang dan lebar yang sudah ditentukan. 
    
	![test](Picture3.png)
    
    Cara ini disebut deklaratif karena kita hanya menyebutkan apa yang ingin dihitung (luas), tanpa menjelaskan bagaimana langkah-langkah proses perhitungannya secara detail. Kode ini mudah dibaca, ringkas, dan bisa digunakan ulang.

---

## Multi-Paradigma Pemrograman Dalam OutSystems

OutSystems merupakan platform low-code yang mengadopsi pendekatan multi-paradigma pemrograman untuk memudahkan pengembangan aplikasi secara efisien, terstruktur, dan scalable. Tidak terpaku pada satu cara berpikir saja, OutSystems menggabungkan beberapa paradigma sekaligus dalam satu lingkungan visual.

Berikut beberapa paradigma yang digunakan OutSystems:

1. **Declarative Programming**
    OutSystems menggunakan paradigma deklaratif saat pengembang mendesain antarmuka atau mengatur logika dengan flowchart, karena cukup menyatakan apa yang ingin dicapai, tanpa perlu menuliskan secara detail langkah-langkah teknisnya.
    
    ![test](Picture4.png)


2. **Event-driven Programming**
    Event-driven programming adalah paradigma pemrograman di mana alur eksekusi program dikendalikan oleh kejadian-kejadian tertentu (event), seperti klik tombol, perubahan input, atau respons dari server. Dalam paradigma ini, program akan merespons suatu event dengan menjalankan aksi atau logika tertentu yang sudah ditentukan.
    
    ![test](Picture5.png)
    
    Di OutSystems, paradigma ini diterapkan secara alami melalui fitur-fitur visualnya. Developer dapat mengatur aksi yang dijalankan berdasarkan event pengguna atau sistem dengan menggunakan event handler seperti OnClick, OnChange, atau OnReady di elemen UI.


3. **Component-Based Development**
    Component-based programming adalah paradigma pemrograman yang berfokus pada pembuatan, penggunaan ulang, dan penggabungan komponen-komponen independen yang memiliki fungsi spesifik. Komponen ini bisa berupa bagian UI, logic, atau modul aplikasi yang dibungkus agar dapat digunakan kembali di berbagai bagian lain tanpa perlu menulis ulang logika atau desainnya.
    
    ![test](Picture6.png)
    
    Dalam OutSystems, paradigma ini sangat menonjol dan diterapkan secara menyeluruh melalui fitur-fitur seperti UI Blocks, Server Actions, Client Actions, dan Modul. Masing-masing bagian ini dirancang agar dapat dikembangkan secara modular dan digunakan ulang (reusable) di halaman atau aplikasi lain.


4. **Model-Driven Development**
    Model-Driven Development (MDD) adalah paradigma pemrograman di mana proses pengembangan aplikasi difokuskan pada pembuatan model visual, bukan penulisan kode secara manual. 
    
    ![test](Picture7.png)
    
    OutSystems merupakan salah satu platform yang sangat mengandalkan Model-Driven Development. Dengan antarmuka visual yang kuat, pengembang bisa membuat aplikasi dengan cepat hanya dengan menyusun elemen-elemen seperti Entity, Logic Flow, dan UI komponen secara drag and drop, tanpa perlu mengetik banyak baris kode. Setiap komponen yang dibuat secara visual pada dasarnya adalah bagian dari model yang mendeskripsikan bagaimana aplikasi bekerja.

---

# Data Abstraction

Abstraksi data adalah salah satu prinsip utama untuk menjaga agar kode tetap bersih, mudah dipahami, dan fleksibel terhadap perubahan. Melalui abstraksi, kita menyembunyikan detail implementasi dan menonjolkan fungsionalitas yang relevan.

## Apa itu Data Abstraction?

Data Abstraction adalah konsep dalam pemrograman yang digunakan untuk menyembunyikan detail internal dari cara data disimpan atau dikelola, dan hanya menampilkan informasi penting atau yang dibutuhkan kepada pengguna.

---

## Tujuan Data Abstraction

- Menyederhanakan antarmuka objek atau struktur data.
    
- Menyembunyikan kompleksitas internal.
    
- Meningkatkan modularitas dan isolasi perubahan.
    
- Menghindari ketergantungan langsung terhadap struktur data.
    

---

## Perbedaan Concrete dan Abstract

Perbedaan concrete dan abstract sangat penting dalam memahami konsep data abstraction, karena keduanya mewakili dua sisi dari bagaimana data dan logika dipresentasikan dalam pemrograman.

| Aspek    | Concrete                                  | Abstract                                                        |
| -------- | ----------------------------------------- | --------------------------------------------------------------- |
| Contoh   | ![test](Picture8.png)                     | ![test](Picture9.png)                                           |
| Definisi | Bentuk nyata yang bisa langsung digunakan | Gambaran umum atau konsep yang belum diimplementasikan penuh    |
| Sifat    | Data bersifat tetap dan statis            | Data bersifat dinamis                                           |
| Tujuan   | Menyediakan Fungsi Spesifik               | Menyediakan struktur dasar yang bisa digunakan oleh banyak tipe |

---
## Data Abstraction Pada OutSystems

Penerapan Data Abstraction pada OutSystems dapat dilihat pada gambar berikut:

![test](Picture10.png)

Pada bagian kiri, tampak desain visual dari sebuah Server Action (ModelExample) yang terdiri dari node IF: PostReady dan Server Action: NewPost. Desain ini menyembunyikan kompleksitas logika di balik masing-masing langkah, dan hanya menampilkan alur proses secara umum, inilah bentuk abstraksi secara visual.

Kemudian, pada bagian kanan gambar, kita bisa lihat hasil terjemahan dari logika visual tersebut dalam bentuk kode C#. Hal ini menunjukkan bahwa meskipun di balik layar sistem bekerja dengan kode yang kompleks, pengguna OutSystems hanya perlu fokus pada modul fungsional yang sudah disederhanakan secara visual.

Konsep data abstraction ini makin kuat ketika kita menerapkan modularisasi, misalnya membuat action NewPost di modul berbeda. Kita tidak perlu tahu detail isi NewPost, cukup tahu bahwa jika kondisi PostReady bernilai true, maka NewPost akan dijalankan. Dengan cara ini, OutSystems menyembunyikan detail internal (konkrit) dan hanya memperlihatkan interface atau alur penggunaan (abstrak) kepada developer.

---
# Data/Object Anti Symmetry

Objek dan struktur data memiliki sifat berlawanan dan tidak boleh dicampur sembarangan. Memahami perbedaan ini akan membantumu mendesain sistem yang lebih modular dan terpisah antara data dan logic.

## Dichotomy Data & Logic pada High Code

Dalam pemrograman high-code seperti Java, C#, atau Python, dikenal konsep Dichotomy of Data & Logic, yaitu pemisahan yang jelas antara data dan logika. Pendekatan ini menekankan bahwa data dan logika adalah dua hal berbeda yang memiliki tanggung jawab masing-masing dalam sistem.

![test](Picture11.png)

Data merujuk pada struktur seperti variabel, objek, atau class yang hanya berfungsi untuk menyimpan informasi. Data tidak memiliki perilaku; ia hanya menyimpan nilai seperti nama, harga, atau status. Dalam konteks ini, data bersifat pasif, hanya tersedia untuk digunakan oleh logika.

Sebaliknya, Logic diwakili oleh fungsi atau metode yang berisi instruksi atau perilaku. Fungsi ini bertugas memproses data, melakukan perhitungan, membuat keputusan, atau mengubah nilai data. Logika tidak menyimpan data, tapi hanya berfokus pada aksi atau proses terhadap data yang diberikan.

Pemisahan ini membuat pengembangan aplikasi lebih fleksibel dan modular, karena data dan logika bisa dikembangkan secara terpisah. Namun, hal ini juga menuntut developer untuk merancang interaksi antara keduanya dengan disiplin.

---
## Mengapa Data dan Logic Perlu Dipisah?

- Tidak Ada Paradigma Universal
    

Setiap use case memiliki kebutuhan berbeda. Ada yang lebih cocok dengan pendekatan Data-First, ada yang lebih efektif dengan Logic-First.

- Modularitas & Skalabilitas
    

Pemisahan membuat kode lebih fleksibel dan mudah dikembangkan tanpa perlu mengubah seluruh sistem.

---

## Dichotomy pada OutSystems

![test](Picture12.png)

OutSystems, sebagai platform low-code, secara eksplisit menerapkan prinsip pemisahan antara data dan logic dalam desain sistemnya. Pendekatan ini selaras dengan praktik terbaik dalam rekayasa perangkat lunak modern yang menekankan modularitas dan pemisahan tanggung jawab. Tab Data berfungsi untuk mendefinisikan struktur data seperti Entity, Static Entity, dan relasi antar data. Semua informasi yang bersifat statis atau dinamis disimpan dan dikelola di sini. Sementara itu, tab Logic digunakan untuk mendefinisikan perilaku aplikasi melalui Client Action, Server Action, dan Integrations.

Dengan menyediakan antarmuka visual yang membedakan pengelolaan data dan logika aplikasi, OutSystems memfasilitasi pengembangan yang lebih terstruktur, mudah dipelihara, dan fleksibel terhadap perubahan.

### Pemisahan Tugas Berdasarkan Fungsi

- Data berfokus pada penyimpanan informasi seperti entitas, variabel, dan struktur data.
    
- Logic menangani proses bisnis, perhitungan, keputusan, dan alur kerja aplikasi.
    

###  Dukungan terhadap Modularitas

- Memisahkan data dan logika memungkinkan pengembangan aplikasi yang modular.
    
- Komponen dapat dikembangkan, diuji, dan dikelola secara independen.
    

###  Kemudahan Pemeliharaan dan Skalabilitas

- Struktur yang jelas mempercepat proses debugging dan pemeliharaan.
    
- Aplikasi dapat dengan mudah ditingkatkan atau dimodifikasi tanpa mempengaruhi seluruh sistem.
    

---

## Permasalahan Pada Data & Logic

  

|   |   |   |
|---|---|---|
|Category|Data|Logic|
|Expose|Data|Logic|
|Hide|Behavior|Data|
|Easy|Add new logic|Add new data|
|Hard|Add new data|Add new logic|

  
Ini menggambarkan paradoks dan tantangan dalam memisahkan serta menangani data dan logika dalam pengembangan perangkat lunak. Tabel ini menunjukkan bahwa tidak ada pendekatan tunggal (baik yang menekankan data maupun logika) yang sepenuhnya ideal dalam semua situasi. Berikut adalah penjelasan untuk tiap baris pada tabel:

### 1. Expose (Apa yang ditonjolkan oleh sistem)

- Data → Menonjolkan Data: Sistem yang berbasis data lebih mengedepankan struktur data (seperti objek dan variabel).  
      
    
- Logic → Menonjolkan Logika: Sistem yang berbasis logika lebih fokus pada alur, algoritma, dan proses.  
      
    

---

### 2. Hide (Apa yang disembunyikan oleh sistem)

- Data → Menyembunyikan Perilaku (Behavior): Dalam pendekatan data-oriented, logika atau perilaku sering tidak terlihat atau terenkapsulasi.  
      
    
- Logic → Menyembunyikan Data: Dalam pendekatan logic-oriented, struktur data sering tidak eksplisit atau tersembunyi dalam proses.  
      
    

---

### 3. Easy (Apa yang mudah dilakukan)

- Data → Menambahkan Logika Baru: Dalam sistem berbasis data, mudah untuk menambahkan logika baru ke struktur data yang sudah ada.  
      
    
- Logic → Menambahkan Data Baru: Dalam sistem berbasis logika, lebih mudah menambahkan data baru ke dalam alur yang sudah ada.  
      
    

---

### 4. Hard (Apa yang sulit dilakukan)

- Data → Menambahkan Data Baru: Menambahkan data bisa rumit jika tidak didukung oleh logika yang fleksibel.  
      
    
- Logic → Menambahkan Logika Baru: Menambahkan logika baru bisa sulit karena sistem sudah kompleks atau kaku.
    

  

---

## Data-First

Data First dalam konteks rekayasa perangkat lunak, di mana struktur data menjadi pondasi utama, dan logika dibangun di atasnya. Sebagai contoh apa itu Data - First kamu dapat melihat gambar berikut : 

Menambah Logika Baru – Easy to add logic

- Data : - Rectangle dan Triangle sudah ada.  
      
    
- Ketika menambahkan logika baru, seperti Circumference, tidak perlu mengubah data. Semua data yang sudah ada bisa langsung diproses oleh logika baru.  
      
    
- Ini menunjukkan bahwa logika bersifat fleksibel dan bisa ditambah tanpa memengaruhi struktur data yang ada.
    

Keuntungan: Mudah menambah logika baru tanpa harus menyentuh data. Cocok untuk sistem yang sering menambahkan fitur atau fungsi baru.

Menambah Data Baru – Hard to add data

- Logika : - Area dan Circumference sudah ada.  
      
    
- Ketika menambahkan data baru, misalnya Circle, maka setiap logika harus dimodifikasi agar mengenali dan memproses data baru tersebut.  
      
    
- Artinya, semua logika yang ada harus diperbarui satu per satu untuk mendukung tipe data baru.
    

Kelemahan: Sulit menambah data baru karena akan berdampak ke banyak bagian logika. Ini adalah kekurangan pendekatan Data First ketika sistem butuh mendukung banyak jenis entitas baru.

## Data First di dalam High Code

Class Rectangle dan Triangle merupakan Data

Class Geometry merupakan Logic

Jika kita menambah logic baru berupa logic circumference di class Geometry, maka data class Rectangle dan Triangle tidak berubah sama sekali.

Class turunan lainnya yang memakai Rectangle dan Triangle juga tidak akan terkena dampak. (Easy to add new logic)

Sebaliknya jika kita menambah data baru, misalkan shape clas Circle, maka class Geometry harus melakukan perubahan juga.  
(Hard to add new data)

## Data First di dalam Outsystems

Membuat Data Terlebih Dahulu

1. Implementasikan Class Rectangle dan Triangle sebagai Structure 
    
2. Membuat Structure Shape untuk Grouping
    

  

Membuat Logic Geometry

  

1. Jika membuat Action Geometry baru, misal Geometry_Circumference, maka Data Rectangle dan Triangle tidak akan berubah (easy to add new logic).
    
2. Jika menambahkan data baru, misal Circle, maka semua Logic akan berubah (hard to add new data).
    

  

Contoh Implementasi Data-First

- Di dalam flow Geometry_area, logika ditulis berdasarkan tipe data dari objek shape.  
      
    
- Percabangan logika (decision nodes) memeriksa apakah objek shape merupakan instance dari Rectangle atau Triangle.  
      
    
- Jika Rectangle, maka logika menghitung luas dengan width * height.  
      
    
- Jika Triangle, maka luas dihitung dengan base * height 
    

---

## Logic-First

Gambar ini menggambarkan pendekatan Logic-First, yang berkebalikan dari Data-First. Dalam pendekatan Logic-First, aturan atau logika menjadi pusat utama, dan data harus menyesuaikan diri dengan logika tersebut.

Menambah Data Baru – Easy to add data

- Dalam analogi ini, “Negara” memiliki aturan: wajib punya KTP.  
      
    
- Semua objek (seperti Rectangle dan Circle) harus punya KTP untuk bisa masuk ke sistem.  
      
    
- Jika ada objek baru (misalnya Triangle) yang ingin bergabung, ia cukup mengikuti aturan yang sudah ada, tanpa perlu mengubah aturan itu sendiri.
    

Keuntungan: Menambah data baru sangat mudah, selama data tersebut mengikuti kontrak atau antarmuka yang ditentukan (misalnya, mengimplementasikan getKTP() atau Area()).

Menambah Logika Baru – Hard to add new logic

- Saat aturan negara berubah, misalnya sekarang semua entitas harus punya metode Area(), maka semua objek yang sudah ada (Rectangle, Circle, dll.) harus dimodifikasi untuk memenuhi aturan baru.  
      
    
- Artinya, setiap entitas atau class perlu diperbarui agar menyediakan metode Area().  
      
    

Kelemahan: Menambah logika baru akan sulit, karena semua class harus diubah untuk mendukung logika tersebut. Hal ini membuat sistem tidak fleksibel terhadap penambahan fitur baru.

## Logic-First di dalam High Code

- Class Shape merupakan Logic abstrak 
    
- Class Rectangle merupakan Data yang mengimplementasi Logic dari class Shape  
      
    
- Jika kita menambahkan shape baru, misalkan class Circle, maka tidak ada Logic yang berubah. (Easy to add new data)  
      
    
- Sebaliknya, jika class abstrak dari Shape akan menambahkan Logic baru, misalkan fungsi menghitung circumference.  
      
    Maka seluruh data turunannya yang mengimplementasikan Logic class Shape, harus ikut berubah. (Hard to add new logic)
    

## Logic-First didalam Outsystems

Mendefinisikan Data Terlebih Dahulu

1. Membuat Shape Logic untuk menampung logic-logic lain terkait Shape.
    
2. Membuat Structure setiap Shape dengan masing-masing atribut
    

  

Membuat Logic Geometry

- Jika kita menambahkan Shape baru, misalkan Triangle, maka logic tidak berubah (easy to add new data).
    
- Jika menambahkan Logic baru, misalkan fungsi Circumference, maka semua Action harus ikut berubah (hard to add new logic).
    

Contoh Implementasi Logic-First

- Flow berjudul GetCircleArea dimulai dari titik awal (Start), lalu menjalankan satu langkah proses bernama Calculate Circle Area.  
      
    
- Di dalam node tersebut, terjadi proses perhitungan:  
    Result.area = 3.14 * Circle.radius * Circle.radius  
    Ini adalah rumus luas lingkaran: π × r².
    
- Perhitungan dilakukan langsung di dalam modul logika yang spesifik hanya untuk lingkaran.
    

---

# The Law Of Demeter

Law of Demeter (LoD) atau “Prinsip Kedekatan” adalah aturan yang membantu mengurangi ketergantungan objek terhadap detail internal dari objek lain.

## Apa itu The Law Of Demeter?

The Law of Demeter (LoD) adalah prinsip desain dalam pemrograman yang menyarankan agar sebuah objek hanya boleh berinteraksi dengan “teman terdekatnya”, dan tidak mengetahui detail struktur internal dari objek lain. Sering juga disebut sebagai prinsip “don’t talk to strangers”.

Suatu objek hanya boleh memanggil:

1. Dirinya sendiri
    
2. Parameter yang diterimanya
    
3. Objek yang dibuatnya sendiri
    
4. Komponen langsung yang dimilikinya
    

---

## The Law Of Demeter Pada OutSystems

Pada OutSystems, konsep ini diterapkan untuk meningkatkan modularisasi agar tidak ada ketergantungan berlebihan antar modul.

Studi Kasus: Menampilkan Harga Kopi per Cangkir

|   |   |   |
|---|---|---|
|Struktur Modul|   |   |
|Modul Data|Modul Bisnis|Modul UI|
|Berisi Entitas: CoffeeMachine, CoffeeCup|Berisi Server Action: CalculatePricePerCup(CoffeeCupId): Price|Memanggil CalculatePricePerCup <br><br>untuk menampilkan harga ke pengguna|

  

- Kesalahan Umum:
    

Di dalam Modul UI, kita langsung mengambil data dari entitas CoffeeMachine tanpa melalui Modul Bisnis.

Bad Practice (Langsung Akses Data dari Modul Lain)

Dampaknya:

- UI terlalu banyak tahu tentang struktur database.
    
- Jika ada perubahan di entitas CoffeeMachine, UI juga harus diubah.
    
- Melanggar prinsip modularisasi karena ketergantungan langsung antar entitas.
    

Solusi:

Kita harus membuat Server Action di Modul Bisnis (misal. CoffeeLogic) agar UI hanya memanggil Action ini.  
  
🟢 Good Practice (Dengan LoD)

Dengan demikian:

- UI hanya berkomunikasi dengan CoffeeLogic di Modul Bisnis, bukan langsung dengan database.
    
- Jika ada perubahan di CoffeeMachine, hanya CoffeeLogic yang perlu untuk diperbarui, bukan UI.
    
- Modular dan lebih mudah dikelola.
    

## 

---

## Kesimpulan

Prinsip Clean Code pada Object dan Data Structures menekankan pentingnya pemisahan antara data dan logika, serta memilih pendekatan yang tepat berdasarkan kebutuhan, baik Data-First maupun Logic-First. Dalam OutSystems, pemisahan ini tercermin melalui penggunaan Entity/Structure untuk mewakili data, dan Server/Client Actions untuk menjalankan logika. Dengan memahami anti-simetri antara data dan objek, serta menerapkan prinsip seperti abstraksi data, modularisasi logic, dan The Law of Demeter, pengembang dapat membangun aplikasi yang fleksibel, mudah diubah, dan terstruktur dengan baik. Tujuan akhirnya adalah menciptakan sistem yang mudah dipahami, dirawat, dan dikembangkan dalam jangka panjang—selaras dengan semangat Clean Code.

**