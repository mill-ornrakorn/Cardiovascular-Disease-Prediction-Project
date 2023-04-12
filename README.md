## Cardiovascular Disease Prediction Project ❤🩺
Project นี้เป็นส่วนหนึ่งของรายวิชา CPE 378 การเรียนรู้ของเครื่อง (Machine Learning) สาขาวิชาวิทยาศาสตร์ข้อมูลสุขภาพ มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี ภาคเรียนที่ 2 ปีการศึกษา 2564

### 🙋‍♀️Group: อ๋อชื่อกลุ่ม
- [Papin Thanutchapat](https://github.com/Jappapin)
- [Piyatida Meesatean](https://github.com/Piyati)
- [Chiraphat Phoncharoenwirote](https://github.com/Chiraphatt)
- [Ornrakorn Mekchaiporn](https://github.com/mill-ornrakorn)

### 📁Dataset
ข้อมูลที่ใช้ในการวิเคราะห์ ประกอบด้วย ดังนี้ Cardiovascular Disease Dataset และ Synthetic Dataset

**1. Cardiovascular Disease Dataset**

เป็นข้อมูลเกี่ยวกับโรดหัวใจและหลอดเลือดของคนไข้ทั้ง 70,000 คน โดยมีผู้ป่วยเป็นโรคหัวใจและหลอดเลือด 34,979 คน และผู้ป่วยที่ไม่เป็นโรคหัวใจและหลอดเลือด 35,021
คน สามารถเข้าถึงได้โดย https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset

![CardiovascularDiseaseDataset](https://github.com/mill-ornrakorn/CPE378-Machine-Learning/blob/main/Final%20Project/pic/3.jpg?raw=true)
Cardiovascular Disease Dataset มีทั้งหมด 70,000 datapoints โดยประกอบด้วย 12 Columns ดังนี้
- age (อายุ) มีหน่วยเป็น วัน (days)
- weight (น้ำหนัก) มีหน่วยเป็นกิโลกรัม (kg)
- height (ส่วนสูง) มีหน่วยเป็นเซนติเมตร (cm)
- ap_hi (ความดันช่วงหัวใจบีบตัว หรือความดันตัวบน) มีหน่วยเป็นมิลลิเมตรปรอท (mmHg) ค่าปกติคือ 90-140 mmHg
- ap_Io (ความดันช่วงหัวใจคลายตัว หรือความดันตัวล่าง) มีหน่วยเป็นมิลลิเมตรปรอn (mmHg) ค่าปกติคือ 60-90 mmHg
- gender (เพศ) 1 หมายถึง เพศหญิง 2 หมายถึง เพศชาย
- smoke (การสูบบุหรี่) 0 หมายถึง ไม่สูบ 1 หมายถึง สูบ
- active (การออกกำลังกาย) 0 หมายถึง ไม่ออกกำลังกาย 1 หมายถึง ออกกำลังกาย
- alco (การดื่มแอลกอฮอล์) 0 หมายถึง ไม่ดื่ม 1 หมายถึง ดื่ม
- cardio (การป่วยเป็นโรคหลอดเลือดหัวใจ) 0 หมายถึง ไม่ป่วยเป็นโรคหลอดเลือดหัวใจ 1 หมายถึง ป่วยเป็นโรคหลอดเลือดหัวใจ
- cholesterol (โคเลสเตอรอล) 1 หมายถึง ปกติ 2 หมายถึง ผิดปกติ 3 หมายถึง ผิดปกติมาก
- gluc (ระดับน้ำตาลในเลือด) 1 หมายถึง ปกติ 2 หมายถึง ผิดปกติ 3 หมายถึง ผิดปกติมาก

**📍note that:** รายละเอียดการทำ Exploratory Data Analysis (EDA) และ Data Preparation สามารถดูได้เพิ่มได้ใน
[รายงาน](https://github.com/mill-ornrakorn/CPE378-Machine-Learning/blob/main/Final%20Project/%E0%B8%AD%E0%B9%8B%E0%B8%AD%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1_CPE378_%2BFinal%2BProject_%E0%B8%AD%E0%B9%8B%E0%B8%AD%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1_%E0%B8%A3%E0%B8%B2%E0%B8%A2%E0%B8%87%E0%B8%B2%E0%B8%99.pdf) 
หรือ[สไลด์](https://github.com/mill-ornrakorn/CPE378-Machine-Learning/blob/main/Final%20Project/%E0%B8%AD%E0%B9%8B%E0%B8%AD%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1_CPE378_%2BFinal%2BProject_%E0%B8%AD%E0%B9%8B%E0%B8%AD%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1_ppt.pdf) นะคะ

**2. Synthetic Dataset**
![SyntheticDataset](https://github.com/mill-ornrakorn/CPE378-Machine-Learning/blob/main/Final%20Project/pic/4.jpg?raw=true)

### 📝ขั้นตอนการออกแบบการวิเคราะห์
![algorithm](https://github.com/mill-ornrakorn/CPE378-Machine-Learning/blob/main/Final%20Project/pic/1.jpg?raw=true)


### 📋สรุปผลการวิเคราะห์
![result](https://github.com/mill-ornrakorn/CPE378-Machine-Learning/blob/main/Final%20Project/pic/2.jpg?raw=true)

