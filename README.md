<div align="center">
 <h1>Card Check <img src="https://64.media.tumblr.com/65a34a47a25662c619588f434def7221/127eb2e64f13cf30-67/s1280x1920/d66f676fd01adaae32172d4e76278803ec4c5430.gif" width="70px"></h1>
<a href="https://github.com/Ileriayo/markdown-badges"><img src="https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white" /></a>
<a href="https://github.com/Ileriayo/markdown-badges"><img src="https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white" /></a>
<a href="https://github.com/Ileriayo/markdown-badges"><img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white" /></a>
<a href="https://github.com/Ileriayo/markdown-badges"><img src="https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white" /></a>
<a href="https://github.com/Ileriayo/markdown-badges"><img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" /></a>
</div>


<img width="100%" height="60%" src="https://github.com/Intummadee/CardCheck/blob/main/assets/edit_version2.3.png?raw=true">
<img width="100%" height="60%" src="https://github.com/Intummadee/CardCheck/blob/main/assets/edit_version2.2.png?raw=true">

<img width="50%" height="60%" src="https://github.com/Intummadee/CardCheck/blob/main/assets/%E0%B8%A3%E0%B8%B2%E0%B8%A2%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%99%E0%B8%B1%E0%B8%81%E0%B8%A8%E0%B8%B6%E0%B8%81%E0%B8%A9%E0%B8%B2.png?raw=true">

## Getting Started
To get started, follow these steps:
1. Clone this repository using `git clone https://github.com/Intummadee/CardCheck.git`
2. Install dependencies using `npm install`
3. Run the app using `npm start`

## Tech Stack :
- **Frontend:** HTML, CSS, Bootstrap,  
- **Backend:** Python Django,  
- **Framework:** Django
- **Library:** Opencv, Pandas, JQuery
- **Database:** MongoDB Atlas, Django Database
- **Version Control:** Git and GitHub
- **Code Editor and tools**: VS Code


## 🕊️ **Initialize** 

- create Environment 
```python -m venv env```

- activate Environment 
--> 👉 ```env\Scripts\activate```
If you can run it, there will be the word (env) in front of PS in the terminal.

- create **app.py**

<details> 
  <summary><h2> 🛥️ Dependency </h2></summary>

 
  <h3>Scientific Computing and Mathematics</h3>
  <ul>
   <li> <b><i> python -m pip install numpy </i></b></li>
   <li> <b><i> python -m pip install scipy </i></b></li>
  </ul>

  <h3>Data Visualization</h3>
  <ul>
   <li> <b><i> python -m pip install matplotlib </i></b></li>
  </ul>

  <h3>Computer Vision</h3>
  <ul>
   <li> <b><i> python -m pip install opencv-python </i></b></li>
   <li> <b><i> python -m pip install opencv-contrib-python </i></b></li>
  </ul>
  
  <h3>Optical Character Recognition (OCR)</h3>
  <ul>
   <li> <b><i> pip install pytesseract </i></b> : a Python wrapper for Google's Tesseract-OCR Engine, used for optical character recognition (OCR).</li>
  </ul>
  
  <h3>Document Generation</h3>
  <ul>
   <li> <b><i> pip install reportlab </i></b> : a library for generating PDF documents.</li>
  </ul>

  <h3>Excel Data Handling</h3>
  <ul>
   <li> <b><i> python -m pip install pandas </i></b> : a powerful data manipulation and analysis library (useful for working with Excel files as well)</li>
   <li> <b><i> python -mpip install openpyxl </i></b> : a library specifically for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files</li>
  </ul>
  
  <h3>Environment Management</h3>
  <ul>
   <li> <b><i> python -m pip install python-dotenv </i></b> : allows you to load environment variables from a .env file into the environment</li>
  </ul>
  
  <h3>File Handling and PDF Manipulation</h3>
  <ul>
   <li> <b><i> pip install pymupdf Pillow </i></b> : Installs PyMuPDF (for working with PDF files) and Pillow (for image processing tasks)</li>
  </ul>
</details>


- ⚠️ Option, if WARNING is given, update the version.
```python -m pip install --upgrade pip```


🍫 Install Django
```python -m pip install Django```

-Option คำสั่ง check ว่าลง django หรือยัง
```django-admin --version```
--> รันแล้วได้ 4.2.10

create Project
```django-admin startproject my_tennis_club```

## 🪼 คำสั่งรัน !!!
```js
env\Scripts\activate
cd my_tennis_club  (อย่าลืมว่าต้องอยู่ใน my_tennis_club)
python manage.py runserver
http://127.0.0.1:8000/  (เปิด path นี้)
```

