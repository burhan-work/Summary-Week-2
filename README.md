# JAVASCRIPT DASAR
## *Introduction*
Javascript adalah bahasa pemrograman yang sangat *powerful* yang digunakan untuk logic pada sebuah *website*. Javascript juga dapat membuat *website* menjadi interaktif dan dinamis. Javascript dapat dijalankan melalui *browser* pada *device* setiap *user*. 

### *Syntax* dan *Statement*
*Syntax* bisa dianalogikan seperti kosa kata (*vocabulary*) dan tata cara (*grammar*) pada bahasa pemrograman. Kita menggunakan *syntax* tertentu untuk membuat *statement* program, instruksi untuk dijalankan/dieksekusi oleh *web browser*, *compiler*, ataupun *intrepreter*. Contoh *syntax*nya seperti **Alert()**, **Prompt()**, **Confirm()**, dan lain-lain.

### *Console Log*
*Console Log* adalah hal yang krusial bagi *developer web*. *Console Log* adalah tempat kita untuk mengecek *logic* pemograman *web* yang kita kembangkan. *Console Log* juga tempat kita untuk melakukan *debugging* (mengetahui *error* pada kode) pada pemrograman *web*.

### *Comments*
*Comments* adalah *syntax* yang digunakan untuk memberi keterangan tentang suatu *statement*. *Comments* tidak akan dijalankan oleh program karena hanya untuk dibaca oleh sesama programmer ataupun diri sendiri untuk memahami maksud dan tujuan sebuah *statement*/*syntax*. Terdapat 2 jenis *comments* yaitu *single comments* dan *multiline comments*.

### Tipe Data
Tipe data adalah klasifikasi yang kita berikan untuk berbagai macam data yang digunakan dalam programming. Ada 6 tipe data fundamental pada Javascript di antaranya:
1. *Number* 

    Tipe data *number* adalah tipe data yang mengandung semua angka termasuk angka desimal.

    Contoh:

        2, 4, 1200, 23.42
2. *String*

    Tipe data *string* adalah grup karakter yang ada pada *keyboard* laptop/PC kita yaitu *letters* (huruf), *number* (angka), *spaces* (spasi), *symbol*, dan lainnya. Penggunaan *string* harus diawali dan diakhiri dengan *single quotes* ‘ … ‘ ataupun *double quotes* “ … “.
3. *Boolean*

    Tipe data *boolean* adalah tipe data yang hanya mempunyai 2 buah nilai yaitu **TRUE** (benar) *or* **FALSE** (salah). Analoginya adalah seperti tombol/*button* ON/OFF dan juga seperti sebuah jawaban antara YES/NO.
4. *Null*

    Tipe data *null* adalah tipe data yang diartikan bahwa sebuah variabel/data tidak memiliki nilai. *Null* berbeda dengan *string* kosong. *String* kosong masih memiliki tipe data *string*.
5. *Undefined*

    Tipe data *undefined* adalah tipe data yang merepresentasikan varibel/data yang tidak memiliki nilai. *Undefined* berbeda dengan null. *Undefined* didapat dari hasil berikut:
    - Nilai dari pemanggilan variabel yang belum didefinisikan
    - Nilai dari pemanggilan *element array* yang tidak ada
    - Nilai dari pemanggilan *property* objek yang tidak ada
    - Nilai dari pemanggilan fungsi yang tidak mengembalikan nilai (*return*)
    - Nilai dari parameter fungsi yang tidak memiliki *argument*

    Tipe data *null* biasanya diperoleh dalam kondisi normal dan sudah kita rencanakan. Sedangkan tipe data *undefined* biasanya didapat dari hasil kesalahan program (*error*), kelalaian programmer, dan tidak direncanakan.
6. *Object*

    Tipe data *object* adalah koleksi data yang saling berhubungan (*related*). Tipe data *object* dapat menyimpan data dengan tipe data apapun (*number*, *string*, *boolean*, dan lainnya). Tipe data *object* mempunyai *key* dan *value*.

### Variabel
Variabel adalah *container*/tempat untuk menyimpan sebuah nilai. Terdapat 3 hal yang dapat dilakukan pada variabel, yaitu : 
1. Membuat variabel dengan nama yang jelas dan menggambarkan tentang data tersebut,
2. Menyimpan dan meng-*update* informasi/data yang disimpan, dan
3. Mendapatkan/menampilan data yang tersimpan.

Adapun cara untuk mendefinisikan sebuah variabel adalah sebagai berikut:
1. **var**
2. **let**
3. **const**

    **const** digunakan jika variabel tidak dapat diubah nilainya. Biasanya digunakan untuk menggambarkan konstanta sebuah nilai. Seperti konstanta pi = 3.14.

**let** dikenalkan pada versi javascript terbaru ES6. Variabel **let** mendukung kaidah *global* variabel dan *local* variabel. Jadi, dianjurkan untuk menggunakan **let** untuk variabel yang dinamis/dapat diubah.

