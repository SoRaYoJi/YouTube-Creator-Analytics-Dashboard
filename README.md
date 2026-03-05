# YouTube Creator Analytics Dashboard 📊

An interactive data visualization dashboard designed to process YouTube analytics from CSV files and extract actionable creator insights.
*(แดชบอร์ดแบบ Interactive สำหรับแสดงผลและวิเคราะห์ข้อมูล YouTube จากไฟล์ CSV เพื่อดึงข้อมูลเชิงลึก (Insights) ที่เป็นประโยชน์สำหรับครีเอเตอร์)*

---

## 📝 Project Overview (ภาพรวมโปรเจกต์)
This project takes raw YouTube Creator data (CSV format) and transforms it into an easy-to-read, interactive dashboard. It allows users to upload local datasets and instantly visualize key metrics such as views, likes, regional distribution, and sentiment analysis without uploading data to an external server (100% secure local processing).

โปรเจกต์นี้เป็นการนำข้อมูลดิบของ YouTube Creator (ในรูปแบบไฟล์ CSV) มาแปลงเป็นแดชบอร์ดที่อ่านง่ายและโต้ตอบได้ ผู้ใช้สามารถอัปโหลดชุดข้อมูลที่มีในเครื่องและดูภาพรวมของสถิติสำคัญได้ทันที เช่น ยอดเข้าชม (Views), ยอดไลก์ (Likes), สัดส่วนตามภูมิภาค และการวิเคราะห์ความรู้สึก (Sentiment Analysis) โดยไม่ต้องอัปโหลดข้อมูลขึ้นเซิร์ฟเวอร์ภายนอก (ประมวลผลในเครื่อง 100% ปลอดภัยแน่นอน)

---

## ✨ Features (ฟีเจอร์หลัก)
* **Local CSV Upload:** Securely process large datasets (e.g., `global_youtube_creator_data_large.csv`) directly on your machine.
  *(อัปโหลดและประมวลผลไฟล์ข้อมูลขนาดใหญ่ได้อย่างปลอดภัยบนเครื่องของคุณเอง)*
* **Dynamic Filtering:** Filter data by Category, Region, Language, and Monetization status.
  *(กรองข้อมูลตามหมวดหมู่, ภูมิภาค, ภาษา และสถานะการสร้างรายได้)*
* **Key Metrics Summary:** Instantly view Total Videos, Views, Likes, and Average Sentiment.
  *(สรุปตัวเลขสำคัญให้เห็นทันที ทั้งจำนวนวิดีโอทั้งหมด, ยอดเข้าชม, ยอดไลก์ และคะแนนความรู้สึกเฉลี่ย)*
* **Interactive Visualizations (กราฟแสดงผลแบบโต้ตอบได้):** * Views by Category (Bar Chart) - *ยอดเข้าชมแยกตามหมวดหมู่*
  * Videos by Region (Pie Chart) - *สัดส่วนวิดีโอแยกตามภูมิภาค*
  * Sentiment by Language (Horizontal Bar Chart) - *คะแนนความรู้สึกเฉลี่ยแยกตามภาษา*
  * Views vs. Likes Correlation (Scatter Plot) - *ความสัมพันธ์ระหว่างยอดเข้าชมกับการกดไลก์*

---

## 📸 Dashboard Walkthrough (ตัวอย่างการใช้งาน)

### 1. Initial Upload Screen (หน้าต่างอัปโหลดเริ่มต้น)
Start by uploading your local CSV file. The application is offline-ready and processes data securely on your device.
*(เริ่มต้นด้วยการอัปโหลดไฟล์ CSV ในเครื่องของคุณ แอปพลิเคชันนี้ทำงานแบบออฟไลน์และประมวลผลข้อมูลในเครื่องอย่างปลอดภัย)*
![Upload Screen](images\Screenshot 2026-03-05 151157.png)

### 2. File Selection (การเลือกไฟล์)
Select your dataset (e.g., the 79MB `global_youtube_creator_data_large.csv`).
*(เลือกชุดข้อมูลของคุณ เช่น ไฟล์ `global_youtube_creator_data_large.csv` ขนาด 79MB)*
![File Selection](images\Screenshot 202026-03-05 20151253.png)

### 3. Data Filtering & Summary (การกรองข้อมูลและสรุปผล)
Use the dropdown menus to filter the analytics by Category, Region, Language, or Ads status to narrow down your insights.
*(ใช้เมนูดรอปดาวน์เพื่อกรองข้อมูลตามหมวดหมู่, ภูมิภาค, ภาษา หรือสถานะโฆษณา เพื่อเจาะลึกข้อมูลที่คุณสนใจ)*
![Dashboard Filters](images\Screenshot 202026-03-05 20151310.png)

### 4. Interactive Visualizations (ส่วนแสดงผลกราฟ)
Explore the generated charts to find actionable insights about content performance, regional popularity, and audience sentiment.
*(สำรวจกราฟที่สร้างขึ้นเพื่อหา Insight เกี่ยวกับประสิทธิภาพของคอนเทนต์, ความนิยมในแต่ละภูมิภาค และความรู้สึกของผู้ชม)*
![Full Dashboard](images\Screenshot 202026-03-05 20151318.png)

---

## 🛠️ Tech Stack (เทคโนโลยีที่ใช้)
* **Language/Environment:** Web-based interface (HTML/CSS/JS) / Python
* **Data Handling:** Capable of processing large CSV datasets efficiently. *(รองรับการประมวลผลไฟล์ CSV ขนาดใหญ่ได้อย่างมีประสิทธิภาพ)*
* **UI/UX:** Clean, modern, and responsive dashboard design. *(ออกแบบแดชบอร์ดให้ดูสะอาดตา ทันสมัย และรองรับการแสดงผลทุกขนาดหน้าจอ)*

---

## 🚀 How to Run Locally (วิธีการรันโปรเจกต์ในเครื่อง)

1. **Clone the repository (โคลน Repository):**
   ```bash
   git clone [https://github.com/SoRaYoJi/YouTube-Creator-Analytics-Dashboard.git](https://github.com/SoRaYoJi/YouTube-Creator-Analytics-Dashboard.git)
   cd YouTube-Creator-Analytics-Dashboard