---

## หน้า Admin
- ไว้ดูข้อมูล user ของ Django รหัสผ่านและชื่อบัญชีอยูในไฟล์ .env
```
http://127.0.0.1:8000/admin
```
- คำสั่งสร้างบัญชี admin เพื่อดูข้อมูล user โดยพวก password ต้องตรงเงื่อนไขที่ Django ต้องการเท่านั้น ไม่งั้นจะสร้างแล้วใช้งานไม่ได้
```
python manage.py createsuperuser
```

---

# ใช้งาน MongoDB
https://account.mongodb.com/account/login?n=https%3A%2F%2Fcloud.mongodb.com%2Fv2%2F65d359c147d94142e1d9fb54&nextHash=%23metrics%2FreplicaSet%2F65d35a0f89492b3df0336104%2Fexplorer%2Fpymongo_demo%2Fdemo_collection%2Ffind&signedOut=true

Source : https://www.youtube.com/watch?v=GJCKIGeK3qc
```JS
python -m pip install "pymongo[srv]"
```

---

# Tesseract วิธีทำให้อ่านข้อความภาษาไทย

https://gist.github.com/dogterbox/7c0ed7387a388f5e13afd00f0cb8cd50
ดาวน์โหลด raw file ของเว็บนี้ https://github.com/tesseract-ocr/tessdata_best/blob/main/tha.traineddata ลงในที่ที่เก็บ ```\Tesseract-OCR\tessdata folder```

---

# ฝั่งFrontEnd
&emsp; https://github.com/atisawd/boxicons

&emsp; https://boxicons.com/

&emsp; https://css-loaders.com/progress/

---

## Extension แนะนำให้โหลดใน Vs code สำหรับอ่าน comment 
- Better-comments
- Comment Styler

---

## ข้อจำกัด
1. ไฟล์ที่อัพโหลด ต้องเป็น pdf เท่านั้น และ ขนาดตัวอักษรในไฟล์ควรมากกว่า 18
2. ตารางใน excel ควรจะชิดกันให้มากที่สุด เพื่อที่จะได้จับข้อความเป็นประโยคเดียวกัน เช่น  64070257 Hydro Carbon ถ้าแต่ละ column ในตารางห่างกันมากเกินไป ชื่อสามอย่างนี่ก็จะแยกออกจากกันไม่รวมในแถวเดียวกันได้ สามารถดูตัวอย่างภาพได้ใน example_image
3. ภาพที่ได้ต้องมีความชัด มีแสงสว่างเพียงพอ ระยะห่างจากกล่องไม่มากเกินไป หรือ น้อยเกินไป
4. บัตรที่ความเงา อย่าง บัตรประชาชน ไม่ควรถ่ายให้ติดเงามากเกินไป เพราะโปรแกรมจะไม่จับข้อความตรงที่มีเงา (สามารถแก้ได้แล้วโดยใช้เทคนิค Contrast Limited Adaptive Histogram Equalization (CLAHE) เพื่อปรับแสงในภาพให้ดียิ่งขึ้น)

---

# อ้างอิง
&emsp; สำหรับ ใช้ computer vision OCR ในการตรวจหาข้อความในภาพ
https://github.com/UB-Mannheim/tesseract/wiki

&emsp; MongoDB and Python
https://www.youtube.com/watch?v=GJCKIGeK3qc

&emsp; How to Install Tesseract OCR on Windows and use it with Python
https://www.youtube.com/watch?v=GMMZAddRxs8

&emsp; Stackoverflow
https://stackoverflow.com/questions/37745519/use-pytesseract-ocr-to-recognize-text-from-an-image
https://stackoverflow.com/questions/21104664/extract-all-bounding-boxes-using-opencv-python


&emsp; Python – Extract names from string with python Regex
https://itecnote.com/tecnote/python-extract-names-from-string-with-python-regex/


&emsp; Python | Similarity metrics of strings
https://www.geeksforgeeks.org/python-similarity-metrics-of-strings/


&emsp; using SequenceMatcher.ratio()
https://www.geeksforgeeks.org/python-similarity-metrics-of-strings/

&emsp; alertifyjs
https://alertifyjs.com/

<br>
<div> 
 <a href="https://www.linkedin.com/in/intummadee-maliyam-800856226/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
 <a href = "mailto:intummadee@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://github.com/Intummadee?tab=repositories" target="_blank"><img alt="All Repositories" title="All Repositories" src="https://img.shields.io/badge/-All%20Repos-2962FF?style=for-the-badge&logo=koding&logoColor=white"/></a>
</div>