Aturan Penamaan Variabel:
1. Harus mendeskripsikan tentang data yang disimpan.
2. Tidak bisa menggunakan *number* pada awal nama variabel.
3. Gunakan *camelcase* untuk penamaan yang lebih dari 1 kata. 

        Contoh: myName, myAge

### Operator
1. *Assignment* Operator (=)

    *Assignment* operator digunakan untuk menyimpan sebuah nilai pada variabel.
2. *Increment* dan *Decrement* (...++ atau ...--)

    Gunakan *increment* atau *decrement* untuk menambah atau mengurangi sebesar 1 nilai. 
3. *Arithmetic* Operator

    *Arithmetic* operator adalah operator yang melibatkan operasi matematika.
    - Tambah (+)
    - Kuramg (-)
    - Perkalian (*)
    - Pembagian (/)
    - Modulus (%)

        Modulus adalah hasil dari sisa bagi. Misalkan 5 modulus 2. Hasil perkalian dari 2 yang mendekati 5 adalah 4. Maka sisa dari operasi modulus tersebut adalah 1. Jadi 5 % 2 adalah 1.
4. *Comparison* Operator

    *Comparison* operator adalah operator yang membandingkan satu nilai dengan nilai lainnya. Hasil operasi yang melibatkan *comparison* operator adalah antara **true** *or* **false**.
    - Lebih kecil dari : **<**
    - Lebih besar dari: **>**
    - Lebih kecil atau sama dengan: **<=**
    - Lebih besar atau sama dengan: **>=**
    - Sama dengan: **===**
    - Tidak sama dengan: **!==**
5. *Logical* Operator

    *Logical* operator biasa digunakan untuk sebuah **CONDITIONAL** pada pemrograman. *Logical* operator menghasilkan nilai **BOOLEAN** yaitu **TRUE** *or* **FALSE**. Simbol dari *logical* operator adalah sebagai berikut:
    - AND operator : **&&**

        AND akan menghasilkan nilai true jika kedua atau semua premis bernilai **TRUE**.
    - OR operator: **||**

        OR akan menghasilkan nilai **TRUE** jika salah satu premis mengandung nilai *true*.
    - NOT operator: **!**

        NOT akan membalikkan sebuah nilai **BOOLEAN**, **TRUE** menjadi **FALSE** dan sebaliknya.

## *Scope and Function*
### Javascript - *Scope*
*Scope* adalah konsep dalam *flow* data variabel. Menentukan suatu variabel bisa diakses pada *scope* tertentu atau tidak. 

Analoginya seperti ini: 

    Kita semua bisa melihat bintang-bintang di langit karena bumi bersifat global. Namun jika kamu tinggal di Bandung, kamu tidak akan bisa melihat monas yang berada di Jakarta. Monas bersifat local yaitu hanya berada di Jakarta.
1. *Blocks*

    *Blocks* adalah kode yang berada di dalam *curly braces* { }. *Conditional*, *function*, dan *looping* menggunakan *blocks*.
2. *Global scope*

    *Global scope* berarti variabel yang kita buat dapat diakses di manapun dalam suatu file. Agar menjadi *global scope*, suatu variabel harus dideklarasikan di luar *blocks*.
3. *Local scope*

    *Local scope* berarti kita mendeklarasikan variabel di dalam *blocks* seperti *function*, *conditional*, dan *looping*. Maka variabel hanya bisa diakses di dalam *blocks* saja, tidak bisa diakses di luar *blocks*.

### Javascript - **Function**
**Function** adalah sebuah blok kode dalam sebuah grup untuk menyelesaikan 1 *task*/1 fitur. Saat kita membutuhkan fitur tersebut nantinya, kita bisa kembali menggunakannya.
1. Membuat **Function**
2. Memanggil **Function**
3. Parameter dan Argumen

    - Parameter **Function**
        
        Dengan parameter, **function** dapat menerima sebuah inputan data dan menggunakannya untuk melakukan task/tugas. Saat membuat **function**/fitur, kita harus tahu data-data yang dibutuhkan. Misalnya saat membuat **function** penambahan 2 buah nilai. Data yang dibutuhkan adalah 2 buah nilai tersebut.
    - Argumen *Function*

        Argumen adalah nilai yang digunakan saat memanggil **function**. Jumlah argumen harus sama dengan jumlah parameternya. Jadi, jika di **function** penambahan ada 2 parameter nilai saat membuat **function**, maka saat memanggil **function** kita gunakan 2 buah nilai argumen.
