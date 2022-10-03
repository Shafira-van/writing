# ARRAY
- Array adalah tipe data yang mampu menyimpan banyak data
## Method Pada Array
- Array.length = untuk melihat panjang data
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505633-d7053855-4a7a-41a8-932e-f099c3c67cc2.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505640-1729aff3-0b51-4708-a1ec-e2ed8c992076.png)

- Array.push()= untuk memasukkan data ke belakang
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505644-3f3d5d83-6a82-4a29-bfb8-ca481da805ac.png)

  - Output 
  <br>![image](https://user-images.githubusercontent.com/85721388/193505653-f3d9c5e0-7b26-4d8d-ba23-b409325b0527.png)

- Array.unshift() untuk menambahkan data ke depan
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505666-b945776c-9b64-4b0b-a21a-baf40a0b260b.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505671-434066e3-1c9a-4e22-9606-1947a1e3f453.png)

 
- array.pop() = menghapus data terakhir
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505685-f4cc6955-d063-4ded-9c1a-6953d0486306.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505696-71e9c6bd-3250-49bf-98ca-69c25848d38d.png)

 
- array.shift() = menghapus data awal
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505709-ba23c079-3d04-4148-935c-22fae9e10153.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505721-13cf58bc-5189-4ce5-95b4-f58fc1179da1.png)

- array.splice(index awal, jumlah yang dihapus, var baru) = menghapus, menyisipkan, mengambil data di index tengah
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505748-4554f172-69e4-43e5-b48a-d895c2178422.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505754-859aae9e-61e5-4445-8790-12923ab90dc1.png)

  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505758-9535c26a-cf3a-4899-90b6-e6bef22bc5fb.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505761-19693d40-37f8-4168-a7de-88ebd5dce64f.png)

  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505770-19183ae9-e111-426e-b70c-f320ebc9ec54.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505785-0f829d85-bdd4-4611-bfc5-99436f28c391.png)

 
- array.slice(index awal, < index akhir) = memanipulasi data array namun tidak merubah data sebenarnya (copy)
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505818-9bdada0d-f22b-467e-a5fd-e10b0a6dd7ff.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505823-ab796ebc-846a-4088-8f2c-131f8e47ac6e.png)

 
- array.map () = melakukan perulangan dan dikembalikan dalam bentuk array
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505834-a98df716-089c-4353-a02e-2001e169101b.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505841-979db1ea-666f-4861-853a-a4410049da61.png)

 
## looping array
- For let
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505850-449ff8a2-30e8-48ea-b40c-23b7f6764d8b.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505854-c328c02c-33d0-4caa-87e0-33ea08b74493.png)

  
- For of
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505864-ca650981-7336-4579-95b0-5651d15317df.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193505871-81a1b6a1-3e75-42ee-88cf-4089d506bfa2.png)

  
- ForEach = tanpa return hanya perulangan
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505883-c081de35-85c4-45e5-999b-139b5aafb5b2.png)

  - Output
  <br>![image](https://user-images.githubusercontent.com/85721388/193506220-5f9970b9-d1f5-43fe-bf31-1b8739ea9eac.png)

  Atau menggunakan index
  - JavaScript
  <br>![image](https://user-images.githubusercontent.com/85721388/193505910-5dcae1e7-449b-4711-adae-a66f6dca6c68.png)

  - Output
  <br> ![image](https://user-images.githubusercontent.com/85721388/193505919-eb5c7e20-29ca-47a3-9863-76a59b9ee351.png)

 
## Perbedaan Map dan ForEach
- Map = data yang dikembalikan berupa array dan dikembalikan dengan return
- ForEach = data tidak berupa array hanya perulangan biasa 
- Contoh :
  - JavaScript
  <br> ![image](https://user-images.githubusercontent.com/85721388/193505933-9c925909-aead-484f-8ba9-1c925291c41a.png)
  - Output
  <br>  ![image](https://user-images.githubusercontent.com/85721388/193505946-9ed01cc3-df1e-4253-8033-d58001261627.png)

## Kapan penggunaan For, Map dan ForEach 

## Array multidimensi 
- JavaScript
<br> ![image](https://user-images.githubusercontent.com/85721388/193505955-dd10d17f-eb00-4aaa-9f65-43435de76f39.png)

- Output
<br> ![image](https://user-images.githubusercontent.com/85721388/193505959-379f15a4-cf46-4908-85c9-405cfcb2ff6f.png)

 
