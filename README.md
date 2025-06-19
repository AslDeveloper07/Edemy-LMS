<div align="center">
  
![favicon](https://github.com/user-attachments/assets/ba86af86-a98e-4842-9cc4-5871c5ef234b)

</div>

# Edemy LMS - A Modern Learning Management System

---

## 📌 Overview

**Edemy LMS** — bu zamonaviy, yengil va foydalanuvchi uchun qulay onlayn ta'lim platformasi. Ushbu tizim orqali foydalanuvchilar kurslarga yozilish, video darslarni ko‘rish, va o‘z bilim darajasini kuzatib borish imkoniyatiga ega.

---

## 🚀 Xususiyatlar

- Kurslarni qo‘shish, tahrirlash va o‘chirish
- YouTube videolarni dars sifatida qo‘shish
- Foydalanuvchi ro‘yxatdan o‘tishi / tizimga kirishi
- Kurs bo‘yicha o‘zlashtirishni kuzatish
- Kurslarni izlash va filtrlash
- Qorong‘i (Dark) rejim
- Yengil va tezkor platforma (Vite asosida)

---

## 🛠️ Ishlatilgan texnologiyalar

- **Frontend:** React.js, Vite, TailwindCSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** Clerk (yoki Firebase/Auth)
- **Deployment:** Vercel yoki Netlify

---

## ⚙️ Muhit sozlamalari (`.env` fayl)

Loyihani to‘g‘ri ishlatish uchun quyidagi ma’lumotlarni `.env` faylga yozing:

VITE_CLERK_PUBLISHABLE_KEY=pk_test_Zmx5aW5nLXJpbmd0YWlsLTE4LmNsZXJrLmFjY291bnRzLmRldiQ
VITE_CURRENCY=$


Terminalga quyidagilarni ketma-ket yozing:

```bash
# Git orqali loyihani yuklab olish
git clone https://github.com/AslDeveloper07/Edemy-LMS.git

# Loyiha papkasiga kirish
cd edemy-frontend

# Barcha kerakli kutubxonalarni o‘rnatish
npm install

# Dasturiy serverni ishga tushurish
npm run dev




## 📂 Project Structure

### **Frontend (`client/`)**
```
📦 client
 ├── 📂 src
 │   ├── 📂 assets
 │   ├── 📂 components
 │   │   ├── 📂 educator
 │   │   │   ├── Footer.jsx
 │   │   │   ├── Navbar.jsx
 │   │   │   ├── Sidebar.jsx
 │   │   ├── 📂 student
 │   │   │   ├── Logger.jsx
 │   ├── 📂 context
 │   │   ├── AppContext.jsx
 │   ├── 📂 pages
 │   │   ├── 📂 educator
 │   │   │   ├── AddCourse.jsx
 │   │   │   ├── Dashboard.jsx
 │   │   │   ├── Educator.jsx
 │   │   │   ├── MyCourses.jsx
 │   │   │   ├── StudentsEnrolled.jsx
 │   │   ├── 📂 student
 │   │   │   ├── CourseDetails.jsx
 │   │   │   ├── CoursesList.jsx
 │   │   │   ├── Home.jsx
 │   │   │   ├── MyEnrollMents.jsx
 │   │   │   ├── Player.jsx
 │   │   ├── App.jsx
 │   │   ├── index.css
 │   │   ├── main.jsx
 ├── 📜 .env
 ├── 📜 .gitignore
 ├── 📜 package.json
 ├── 📜 tailwind.config.js
 ├── 📜 vite.config.js

```



## 🌟 Features

✅ **User Authentication** (Signup, Login, Clerk Integration)  
✅ **Course Management** (Add, Edit, Delete, Enroll)  
✅ **Video Streaming** (Embedded YouTube player)  
✅ **Progress Tracking** (Course Completion)  
✅ **Educator Dashboard** (Monitor students)  
✅ **Secure Payments** (Stripe integration)  
✅ **Responsive Design** (Mobile-friendly UI)  

---

## 📸 Screenshots

| Page | Screenshot |
|------|-----------|
| **Home Page** | ![Home](https://github.com/user-attachments/assets/03cf6bd7-8c30-4817-ad49-4a8fe8000541) |
| **Course Page** | ![Course](https://github.com/user-attachments/assets/e42c2660-8271-42ae-b7e3-c5278b6a9cf1) |
| **My Enrollments** | ![Enrollments](https://github.com/user-attachments/assets/a88cf7c1-cab1-4106-a64d-d7cfd5d9d4b7) |
| **Player Page** | ![Player](https://github.com/user-attachments/assets/cdc8fb2a-6f44-416f-b4bd-2f35b7acfbbd) |
| **Educator Dashboard** | ![Dashboard](https://github.com/user-attachments/assets/6c3bec05-805e-4652-ac51-113fd870b267) |
| **Add Course** | ![Add Course](https://github.com/user-attachments/assets/ee846dba-7b14-4006-ae95-8ff76402ed8d) |
| **My Courses** | ![My Courses](https://github.com/user-attachments/assets/e9f1b602-fc46-4dd7-8833-f1d8b15f43a1) |
| **Enrolled Students** | ![Enrolled Students](https://github.com/user-attachments/assets/6d118429-4aa0-487e-ad6c-1f37af3f9968) |

![image](https://github.com/user-attachments/assets/6eb66c29-6a73-4f98-9c15-7625a903a109)
