# DOM (Day 3)
- Dom adalah suatu jembatan agar dokumen dapat berinteraksi ke html yang berfungsi untuk memanipulasi struktur html
- Dom bukan merupakan bagian dari javascript

## Traversing
file html
<br> ![image](https://user-images.githubusercontent.com/85721388/192695809-613ef1a1-b4cd-419d-bd27-1917e5414b9e.png)

### Ke Bawah
-	getElementById(id) = untuk mengakses element HTML berdasarkan nilai id-nya.
 <br> ![image](https://user-images.githubusercontent.com/85721388/192693611-e5de0b2f-9031-430b-b3ad-67a4b1abe693.png)
<br>![image](https://user-images.githubusercontent.com/85721388/192693715-da4078f5-a10e-4586-a9f3-39c1e376a955.png)

-	getElementsByClassName(className) = Untuk mengakses element-element HTML berdasarkan nilai attribute class-nya
 <br>![image](https://user-images.githubusercontent.com/85721388/192696602-973c5f67-e0ed-4f9a-a08c-6fe0c5801b2c.png) 
 <br>![image](https://user-images.githubusercontent.com/85721388/192696487-3cc90191-1108-4eeb-a1f8-17fb5854de8d.png)
 <br>![image](https://user-images.githubusercontent.com/85721388/192696714-961d094f-da40-4087-a20e-5e241cb81aa6.png)
 <br>![image](https://user-images.githubusercontent.com/85721388/192696799-4d2b93fe-6dea-461a-a359-281de1a5c83a.png)

-	getElementsByTagName(tag) = Untuk mengakses element-element HTML berdasarkan jenis tag-nya
<br> ![image](https://user-images.githubusercontent.com/85721388/192694554-85c33e55-f6d0-4c38-97fe-ae820fa64507.png)
<br> ![image](https://user-images.githubusercontent.com/85721388/192694628-fc5daeae-ee88-43a2-a718-5f7d002936df.png)

-	querySelector Family  = Untuk mengakses element-element HTML berdasarkan CSS Selector-nya HTML
    - querySelector()
    <br> ![image](https://user-images.githubusercontent.com/85721388/192697347-d76fe400-2267-4ad1-82c5-8a92ed73d027.png)
    <br> ![image](https://user-images.githubusercontent.com/85721388/192697355-7a5968a1-ed9a-4f54-8b19-36d3da2db1df.png)
    <br> ![image](https://user-images.githubusercontent.com/85721388/192697367-fd7b63ee-cdfa-454a-9c39-eec14f826911.png)
    <br> ![image](https://user-images.githubusercontent.com/85721388/192697381-16c6c5fe-d3d7-4d78-9b12-cfaf3efa0c27.png)

    - querySelectorAll(cssSelector)
    <br> ![image](https://user-images.githubusercontent.com/85721388/192694858-1784d8da-ce89-458c-a83c-0e3a55251889.png)
    <br> ![image](https://user-images.githubusercontent.com/85721388/192697597-bad4b604-db88-4af5-9b93-af1c73c78925.png)

- children
<br>![image](https://user-images.githubusercontent.com/85721388/192694357-e59e5d50-c6dd-4409-ad6f-5f6adb1b0312.png)
![image](https://user-images.githubusercontent.com/85721388/192694419-391bef0f-f729-4443-811d-b2171f1cd402.png)


### Ke Atas
- parentElement
<br> ![image](https://user-images.githubusercontent.com/85721388/192694997-9e29e7e7-670a-4965-87ce-8d8db6e50b25.png)
<br> ![image](https://user-images.githubusercontent.com/85721388/192697867-40534601-80fb-4652-8b58-c7684bc9048d.png)

- closest()
<br> ![image](https://user-images.githubusercontent.com/85721388/192695071-a3b54883-7ae8-4f10-ae99-c63e4bcdf469.png)
<br> ![image](https://user-images.githubusercontent.com/85721388/192697844-0cafc357-6976-462f-8f95-f7836c5bbfbe.png)

### Ke Samping
- nextElementSibling
<br> ![image](https://user-images.githubusercontent.com/85721388/192695172-5301aff0-f9ac-4c4c-a55d-639eab19f2e0.png)
<br> ![image](https://user-images.githubusercontent.com/85721388/192695447-d3fb83fe-f61e-4188-bef1-a9183028d71c.png)

- previousElementSibling
<br> ![image](https://user-images.githubusercontent.com/85721388/192695110-5755ce69-7fec-47e9-949e-ee22fb267cb2.png)
<br> ![image](https://user-images.githubusercontent.com/85721388/192695501-b15a41d1-9490-4c4c-94c7-94ca15ebde48.png)

## Looping dan Traversing
<br> ![image](https://user-images.githubusercontent.com/85721388/192695620-762b0f2c-751a-43e1-90fe-2c4c14ba5cf3.png)
<br> ![image](https://user-images.githubusercontent.com/85721388/192695676-1e68734e-2846-416b-bc94-3f0ed4ddbac4.png)

