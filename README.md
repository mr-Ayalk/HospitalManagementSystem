**This Project is Under Development so the Full code is under Private visibility this is just a demo**


## 🌐 Live Demo

🔗 **Demo URL**: ([https://your-deployment.vercel.app](https://healthcaremanagement-dow4.vercel.app))  
🔐 Use Clerk dev accounts or create a new user to explore the features.

---



# 🏥 Shalom Health Care Center - Hospital Management System

Welcome to the **Shalom Health Care Center Management System** — a robust, modern full-stack web application tailored to meet the daily operational needs of hospitals and clinics. This system is thoughtfully crafted using **Next.js App Router**, **TypeScript**, **PostgreSQL (via Prisma ORM)**, and **Clerk authentication**, styled beautifully with **Tailwind CSS** and **Shadcn UI** components.

---

## 🚀 Features at a Glance

✅ **Role-Based Dashboards**  
Separate dashboards for **Admin**, **Doctor**, and **Patient**, showing relevant statistics and quick actions.

✅ **Secure Authentication**  
Implemented with **Clerk**, providing seamless sign-in/sign-up experiences with layout customization.

✅ **Patient Management**  
Full patient lifecycle support — registration, profile management, medical history, appointments, billing, and emergency contact tracking.

✅ **Appointment Handling**  
Doctors and patients can view, manage, and analyze appointments — with filtering, statistics, and visualizations.

✅ **Medical Records**  
Robust recordkeeping for diagnoses, prescriptions, lab tests, and vitals — all integrated with appointments.

✅ **Billing and Payments**  
Detailed billing interface with discount, payable, paid, and status tracking — tied directly to appointments.

✅ **Staff and Doctor Profiles**  
View, manage, and track doctors and other hospital staff with detailed statistics and performance indicators.

✅ **Notifications System**  
Receive system-generated alerts or messages from staff with real-time reply capability.

✅ **Visual Analytics**  
Interactive charts for appointments and consultations, giving instant insight into hospital activity.

---

## 🧱 Tech Stack

| Layer           | Technology                          |
|----------------|--------------------------------------|
| Frontend        | Next.js 14 (App Router), React       |
| Styling         | Tailwind CSS, Shadcn UI              |
| Backend         | Node.js (API routes), Prisma ORM     |
| Database        | PostgreSQL                           |
| Auth            | Clerk (authentication & user roles) |
| Data Fetching   | Server Actions + Async Functions     |
| Deployment      | Vercel / Railway / Custom            |

---


<p align="center">
<img width="1355" height="642" alt="image" src="https://github.com/user-attachments/assets/f3695d8e-1731-417b-8fda-3c3c8952d130" />

<img width="1348" height="643" alt="image" src="https://github.com/user-attachments/assets/127be5fc-f8eb-4d42-aca5-ab0dabe108f9" />
<img width="1358" height="637" alt="image" src="https://github.com/user-attachments/assets/6efdef9b-879f-429f-a140-466010cfbeb8" />
<img width="1366" height="642" alt="image" src="https://github.com/user-attachments/assets/31068166-284a-415f-98bb-a560c6802109" />

</p>

---

## 🛠 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/mr-Ayalk/hospital-management-system.git
   cd hospital-management-system

2.⚙️ Local Development
# 1. Install dependencies
npm install

# 2. Setup Prisma DB
npx prisma generate
npx prisma migrate dev --name init

# 3. Run dev server
npm run dev



---

## 📦 Environment Variables

Create a `.env.local` file and include the following:

```env
DATABASE_URL=postgresql://username:password@localhost:5432/hospital_db
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key
CLERK_SECRET_KEY=your-clerk-secret-key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard


---
👨‍💻 Author
Ayalkbet Teketel
GitHub: @mr-Ayalk
