# Domestic Violence Data Insights: Hackathon Achievement 🏆

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Visualization-Plotly-brightgreen.svg)](https://plotly.com/)

โปรเจกต์วิเคราะห์ข้อมูลชุด "ความรุนแรงในครอบครัว" (Domestic Violence) ซึ่งเป็นส่วนหนึ่งของการแข่งขัน Hackathon โดยมุ่งเน้นการทำ Data Storytelling เพื่อหาปัจจัยเสี่ยงและแนวทางการป้องกันทางสังคม

## 📌 Overview & Context
- **Dataset:** [Thackle - Domestic Violence Dataset](https://www.thackle.or.th/en/dataset)
- **Objective:** วิเคราะห์ความสัมพันธ์ระหว่างปัจจัยด้านประชากรศาสตร์ (Demographics) กับปัจจัยกระตุ้น (Risk Factors) เพื่อระบุ "สัญญาณเตือนภัยล่วงหน้า"
- **Hackathon Status:** ผลงานจากการแข่งขัน [ชื่อรายการถ้ามี] โดยได้รับคะแนนในระดับ [ระบุผลลัพธ์ที่ภาคภูมิใจ]

## 🛠️ Data Engineering & Cleaning (Professional Approach)
ความโดดเด่นของโปรเจกต์นี้อยู่ที่การทำ **Data Cleaning Log** อย่างเป็นระบบ:
1. **Deduplication:** ตรวจพบและกำจัดข้อมูลซ้ำซ้อน (Duplicate Cases) เพื่อความแม่นยำในการวิเคราะห์
2. **Handling Missing Values:** จัดการข้อมูลที่ไม่ระบุเพศ/อายุ โดยใช้เกณฑ์ทางสถิติเพื่อไม่ให้บิดเบือน Pattern หลัก
3. **Data Transformation:** ปรับปรุงโครงสร้างข้อมูลจากไฟล์ดิบ (JSON/CSV) ให้พร้อมสำหรับการทำ Interactive Visualization

## 📊 Key Insights & Analysis
จากการวิเคราะห์เชิงลึก พบประเด็นสำคัญดังนี้:
- **High-Risk Profiles:** ผู้กระทำมักเป็นเพศชายช่วงอายุ 38–40 ปี ขณะที่ผู้ถูกกระทำส่วนใหญ่เป็นผู้หญิงและเด็ก (อายุเฉลี่ย 13 ปี)
- **Trigger Factors:** สุราและยาเสพติดเป็นปัจจัยกระตุ้นหลักที่ทำให้สถานการณ์ทวีความรุนแรง
- **Early Warning Signs:** ความเครียดจากปัญหาเศรษฐกิจรวมกับการใช้สารเสพติด เป็นจุดที่หน่วยงานควรเข้าแทรกแซง (Intervene) ทันที

## 🚀 How to Run
1. Clone repository นี้
2. ติดตั้ง library: `pip install pandas plotly seaborn matplotlib`
3. เปิดไฟล์ `.ipynb` ผ่าน Jupyter Notebook หรือ Google Colab

---
**Author:** Apirak Ketrueng (Tung)
**GitHub:** [https://github.com/Tung0000]
