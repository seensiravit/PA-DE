# PA-DE (Parkinson Disease Early Detection System)

Welcome to PA-DE, our mobile application designed for the 2024 NSC competition. Our mission is to provide an early detection system for Parkinson's disease using interactive minigames and detailed assessments.

## 🚀 What is this project about?

PA-DE is a mobile application that helps identify early signs of Parkinson's disease. By engaging in three unique minigames, users can monitor their symptoms and receive tailored guidance based on their results. Additionally, the app keeps a record of user's test history.

This repository is about the AI models. For the mobile application, please refer to our [mobile application repository](https://github.com/seensiravit/PA-DE)

## 🎮 List of minigame

Our app features three minigames, each designed to assess different aspects of motor control and coordination:

1. น้ำกลิ้งบนใบบอน
2. เขียนเสือให้วัวกลัว
3. เล่าสู่กันฟัง 

### น้ำกลิ้งบนใบบอน

Users balance a ball in the middle of the screen using their hands for a set amount of time. The ball's position is determined by the device's orientation, and the input is evaluated based on the frequency and amplitude of any shaking detected.

### เขียนเสือให้วัวกลัว 

Users draw three spirals on the screen with their finger. The drawing is first checked to ensure it resembles a spiral, and then evaluated based on the shaking of the strokes. This assessment is powered by our AI models.

### เล่าสู่กันฟัง 

Users answer 20 questions designed to assess their severity level of Parkinson's disease.

## 📊 Dataset

We use a variety of datasets for our spiral minigame AI model, including:

- [Kaggle](https://www.kaggle.com/datasets/kmader/parkinsons-drawings/data)
- [HandPD](https://wwwp.fc.unesp.br/~papa/pub/datasets/Handpd/)
- And a few others we gathered ourselves

The dataset after cleaning is uploaded [here](https://github.com/seensiravit/Parkinson-SpiralDrawing)

## 🔧 Tech Stack

- [Hugging-Space](https://huggingface.co/) Provides AI models and tools for natural language processing.
- [FastAPI](https://fastapi.tiangolo.com/) For efficient API deployment.
- [Flutter](https://flutter.dev/) For building the cross-platform mobile application.
- [Firebase](https://firebase.google.com/) Manages our database and authentication processes.

## 📥 Installation

Currently, PA-DE is available exclusively for Android, but we have plans to expand to other platforms in the near future!

For the offical version: download app-release.apk file from this repository

For the latest version: visit our [mobile application repository](https://github.com/seensiravit/PA-DE)

## 🙌 Contributors

- [seesawseen](https://github.com/seensiravit) for building the AI model
- [njoop](https://github.com/Phakbhumi) for building the mobile application
- And [Porsche](https://www.instagram.com/pxrsche.eeee) for his research on parkinson's disease.

## ⚙️ Software Usage

ข้อตกลงในการใช้ซอฟต์แวร์

ซอฟต์แวร์นี้เป็นผลงานที่พัฒนาขึ้นโดย นายสิรวิชญ์ กีรติพรานนท์, นายภาคภูมิ เกียรติวนิชวิไล, นายวชิระพงศ์ พงศ์วิสสุตรา จาก โรงเรียนเตรียมอุดมศึกษา ภายใต้การดูแลของ นางสาวชุตินันท์ พ่วงขาว ภายใต้โครงการ 26p23c0124 (ระบบตรวจประเมินอาการโรคพาร์กินสันเบื้องต้น) ซึ่งสนับสนุนโดย สำนักงานพัฒนาวิทยาศาสตร์และเทคโนโลยีแห่งชาติโดยมีวัตถุประสงค์เพื่อส่งเสริมให้นักเรียนและนักศึกษาได้เรียนรู้และฝึกทักษะในการพัฒนา ซอฟต์แวร์ลิขสิทธิ์ของซอฟต์แวร์นี้จึงเป็นของผู้พัฒนา ซึ่งผู้พัฒนาได้อนุญาตให้สำนักงานพัฒนาวิทยาศาสตร์และเทคโนโลยีแห่งชาติเผยแพร่ซอฟต์แวร์นี้ตาม “ต้นฉบับ” โดยไม่มีการแก้ไขดัดแปลงใด ๆ ทั้งสิ้น ให้แก่บุคคลทั่วไปได้ใช้เพื่อประโยชน์ส่วนบุคคลหรือประโยชน์ทางการศึกษาที่ไม่มีวัตถุประสงค์ในเชิงพาณิชย์โดยไม่คิดค่าตอบแทนการใช้ซอฟต์แวร์ดังน้ัน สำนักงานพัฒนาวิทยาศาสตร์และเทคโนโลยีแห่งชาติจึงไม่มีหน้าที่ในการดูแล บำรุงรักษา จัดการอบรมการใช้งาน หรือพัฒนาประสิทธิภาพซอฟต์แวร์ รวมทั้งไม่รับรองความถูกต้องหรือประสิทธิภาพการทำงานของซอฟต์แวร์ ตลอดจนไม่รับประกันความเสียหายต่าง ๆ อันเกิดจากการใช้ซอฟต์แวร์นี้ท้ังสิ้น
