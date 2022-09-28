# Method dan Prototype (Day 2)
## Data Type Built In dan Method
-	Typeof berfungsi untuk menetapkan variable sehingga tidak bisa diubah lagi
-	Property ciri ciri dari string
- Method adalah keahlian, suatu fungsi yang telah disediakan oleh javascript
- Data Type
  - number = tipe data yang mengandung semua angka termasuk angka desimal.
  - string = mengandung huruf, angka, simbol dalam bentuk kata, Harus diawali dan diakhiri dengan single quotes ‘ … ‘ ataupun double quotes “ … “.
  - boolean = true dan false
  - null = sebuah data tidak memiliki nilai, Tipe data null biasanya diperoleh dalam kondisi normal dan sudah kita rencanakan
  - undefined = tipe data yang merepresentasikan data yang tidak memiliki nilai, Tipe data undefined biasanya didapat dari hasil kesalahan program (error), kelalaian programmer, dan tidak direncanakan
    Undefined didapat dari hasil berikut:
    - Nilai dari pemanggilan variabel yang belum didefinisikan
    - Nilai dari pemanggilan element array yang tidak ada
    - Nilai dari pemanggilan property objek yang tidak ada
    - Nilai dari pemanggilan fungsi yang tidak mengembalikan nilai (return)
    - Nilai dari parameter fungsi yang tidak memiliki argumen
  - object = koleksi data yang saling berhubungan (related). Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya).
  
- Methode
  - string
    - toUpperCase() membuat semua huruf menjadi huruf besar
    - toLowerCase() membuat semua huruf menjadi huruf kecil
    - charAt() mengembalikan karakter berdasarkan posisi indexnya
    - includes() melakukan pencarian didalam string
    - split() memisahkan sebuah string menjadi data array berdasarkan spasi
  - number
    - isnan() memberitahu yang bukan angka
    - toString() mengganti angka menjadi string
    - toFixed() mengambil beberapa angka di belakang koma dan merubahnya menjadi string
    - number(pi.tofixed(2)) merubah string menjadi number
  - Math
    - Math.pi
    - Math.abs
    - Math.pow
    - Math.sqrt() = akar dari
  - Date
    - getFullYear()  
## prototype 
prototype adalah mekanisme yang mampu menurunkan satu fitur ke fitur yang lain
- membuat method baru dengan tipe data string
<br>![image](https://user-images.githubusercontent.com/85721388/192717102-23a4455b-3389-4504-8ba9-5593c3a1561c.png)
<br>![image](https://user-images.githubusercontent.com/85721388/192717812-f3d50e34-b6aa-4e59-9227-22deaec45e1f.png)



## referensi 
  - mdn web docs 