4. *Default* paramater

    *Default* paramater digunakan untuk memberikan nilai awal/*default* pada parameter **function**. *Default* parameter bisa digunakan jika kita ingin menjaga **function** agar tidak *error* saat dipanggil tanpa argumen.
5. *Function Helper*

    Kita bisa menggunakan **function** yang sudah dibuat pada **function** lain.
6. *Arrow function* 

    *Arrow function* adalah cara lain menuliskan **function**. Ini adalah fitur terbaru yang ada pada ES6 (Javascript *Version*)
7. *Short Syntax Function*

    - *Zero Parameters*
    - *One Parameters*
    - *Two or More Parameters*
    - *Single-line Block*
    - *Multi-line Block*

Nantinya saat kita mengembangkan aplikasi dengan skala besar, **function** sangat dibutuhkan agar kita dapat dengan mudah *memanage code* dan *tracing code* jika ada *error*.

## Data *Type Built in Prototype and Method*

## DOM *Manipulation*
### *Rendering*
**Isu terkait proses *rendering***

     Jika saat proses parsing HTML, ditemukan tag <script>, secara default proses parsing akan dihentikan sampai script tersebut selesai diunduh dan dijalankan. Jika script yang diunduh itu besar, ada jeda yang cukup lama antara halaman mulai dimuat sampai keluar tampilan.
**Solusi dari isu terkait proses *rendering***

    1. Taruh tag <script> eksternal sebelum tag penutup </body>
    Ini solusi paling umum agar dia mulai diproses setelah parsing HTML selesai.
    2. Taruh tag <script> sedini mungkin dan gunakan atribut async
    Atribut async akan membuat script tersebut diunduh tanpa menghentikan proses parsing dan dieksekusi seselesainya ia diunduh.
    3. Untuk script yang bergantung pada DOM, taruh tag <script> sedini mungkin, dan gunakan atribut defer
    Atribut defer akan membuat script tersebut diunduh tanpa menghentikan proses parsing dan dieksekusi seselesainya proses parsing selesai.

### Memanipulasi *Element* HTML
Penting untuk diingat, “DOM bukan bagian dari JavaScript, 
melainkan *browser* (Web API)”.
1. Mencari *Element* HTML
    - **.getElementsById**
    - **.getElementsByClassName**
    - **.querySelector**
2. Mengubah Konten *Element*
    - *Element* **.textContent**
    
        *Element* **.textContent** dapat kita gunakan untuk mengubah teks di dalam sebuah *element*.

    - *Element* **.innerHTML**

        *Element* **.innerHTML** dapat kita gunakan untuk mengubah konten HTML di dalam sebuah *element*.
3. Membuat *Element* HTML
    - **.createElement()**
    - **.textContent** untuk mengubah kontennya
    - **.appendChild()** untuk menambahkan ke DOM
4. Interaksi *User* (*Event*)

    *User experience* itu bersifat dua arah, selain menampilkan *element HTML*, halaman web juga harus bisa menangkap interaksi *user*.
5. Berbagai HTML DOM *Event*
    - *Change*
    - *Focus*
    - *Hover*
    - *Click*
    - *Blur*
    - *Scroll*
    - *Submit*
6. Menangkap Interaksi *User*
    - *Element* **.addEventListener(“event”)**
    - *Element* **.onevent**
7. *EventListener*

    Dengan cara *Element* **.addEventListener(“event”)**
    - Bisa dihilangkan
    - Bisa ada beberapa event listener yang sama untuk 1 *element*
    - Memiliki argumen tambahan { *options* }

***EventListener - Click***

Misalkan kita mempunyai element
        
        <input id=”user-input” /> 
dan
        
        <button id=”alert-button”>show</button>.

Kita ingin menampilkan pop up box yang berisi teks di dalam input tadi.

    // cari dulu kedua element tersebut berdasarkan id-nya

        const input = document.getElementById(“user-input”)
        const button = document.getElementById(“alert-button”)

    // baru tambahkan event listener
        
        button.addEventListener(“click”, function() {
	    alert(input.value)})

    // atau

        button.onclick = function() { alert(input.value) }

***EventListener - Blur***

“Blur”, lawan dari “focus”, adalah event dimana sebuah element kehilangan fokus dari user (misal user klik mouse di luar element tersebut atau user klik tab untuk berpindah element).
    
Misalkan kita ingin memvalidasi isi dari 
    
        <input id=”username” />
    
Agar panjangnya minimal 6 karakter..

    // cari dulu element tersebut berdasarkan id-nya

        const input = document.getElementById(“username”)

    // tambahkan event listener

        input.addEventListener(“blur”, () => {if(input.value.length < 6) alert(“Panjang username minimal 6”)})

***EventListener - Form Submission***

Misalkan kita mempunyai element beberapa input dalam sebuah form

    <input name=”email /> dan <input type=”password” name=”password” />
Bagaimana caranya  kita mendapatkan isi dari kedua input tersebut saat submit form?

Ada 2 cara:
    
- Pasang event listener di kedua input dan tombol submit, lalu saat tombol diklik, baca value dari kedua input tersebut. 
- Pasang event listener di form, lalu gunakan FormData untuk mengambil data dari masing-masing input

        const form = document.getElementById(“form”)

        form.addEventListener(“submit”, function(event) {
	        // cegah page refresh
	        event.preventDefault()

	        const formData = new FormData(form)
	        const values = Object.fromEntries(formData) // { email: ... }
        })
