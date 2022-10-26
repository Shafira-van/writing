# Komponen dan Style React (Day 2)

## Pemangggilan komponen
![image](https://user-images.githubusercontent.com/85721388/197697806-57bf7c47-30a8-4f65-a1f0-1ccc3059796b.png)
![image](https://user-images.githubusercontent.com/85721388/197697835-772c4b4f-2cb6-409f-b018-a98aa7ae2129.png)
 
## state dan props
- stateful = memiliki state dan bisa mengirim state ke component
- stateless = tidak memiliki state dan hanya memiliki props 
### state 
- objek yang menyimpan data
- contoh 
  <br>![image](https://user-images.githubusercontent.com/85721388/197697936-c832b8b6-aaaa-4146-8961-f46dd896af85.png)

- useState = lokal state
  <br>![image](https://user-images.githubusercontent.com/85721388/197697955-76749bf5-0186-494f-a12b-fecb67f8916a.png)


### props 
- merupakan jalur komunikasi antara parent dan child / pemberian data antara komponen
![image](https://user-images.githubusercontent.com/85721388/197698283-c0633aeb-1fcd-4e4e-8653-5004841a952c.png)
![image](https://user-images.githubusercontent.com/85721388/197698316-70107ddb-4034-4179-b7d8-c07781d21ac2.png)
  
## Css di react
### External CSS  
  - Home.css
    <br>![image](https://user-images.githubusercontent.com/85721388/197698583-6667bdd5-8fd8-4e25-b4a1-a4528302ce50.png)
  - App.js
    <br>![image](https://user-images.githubusercontent.com/85721388/197698758-af66b9e8-58cc-4846-8aba-36a3f7ef7afe.png)

### Inline CSS
![image](https://user-images.githubusercontent.com/85721388/197698782-b1e25a52-cf0f-456d-8112-60379b4a8508.png)

 
### CSS dalam props
![image](https://user-images.githubusercontent.com/85721388/197698823-bf5229f0-b466-4cfd-8d96-3a3136966f81.png)

![image](https://user-images.githubusercontent.com/85721388/197698789-9000b9cb-6312-48be-9454-5f2ffcaa128c.png)
 
 ## Bootstrap
 ### menyisipkan link bootstrap di index.html
 - CSS = < link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
- JS = <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>

 
 ### menginstall bootstrap
- npm install bootstrap
- tambahkan link dibawah ke index.js/main.js
  - import "bootstrap/dist/css/bootstrap.min.css"
  - import "bootstrap/dist/js/bootstrap.bundle.min"

