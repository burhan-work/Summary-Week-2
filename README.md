# JavaScript Dasar
## ***Introduction***
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
