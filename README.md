# 📱 Social Media App (Project Y)

แอปพลิเคชันโซเชียลมีเดียที่พัฒนาด้วย **Flutter** และเชื่อมต่อกับ **Firebase** ผู้ใช้งานสามารถโพสต์ข้อความ กดถูกใจ และแสดงความคิดเห็นได้แบบ **Real-time** เหมาะสำหรับใช้เป็นโปรเจกต์การเรียนรู้หรือโปรเจกต์ตัวอย่างด้าน Mobile Application Development

---

## ✨ ฟีเจอร์หลัก (Features)

* 🔐 **User Authentication**
  ระบบสมัครสมาชิก / เข้าสู่ระบบ / ออกจากระบบ ด้วย Firebase Authentication

* 📰 **Real-time Feed**
  แสดงโพสต์ทั้งหมดของผู้ใช้แบบเรียลไทม์ เรียงตามเวลา

* ✍️ **Create Post**
  ผู้ใช้สามารถสร้างและเผยแพร่โพสต์ข้อความได้

* ❤️ **Like System**
  กดถูกใจ (Like) และยกเลิกถูกใจ (Unlike) โพสต์

* 💬 **Comment System**
  แสดงความคิดเห็นใต้โพสต์ได้

* 🛠 **Post Management**

  * ✏️ แก้ไขโพสต์ (เฉพาะเจ้าของโพสต์)
  * 🗑 ลบโพสต์ (เฉพาะเจ้าของโพสต์) พร้อมลบคอมเมนต์ที่เกี่ยวข้องอัตโนมัติ

* 👤 **User Profile**
  แสดงข้อมูลโปรไฟล์ของผู้ใช้งาน

---

## 🛠 เทคโนโลยีที่ใช้ (Tech Stack)

* **Frontend:** Flutter (Dart)
* **Backend:** Firebase

  * Firebase Authentication
  * Cloud Firestore (Real-time NoSQL Database)
* **State Management & Routing:** GetX
* **Utilities:** Intl (จัดรูปแบบวันที่และเวลา)

---

## 📂 โครงสร้างโปรเจกต์ (Project Structure)

```text
lib/
├── components/           # วิดเจ็ตที่ใช้ซ้ำ (UI Components)
│   ├── Y_post.dart       # การแสดงผลโพสต์ (Like / Comment / Edit / Delete)
│   ├── comment_btn.dart  # ปุ่มคอมเมนต์
│   ├── delete_btn.dart   # ปุ่มลบโพสต์
│   ├── edit_btn.dart     # ปุ่มแก้ไขโพสต์
│   ├── like_button.dart  # ปุ่มไลก์
│   ├── text_field.dart   # กล่องข้อความ input
│   └── drawer.dart       # เมนูแถบข้าง
├── helper/               # ฟังก์ชันช่วยเหลือ (Helper Methods)
├── pages/                # หน้าจอหลัก (Login, Signup, Profile)
├── homepage.dart         # หน้า Feed หลัก
├── wrapper.dart          # จัดการสถานะการล็อกอิน (Auth State)
└── main.dart              # Entry Point ของแอป
```

---

## 🚀 การติดตั้งและเริ่มต้นใช้งาน (Getting Started)

### 1️⃣ Clone โปรเจกต์

```bash
git clone https://github.com/your-username/social-media-app.git
cd social-media-app
```

### 2️⃣ ติดตั้ง Dependencies

```bash
flutter pub get
```

### 3️⃣ ตั้งค่า Firebase (สำคัญ)

1. สร้างโปรเจกต์ใหม่ที่ **Firebase Console**
2. เปิดใช้งาน **Authentication (Email/Password)**
3. เปิดใช้งาน **Cloud Firestore**
4. เพิ่มแอปใน Firebase Console

* **Android:** วางไฟล์ `google-services.json` ที่ `android/app/`
* **iOS:** วางไฟล์ `GoogleService-Info.plist` ที่ `ios/Runner/`

### 4️⃣ รันแอปพลิเคชัน

```bash
flutter run
```

---

## 👨‍💻 ผู้พัฒนา (Developer)

Developed by **Clumsyz**

---

⭐ หากคุณชอบโปรเจกต์นี้ อย่าลืมกด Star ให้ด้วยนะครับ!
