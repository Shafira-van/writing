# Testing
## Tipe Testing
-	Manual 
<br>  ![image](https://user-images.githubusercontent.com/85721388/200870422-ffbeec6e-aaa7-4a06-837c-58776e72256d.png)
![image](https://user-images.githubusercontent.com/85721388/200870445-c15129e1-9916-457d-85fa-64caf4e50f9a.png)

-	Automation
    - Unit Test = membuat komponen dari yang paling kecil seperti function
    - Integration = melakukan testing dari satu aplikasi terhubung dengan system yang lain
    - End to end = dari sisi user
## 2 Cara nulis testing
-	Buat fitur -> testing
-	Testing -> buat fitur 
## Elemen berdasarkan accessibility
-	Access by everyone
    - getByRole
    - getByLabelText
    - getByPlaceholderText
    - getByText
-	Semantic queries
    - getByAllText
    - getByTitle
-	Test ID
    - getByTestId


## Contoh
### Tanpa Components
-	app.test.js
<br> ![image](https://user-images.githubusercontent.com/85721388/200870523-ab0eba4e-9b4b-4cc2-8c5b-046cd9a76ebd.png)

-	app.js
<br> ![image](https://user-images.githubusercontent.com/85721388/200870554-2d8f0de1-b2b6-4602-b25b-80e3ef036a6e.png)

### Dengan Components
-	Counter.jsx
<br> ![image](https://user-images.githubusercontent.com/85721388/200870573-6aa82888-c0ee-4e58-8803-51ca7bfb5215.png)

-	Counter.test.js
<br> ![image](https://user-images.githubusercontent.com/85721388/200870596-406264c0-144c-4415-9569-f471d2d38eb4.png)
<br>![image](https://user-images.githubusercontent.com/85721388/200871127-5b37a807-21e8-4af4-9cb0-b9a61834e2e9.png)
<br>![image](https://user-images.githubusercontent.com/85721388/200871161-38109f2b-ef45-4cb5-b38a-e05d5ff70aae.png)


## Perintah
- Npm run test
 
 


