## Cardiovascular Disease Prediction Project ❤🩺
Project นี้เป็นส่วนหนึ่งของรายวิชา CPE 378 การเรียนรู้ของเครื่อง (Machine Learning) สาขาวิชาวิทยาศาสตร์ข้อมูลสุขภาพ มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี ภาคเรียนที่ 2 ปีการศึกษา 2564


### 🙋‍♀️Group: อ๋อชื่อกลุ่ม
- [Papin Thanutchapat](https://github.com/Jappapin)
- [Piyatida Meesatean](https://github.com/Piyati)
- [Chiraphat Phoncharoenwirote](https://github.com/Chiraphatt)
- [Ornrakorn Mekchaiporn](https://github.com/mill-ornrakorn)


โรคหัวใจและหลอดเลือด (cardiovascular disease, CVD) เป็นกลุ่มโรคที่เกิดจากความผิดปกติ
ของหัวใจหรือหลอดเลือด ได้แก่ โรคหลอดเลือดหัวใจ (coronary heart disease) โรคหลอดเลือดสมอง (cerebrovascular disease) โรคเส้นเลือดแดงส่วนปลายอุดตัน (peripheral artery disease) ภาวะ
หลอดเลือดดำ อุดตัน (deep vein thrombosis) และภาวะลิ่มเลือดอุดตันในปอด (pulmonary embolism) เป็นต้น ปัจจัยเสี่ยงหลักที่สำ คัญของโรคหัวใจและหลอดเลือด เกิดจากพฤติกรรมการใช้ชีวิตประจำวันที่ไม่ถูกต้อง ได้แก่ การรับประทานอาหารที่มีรสเค็มจัด หรืออาหารไขมันสูง การไม่ออกกำ ลังกาย การสูบบุหรี่ และการดื่มแอลกอฮอล์ ปัจจัยเสี่ยงดังกล่าวจะนำ ไปสู่ภาวะความดันโลหิตสูง ระดับน้ำ ตาลในเลือดสูง ระดับไขมัน ในเลือดสูง ภาวะน้ำ หนักเกินหรือโรคอ้วน และเกิดโรคหัวใจและหลอดเลือดในที่สุด โรคหัวใจและหลอดเลือด
เป็นโรคที่พบมากในผู้สูงอายุ [(1)](https://ccpe.pharmacycouncil.org/index.php?option=seminar_detail&subpage=seminar_detail&id=1623)

จากการรายงานสถิติขององค์การอนามัยโลก (WHO) ในปี 2563 พบว่า โรคหัวใจและหลอดเลือด (cardiovascular diseases) คือกลุ่มโรคที่เป็นสาเหตุการตายอันดับ 1 ของคนทั่วโลก โดยมีผู้เสียชีวิตจาก กลุ่มโรคนี้ประมาณ 17.9 ล้านคน และสำหรับสถิติข้อมูลการเสียชีวิตของคนไทย ในกลุ่มโรคหัวใจและหลอดเลือด พบว่า ร้อยละ 80 เสียชีวิตด้วยกล้ามเนื้อหัวใจขาดเลือดเฉียบพลัน อีกทั้งข้อมูลจากกรมการแพทย์ ปี 2557 พบว่า ประเทศไทยมีค่าใช้จ่ายในการรักษาพยาบาลเฉลี่ยของผู้ป่วยโรคหัวใจถึง 6,906 ล้านบาทต่อปี และมีแนวโน้มการป่วยเพิ่มขึ้นอย่างต่อเนื่อง ซึ่งส่งผลกระทบต่อคุณภาพชีวิตของประชาชน เกิดความสูญเสียทางเศรษฐกิจจากการเสียชีวิตก่อนวัยอันควร ทั้งในระดับบุคคล ครอบครัว สังคม และประเทศชาติ [(2)](https://ddc.moph.go.th/odpc6/news.php?news=14902&deptcode=odpc6&news_views=265)

จากสถิติที่กล่าวว่าโรคโรคหัวใจและหลอดเลือดเป็นสาเหตุสำคัญในการเสียชิวิตของประชากรส่วนใหญ่ซึ่งวิธีในการช่วยเพิ่มโอกาสในการรักษา และเพิ่มอัตราการรอดชีวิตสามารถทำได้หากวิฉัยโรคโรคได้เร็ว การทำเทคโนโลยีทางคอมพิวเตอร์อย่างการเรียนรู้ของเครื่องเข้ามาช่วยในการวินิจฉัยจึงเป็นหนึ่งในทางเลือกที่เหมาะสม

ดังนั้นในการทำ Project ในครั้งนี้ คณะผู้จัดทำจึงเลือกอัลกอริทึม 3 แบบ คือ Logistic
Regression Classifier, Random Forest Classifier, และ eXtreme Gradient Boosting (XGBoost)
นำมาใช้ในการสร้างแบบจำลองทำนายความเสี่ยงโรคหลอดเลือดหัวใจจากชุดข้อมูล Cardiovascular
Disease

## 💡Objectives
- เพื่อเปรียบเทียบความถูกต้องของอัลกอริทึมทั้ง 3 แบบ ได้แก่ Logistic Regression Classifier, Random Forest Classifier, และ eXtreme Gradient Boosting (XGBoost)
- เพื่อหาอัลกอริทึมที่สามารถสร้างแบบจำลองในการทำนายความเสี่ยงโรคได้ถูกต้องที่สุด


## ⚙ Algorithms ที่เลือกใช้
 - **Ensemble Method**
    - เป็นวิธีการปรับปรุงแบบจำ ลองเดิมให้สามารถรับมือกับปัญหาที่มีความซับซ้อนมากขึ้นได้ ซึ่งเป็นการรวบรวมหลายแบบจำ ลองด้วยวิธีต่าง ๆ เพื่อให้ได้แบบจำลองสุดท้ายที่มีประสิทธิภาพ และแม่นยำมากขึ้น Ensemble ใน Machine Learning ที่มักใช้กันบ่อยมี 2 วิธี ได้แก่
        1. Bagging (ย่อมาจาก Bootstrap Aggregation) ซึ่งเป็นพื้นฐานของ **Random Forest Classifier** ใน scikit-learn library
        2. Boosting ซึ่งเป็นพื้นฐานของ AdaBoost หรือ Gradient Boosting ในไลบรารี่เช่น
        **XGBoost** และ LightGBM

- **GridSearchCV** [(3)](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
    - เป็นไลบรารี่ sklearn สำหรับการปรับพารามิเตอร์ในโมเดล GridSearchCV เป็นอัลกอริทึมประเภท Exhaustive search 
    - ใช้ค้นหาพารามิเตอร์ที่เหมาะสมสำหรับโมเดลตามค่าของพารามิเตอร์ที่กำหนดใน parameter grid
    - Parameter grid เป็นตัวแปรที่ประเภท dictionary เก็บค่า parameter เป็น key เก็บ list ค่าพารามิเตอร์ เป็น value ผู้ใช้จำ เป็นจะต้องมีการกำหนดค่าของพารามิเตอร์ที่สนใจเป็น list โดยพารามิเตอร์จะถูกเพิ่มประสิทธิภาพด้วยการทำ cross-validated grid-search เพื่อลดความจำเพาะต่อชุดข้อมูลที่ใช้ฝึกโมเดล 
 
 <hr>

ดังนั้นจึงเลือกอัลกอริทึม 3 แบบ คือ
    
1. **Logistic Regression** เป็น classifier algorithm เป็นเทคนิคการวิเคราะห์สถิติเชิงคุณภาพ นิยมใช้มากในการวิจัยทางด้านการแพทย์และสาธารณสุข [(4)](http://classroom.takasila.org/classroom/dataupload/takasila/project/29file/Logistic/LogisticSLT.pdf) เป็นเทคนิคการวิเคราะห์ความสัมพันธ์ของตัวแปรที่มี
เป้าหมายการวิเคราะห์คือ ทำนายหรือคาดการณ์โอกาสของการเกิดขึ้น และไม่เกิดขึ้นที่เป็นไปได้ของข้อมูลที่สนใจ [(5)](http://rdi.rmutsv.ac.th/rmutsvrj/download/year4-issue1-2555/p1.pdf)
2. **Random Forest** เป็น Ensemble model ประเภทหนึ่งที่มีพื้นฐานมาจากต้นไม้ตัดสินใจ (Decision tree) ซึ่งเป็นแบบจำลองที่อ้างอิงตามกฎ (Rule-based) ที่จะสร้างกฎ If-else condition โดยจำลองว่าถ้าเกิดเหตุการณ์ A แล้วผลลัพธ์จะเป็นอย่างไร และหากไม่เกิดเหตุการณ์ A จะได้ผลลัพธ์อย่างไร
3. **eXtreme Gradient Boosting (XGBoost)** แบบจำลองที่ถูกพัฒนาขึ้นมาต่อจาก Gradient boosting เพื่อเพิ่มความแม่นยำและความยืดหยุ่นให้กับแบบจำลอง โดยใช้หลักการของ Ensemble Learning Method โดยพัฒนาขึ้นเพื่อให้ทำงานได้เร็วยิ่งขึ้นกว่าเดิมในการค้นหาตัวแปรที่จะส่งผลต่อแบบจำลองมากที่สุดแทนการใช้ทุก ๆ ตัวแปรแบบ gradient boosting ดั้งเดิม ในการ Boosting เพื่อสร้างตัวเรียนรู้หลายๆตัว (Multiple Learner) [(6)](http://ir-ithesis.swu.ac.th/dspace/bitstream/123456789/610/1/gs611130429.pdf) หรือเรียกได้ว่าเป็นการรวม Weak Leamners หลาย ๆ ตัวมาทำงานเป็นช่ต่อเข้าด้วยกัน ซึ่ง Learner ที่สร้างขึ้นใหม่แต่ละรุ่นนั้นจะทำการแก้ไขข้อบกพร่องในการทำงานของ Learner รุ่นก่อนหน้าเพื่อลด Error พอฝึกแบบจำลองเสร็จแล้ว Learner ทุกตัวจะพยากรณ์ร่วมกัน [(7)](https://guopai.github.io/ml-blog11.html)

## 📁Dataset
ข้อมูลที่ใช้ในการวิเคราะห์ ประกอบด้วย ดังนี้ Cardiovascular Disease Dataset และ Synthetic Dataset

**1. Cardiovascular Disease Dataset**

เป็นข้อมูลเกี่ยวกับโรดหัวใจและหลอดเลือดของคนไข้ทั้ง 70,000 คน โดยมีผู้ป่วยเป็นโรคหัวใจและหลอดเลือด 34,979 คน และผู้ป่วยที่ไม่เป็นโรคหัวใจและหลอดเลือด 35,021
คน สามารถเข้าถึงได้โดย https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset


<p align="center">
<img src="https://github.com/mill-ornrakorn/Cardiovascular-Disease-Prediction-Project/blob/main/pic/3.jpg?raw=true" alt= "cardiovascular-disease-dataset" height="150">
</p>

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



<details>
<summary><b><h3>Exploratory Data Analysis (EDA) ใน Cardiovascular Disease Dataset</b></summary>

**1. ตรวจสอบข้อมูล**

จากการตรวจสอบข้อมูล พบว่า มี 70,000 datapoints และประกอบด้วย 12 Columns โดย
เป็น numerical data ทั้งหมด ซึง่ มี 12 integers และ 1 float

**2. ตรวจสอบ null ของข้อมูล**

จากการตรวจสอบ null ในข้อมูล พบว่า ในข้อมูลไม่มี Null

**3. Descriptive statistics**




จากการตรวจสอบ Descriptive statistics พบว่า มีความผิดปกติตรงค่า Min และ ค่า Max ใน
Column ดังนี้
- height: ส่วนสูงทีน่ ้อยทีส่ ุดคือ 55 cm และมากทีส่ ุดคือ 250 cm
- weight: น้ำ หนักทีน่ ้อยทีส่ ุดคือ 10 kg และมากทีส่ ุดคือ 200 kg
- ap_hi: ความดันช่วงหัวใจบีบตัวทีน่ ้อยทีส่ ุดคือ -150 mmHg และมากทีส่ ุดคือ 16,020 mmHg
ซึง่ ค่าความดันช่วงหัวใจบีบตัวจะติดลบไม่ได้ และไม่ควรน้อยกว่า 80 mmHg และมากกว่า 180
mmHg เพราะจะกลายเป็น emergency case
- ap_lo: ความดันช่วงหัวใจคลายตัวทีน่ ้อยทีส่ ุดคือ -70 mmHg และมากทีส่ ุดคือ 11,000 ซึง่ ค่า
ความดันช่วงหัวใจคลายตัวจะติดลบไม่ได้ และไม่ควรน้อยกว่า 60 mmHg และมากกว่า 110
mmHg เพราะจะกลายเป็น emergency case

ดังนั้นเพื่อจัดการกับข้อมูลทีม่ ีความผิดปกติดังกล่าว จึงต้องทำ Preparing Data ในขั้นตอนต่อไป


**4. สรุปการกระจายตัวของข้อมูล และสัดส่วนของข้อมูลแต่ละ Columns ในข้อมูล**
- age


- gender

จากการแสดงสัดส่วนของข้อมูล gender Column พบว่า มีจำนวนผู้ป่วยเพศหญิง(1) มากกว่าจำนวนผู้ป่วยเพศชาย(2)

- height

จาก box plot ของ height Column พบ Outliers จำนวนมาก จึงต้องทำ Data Preparation ในขั้นตอนต่อไป

- weight

จาก box plot ของ weight Column พบ Outliers จำนวนมาก จึงต้องทำ Data Preparation ในขั้นตอนต่อไป

- ap_hi

จาก box plot ของ ap_hi Column พบ Outliers จำนวนมาก จึงต้องทำ Data Preparation ในขั้นตอนต่อไป

- ap_lo

จาก box plot ของ ap_hi Column พบ Outliers จำนวนมาก จึงต้องทำ Data Preparation ในขั้นตอนต่อไป

- cholesterol

จากการแสดงสัดส่วนของข้อมูล cholesterol Column พบว่า มีจำนวนผู้ป่วยทีมีระดับ cholesterol อยู่ในปกติ(1) มากทีสุด ต่อมามีจำนวนผู้ป่วยทีมีระดับ cholesterol อยู่ในผิดปกติ(2) และจำนวนผู้ป่วยทีมีระดับ cholesterol อยู่ในผิดปกติมาก(3) รองลงมา ตามลำดับ

- gluc 

จากการแสดงสัดส่วนของข้อมูล gluc Column พบว่า มีจำนวนผู้ป่วยที่มีระดับน้ำตาลในเลือดอยู่ในปกติ(1) มากที่สุด ต่อมามีจำนวนผู้ป่วยที่มีระดับน้ำตาลในเลือดอยู่ในผิดปกติมาก(3) และจำนวนผู้ป่วยที่มีระดับน้ำตาลในเลือดอยู่ในผิดปกติ(2) รองลงมา ตามลำดับ

- smoke

จากการแสดงสัดส่วนของข้อมูล smoke Column พบว่า มีจำนวนผู้ไม่สูบบุรี่(0) มากกว่าจำนวนผู้ป่วยสูบบุหรี่(1)

- alco

จากการแสดงสัดส่วนของข้อมูล alco Column พบว่า มีจำนวนผู้ป่วยไม่ดื่มแอลกอฮอล์(0)มากกว่า จำนวนผู้ป่วยดื่มแอลกอฮอล์(1)

- active

จากการแสดงสัดส่วนของข้อมูล active Column พบว่า มีจำนวนผู้ป่วยออกกำลังกาย(1)มากกว่า จำนวนผู้ป่วยไม่ออกกำลังกาย(0)

- cardio

จากการแสดงสัดส่วนของข้อมูล cardio Column พบว่า มีจำนวนผู้ป่วยที่ไม่ป่วยเป็นโรคหลอดเลือดหัวใจ(0) และจำนวนผู้ป่วยที่ป่วยเป็นโรคหลอดเลือดหัวใจ(1) ใกล้เคียงกัน

</details>

<details>
<summary><b><h3>Data Preparation ใน
Cardiovascular Disease Dataset</b></summary>

**1. การจัดการข้อมูลที่มีความผิดปกติใน ap_hi Column หรือ ความดันช่วงหัวใจบีบตัว**

**2. การจัดการข้อมูลที่มีความผิดปกติใน ap_lo Column หรือ ความดันช่วงหัวใจคลายตัว**

**3. เพิ่ม BMI Column และจัดการข้อมูล BMI ที่มีความผิดปกติ**

**4. การเปลี่ยนแปลงข้อมูลใน gender, cholesterol, gluc Column**

**5. การเปลี่ยนแปลงหน่วยของข้อมูลใน age Column** 

</details>


### สรุป Cardiovascular Disease Dataset หลังจากทำ Data Preparation




จะเห็นว่าข้อมูลที่ได้ไม่มีความผิดปกติแล้ว จากการกระจายของ cardio Column หลังจากการทำ Data Preparation แล้ว พบว่า สัดส่วนของข้อมูลใน cardio Column มีค่าใกล้เคียงกัน ดังนั้นจึงสามารถใช้ ค่าความถูกต้อง (Accuracy) ในการประเมินแบบจำลองในขั้นตอนต่อ ๆ ไปได้

<!-- **📍note that:** รายละเอียดการทำ Exploratory Data Analysis (EDA) และ Data Preparation สามารถดูได้เพิ่มได้ใน
[รายงาน](https://github.com/mill-ornrakorn/Cardiovascular-Disease-Prediction-Project/blob/main/%E0%B8%AD%E0%B9%8B%E0%B8%AD%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1_CPE378_%2BFinal%2BProject_%E0%B8%AD%E0%B9%8B%E0%B8%AD%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1_%E0%B8%A3%E0%B8%B2%E0%B8%A2%E0%B8%87%E0%B8%B2%E0%B8%99.pdf) 
หรือ[สไลด์](https://github.com/mill-ornrakorn/Cardiovascular-Disease-Prediction-Project/blob/main/%E0%B8%AD%E0%B9%8B%E0%B8%AD%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1_CPE378_%2BFinal%2BProject_%E0%B8%AD%E0%B9%8B%E0%B8%AD%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1_ppt.pdf) นะคะ

-->
<hr>

**2. Synthetic Dataset**
![SyntheticDataset](https://github.com/mill-ornrakorn/Cardiovascular-Disease-Prediction-Project/blob/main/pic/4.jpg?raw=true)

### 📝ขั้นตอนการออกแบบการวิเคราะห์
![algorithm](https://github.com/mill-ornrakorn/Cardiovascular-Disease-Prediction-Project/blob/main/pic/1.jpg?raw=true)


### 📋สรุปผลการวิเคราะห์
![result](https://github.com/mill-ornrakorn/Cardiovascular-Disease-Prediction-Project/blob/main/pic/2.jpg?raw=true)


## References 📖
1. โรคหัวใจและหลอดเลือด [อินเตอร์เน็ต]. [เข้าถึงเมื่อ 14 พ.ค. 2565]. เข้าถึงได้จาก:
https://ccpe.pharmacycouncil.org/index.php?option=seminar_detail&subpage=seminar_detail&id=1623

2. รอบรู้เรื่องโรคและภัยสุขภาพ : สคร.6 ชลบุรี ชวนปกป้องหัวใจ ในวันหัวใจโลก [อินเตอร์เน็ต]. 2563
[เข้าถึงเมื่อ 14 พ.ค. 2565]. เข้าถึงได้จาก:
https://ddc.moph.go.th/odpc6/news.php?news=14902&deptcode=odpc6&news_views=265

3. Scikit-learn [อินเตอร์เน็ต]. [เข้าถึงเมื่อ 14 พ.ค. 2565]. เข้าถึงได้จาก:
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html

4. การวิเคราะห์ข้อมูลการวิจัยทางวิทยาศาสตร์สุขภาพโดยใช้ การถดถอยลอจีสติก [อินเตอร์เน็ต]. [เข้าถึงเมื่อ 14 พ.ค. 2565]. เข้าถึงได้จาก: http://classroom.takasila.org/classroom/dataupload/takasila/project/29file/Logistic/LogisticSLT.pdf

5. หลักการและการใช้การวิเคราะห์การถดถอยโลจิสติคสำ หรับการวิจัย [อินเตอร์เน็ต]. [เข้าถึงเมื่อ 14 พ.ค. 2565]. เข้าถึงได้จาก: http://rdi.rmutsv.ac.th/rmutsvrj/download/year4-issue1-2555/p1.pdf

6.การใช้เทคโนโลยีการเรียนรู้ของเครื่อง เพื่อทำนายผลการเรียนของนักเรียน [อินเตอร์เน็ต]. [เข้าถึง
เมื่อ 14 พ.ค. 2565]. เข้าถึงได้จาก: http://ir-ithesis.swu.ac.th/dspace/bitstream/123456789/610/1/gs611130429.pdf

7. Boosting [อินเตอร์เน็ต]. [เข้าถึงเมื่อ 14 พ.ค. 2565]. เข้าถึงได้จาก: https://guopai.github.io/ml-blog11.html