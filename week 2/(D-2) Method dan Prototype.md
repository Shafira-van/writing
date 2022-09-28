# Method dan Prototype (Day 2)
## Data Type Built In dan Method
-	Typeof berfungsi untuk menetapkan variable sehingga tidak bisa diubah lagi
-	Property ciri ciri dari string
- Method adalah keahlian, suatu fungsi yang telah disediakan oleh javascript
- Prototype adalah mekanisme yang mampu menurunkan satu fitur ke fitur yang lain
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
  
- Method
  - string
    - toUpperCase() membuat semua huruf menjadi huruf besar
    <br>![image](https://user-images.githubusercontent.com/85721388/192725830-97601798-cecf-4456-90fe-7eb9ca4cef5a.png)
    <br>Output : HAI 
    - toLowerCase() membuat semua huruf menjadi huruf kecil
    <br>![image](https://user-images.githubusercontent.com/85721388/192726041-955de870-169b-497e-9558-b2f1981f3ef4.png)
    <br>Output : hai
    - charAt(n) mengembalikan karakter berdasarkan posisi indexnya
    <br>![image](https://user-images.githubusercontent.com/85721388/192726230-ff758ec7-c2fe-4f09-bb31-8af73ce52119.png)
    <br>Output : I
    - includes() melakukan pencarian didalam string
    <br>![image](https://user-images.githubusercontent.com/85721388/192726626-86716398-2e33-4c5f-b6e0-1c45cdb1472a.png)
    <br>Output : true
    - split() memisahkan sebuah string menjadi data array berdasarkan spasi
    <br>![image](https://user-images.githubusercontent.com/85721388/192727009-f344d7bb-39a9-41eb-a030-3aa21b78fa57.png)
    <br>![image](https://user-images.githubusercontent.com/85721388/192727161-807763c0-1986-4270-97c1-297f2ef80df6.png)

  - number
    - isnan() memberitahu yang bukan angka
    <br>![image](https://user-images.githubusercontent.com/85721388/192725199-b5bbcab2-e0ea-4c9a-92fe-2d65a1676b88.png)
    <br>Output : true
    - toString() mengganti angka menjadi string
    <br>![image](https://user-images.githubusercontent.com/85721388/192723889-ef952400-cb1c-4169-9882-42d3a91a6ee2.png)
    <br>Output : "20"
    - toFixed() mengambil beberapa angka di belakang koma dan merubahnya menjadi string
    <br>![image](https://user-images.githubusercontent.com/85721388/192724277-0663a5d6-906d-45ba-be1e-fc3bee10ce53.png)
    <br>![image](https://user-images.githubusercontent.com/85721388/192724369-45b4c569-ae8f-4de9-99d7-aa29128754d3.png)
    - number() merubah string menjadi number
    <br>![image](https://user-images.githubusercontent.com/85721388/192724842-48335c09-dc8c-402c-bad3-b35570bb44ef.png)
    <br>Output : 3.41

  - Math
    - Math.pi = 3,14
    - Math.E = Bilangan Euler
    - Math.LN2 = Log 2 
    - Math.LN10 = Log 10
    - Math.LOG2E = Log E di Basis 2
    - Math.LOG10E = Log E di Basis 10
    - Math.SQRT1_2 = Akar Kuadrat dari 0.5
    - Math.SQRT2 = Akar Kuadrat dari 2
    - Math.abs(x) = mengubah nilai x dari negatif menjadi positif (absolute) 
    - Math.pow(x,y) = x pangkat y
    - Math.sqrt(x) = akar kuadrat dari x
    - Math.cbrt(x) = menghitung akar pangkat 3 dari x.
    - Math.round(x) = Digunakan untuk membulatkan angka desimal x menjadi bilangan bulat.
    - Math.floor(x) = Digunakan untuk membulatkan angka desimal x ke bawah.
    - Math.ceil(x) = Digunakan untuk membulatkan angka desimal x ke atas.
    - Math.random() = Digunakan untuk menampilkan angka secara acak antara 0 hingga 1 (0 termasuk. 1 tidak).
    - Math.max(x, y, z, ..., n) = Digunakan untuk mencari angka terbesar di antara parameter x, y, z, ..., n.
    - Math.min(x, y, z, ..., n) = Digunakan untuk mencari angka terkecil di antara parameter x, y, z, ..., n.
    
  - Date
    - getFullYear()  
    <br>![image](https://user-images.githubusercontent.com/85721388/192728658-c49245fa-c0ea-468f-9597-4afdca98685f.png)
    <br>![image](https://user-images.githubusercontent.com/85721388/192728725-fd909748-8319-4558-92d2-76b75dfab6cb.png)

- membuat method baru dengan tipe data string
<br>![image](https://user-images.githubusercontent.com/85721388/192717102-23a4455b-3389-4504-8ba9-5593c3a1561c.png)
<br>![image](https://user-images.githubusercontent.com/85721388/192717812-f3d50e34-b6aa-4e59-9227-22deaec45e1f.png)

## referensi 
  - mdn web docs 
