# Javascript (Day 5) 
-	Javascript merupakan sebuah cara untuk membuat web lebih interaktif
## Menyisipkan javascript
-	Internal Javascript dapat dijalankan di dalam file html
<br>![image](https://user-images.githubusercontent.com/85721388/192105359-c7de121f-512e-4ac9-a9d5-b9ad279f6a3d.png)

-	External javascript dapat dijalankan diluar file html namun file html ditambahkan code berikut 
<br> ![image](https://user-images.githubusercontent.com/85721388/192105363-d0afff70-10a4-47c3-ad13-90cc08d106fa.png)

## Type data
-	Type data primitive = String, Number, Boolean
-	Type data unprimitive = Array, Object
      1.	String = karakter dengan tanda kutip
      2.	Boolean = tipe data pembanding dengan true/false
## Menampilkan data
-	Alert berfungsi untuk menampilkan data dengan pop up
-	Confirm berfungsi untuk menampilkan data dengan pop up namun menghasilkan nilai jika oke (true) tapi jika cancel (false)
## comment
-	Single comments //
-	Multiline comment /* */
## Operator
-	Operator aritmatika
 <br>![image](https://user-images.githubusercontent.com/85721388/192105376-049db5e1-73ac-477c-9560-b942706370eb.png)

-	Operator pembanding
 <br>![image](https://user-images.githubusercontent.com/85721388/192105389-ee18b397-5633-4aac-a01d-5c9a171fa61d.png)

-	Operator logika
 <br>![image](https://user-images.githubusercontent.com/85721388/192105396-aaa21746-4bde-4991-ac5b-0a184d676a2c.png)

## Scope

-	Lingkup Global = sebuah variabel bisa diakses dari mana saja, baik di dalam maupun di luar dari suatu fungsi atau blok (grup) kode
<br> ![image](https://user-images.githubusercontent.com/85721388/192105401-ffcba13d-f97e-49f7-a5b0-752f008ecfb3.png)

-	Lingkup Lokal = sebuah variabel hanya bisa diakses di dalam sebuah fungsi atau blok kode.
    1.	lingkup fungsi (function scope)
          -	var = terlalu bebas sehingga tidak muncul error walaupun variabel sama, boleh diluar lokasi  kurung
    2.	lingkup blok (block scope) 
          -	let = akan error jika pendeklarasian/variabel sama harus dalam satu lokasi kurung
          -	const = tidak dapat diubah sama sekali karena sudah tetap
 <br>![image](https://user-images.githubusercontent.com/85721388/192105406-fa328581-5b67-4e0a-b260-05ff3149c16f.png)

## Function
<br> ![image](https://user-images.githubusercontent.com/85721388/192105413-07ce6444-b94f-4906-b066-236336ffde99.png)

## conditional
-	Conditional merupakan suatu kondisi jika.. maka...
-	Conditional berfungsi agar aplikasi lebih dinamis dan terintegrasi 
-	Kondisi ada beberapa yaitu
    1.	if else
    2.	switch case
-	Truthy merupakan kondisi jika benar
-	False merupakan kondisi jika salah
-	Ternary operator sama seperti if else dan penulisannya lebih singkat hanya sebaris namun tidak cocok untuk kondisi yang panjang
Let makan
Makan? Console.log ("kenyang") : console.log("lapar")
## looping
-	Looping adalah suatu perulangan sampai kondisi tercapai
-	Looping terdiri dari for loop, while do
## DOM
-	getElementById(id) = untuk mengakses element HTML berdasarkan nilai id-nya.
 <br>![image](https://user-images.githubusercontent.com/85721388/192105420-82786027-84c0-4866-a963-dd065d2f5e56.png)

-	getElementsByTagName(tag) = Untuk mengakses element-element HTML berdasarkan jenis tag-nya
<br> ![image](https://user-images.githubusercontent.com/85721388/192105425-a78a46ce-3d9c-48b1-a6c6-c2ca54716b0a.png)

-	getElementsByClassName(className) = Untuk mengakses element-element HTML berdasarkan nilai attribute class-nya
 <br>![image](https://user-images.githubusercontent.com/85721388/192105429-9f6ad9ca-cdd3-42a6-ac6f-d9ce9c03fbf3.png)

-	querySelectorAll(cssSelector) = Untuk mengakses element-element HTML berdasarkan CSS Selector-nya HTML
 <br>![image](https://user-images.githubusercontent.com/85721388/192105437-5227a8da-fbd7-48b4-bc35-27b4adbd5fec.png)


## Mengubah element
-	element.innerHTML = untuk mengambil/mengubah isi HTML dari sebuah element.
<br> ![image](https://user-images.githubusercontent.com/85721388/192105441-491d98f7-e4b2-406e-99c8-edff419b9c5c.png)

-	element.attribute = untuk mengambil/mengubah/menambah nilai attribute dari sebuah element.
<br> ![image](https://user-images.githubusercontent.com/85721388/192105448-880be500-73c7-4da3-82c0-b324f81961b0.png)

-	element.setAttribute(attribute, nilai) = seperti element.attribute namun setAttribute itu termasuk DOM Method sedangkan element.attribute itu DOM Property.
<br> ![image](https://user-images.githubusercontent.com/85721388/192105454-395c5353-8aa1-42eb-b274-b72c588f61f9.png)

-	element.style.property = adalah untuk mengambil/mengubah/menambah CSS dari element HTML
<br>![image](https://user-images.githubusercontent.com/85721388/192105466-f88f47ce-3d92-47c9-ba08-74ccf27ece3c.png)
<br>![image](https://user-images.githubusercontent.com/85721388/192105472-0523add3-66e3-46f1-a909-2f99d0421e39.png)
