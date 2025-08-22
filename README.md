# 🩺 CarePulse – Patient Management System (Next.js, Appwrite, Twilio)

**CarePulse** is a modern healthcare management system designed to optimize patient check-ups and streamline appointment scheduling with real-time SMS notifications.  
Built with Next.js, TypeScript, TailwindCSS, Appwrite, and Twilio, this project demonstrates a real-world solution ready for production and portfolio use.

---

## 🚀 Features

- **User Authentication & Registration**
  - Patient sign-up with phone number verification (OTP)
  - Personal info, medical history, and ID upload
  - Consent to privacy terms

- **Appointment Scheduling**
  - Book appointments with preferred doctor, date, and reason
  - Confirmation screen after successful booking
  - Real-time SMS notifications for confirmations

- **Admin Dashboard**
  - Secure access via Pass Key
  - Overview of appointment statuses (scheduled, pending, canceled)
  - Responsive, paginated data table of all appointments
  - Admin actions: confirm, schedule, or cancel appointments
  - SMS notifications to patients on status changes

- **Patient Portal**
  - View and manage personal info and medical history
  - Book new appointments and view appointment history

- **Reusable & Advanced Form Components**
  - Built with react-hook-form and Zod for validation
  - Custom components: date pickers, phone input, OTP verification, file uploader, select, radio group, textarea

- **Real-Time SMS Notifications**
  - Integrated with Twilio via Appwrite Messaging
  - Dynamic messages for appointment confirmations and cancellations

- **Monitoring & Analytics**
  - Sentry integration for error tracking, performance monitoring, and user session replays
  - Custom metrics and conversion funnels

- **Mobile-First & Responsive UI**
  - Built with TailwindCSS and shadcn/ui components
  - Fully responsive layouts and interactive charts

---

## 🛠️ Tech Stack

- **Frontend:** Next.js (App Router, SSR, server actions), TypeScript, TailwindCSS, shadcn/ui
- **Backend:** Appwrite (open-source BaaS), Appwrite Messaging (SMS), Appwrite Storage
- **Notifications:** Twilio (SMS provider)
- **Monitoring:** Sentry (error tracking, performance, replays)
- **Forms:** react-hook-form, Zod, react-datepicker, react-phone-number-input, react-dropzone
- **Other:** Figma (UI design), clsx, tailwind-merge, next-themes, next/image, next/link

---

## ⚡ Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-user/carepulse.git
   cd carepulse
Install dependencies:

Bash

npm install
Configure environment variables:
Create a .env.local file with:

PROJECT_ID, API_KEY, DATABASE_ID, PATIENT_COLLECTION_ID, DOCTOR_COLLECTION_ID, APPOINTMENT_COLLECTION_ID
NEXT_PUBLIC_BUCKET_ID, NEXT_PUBLIC_ENDPOINT, NEXT_PUBLIC_ADMIN_PASSKEY
Twilio credentials (via Appwrite Messaging)
Run the development server:

Bash

npm run dev
Access the app:
Open http://localhost:3000 in your browser.

🧩 Application Structure
/ – Welcome page, phone login, admin access
/patients/[userId]/register – Patient registration and info
/patients/[userId]/new-appointment – Book new appointment
/patients/[userId]/new-appointment/success – Appointment confirmation
/admin – Admin dashboard (Pass Key protected)
🖼️ Screenshots
Welcome/Login	Patient Registration	Admin Dashboard
Welcome	Register	Admin
💡 Best Practices & Highlights
Modular, reusable components for rapid development
Real-time SMS notifications for critical actions
Secure, privacy-focused data handling (no third-party cookies)
Sentry for full-stack monitoring and performance
Mobile-first, accessible UI
Open-source backend (Appwrite) and free deployment (Vercel)

Thank you for visiting! If you like this project, please star the repo and follow me on GitHub.
Happy coding! 🚀


https://github.com/user-attachments/assets/e1952faf-23d1-4363-83c4-b7cc75769ba2

<img width="1781" height="964" alt="appointment" src="https://github.com/user-attachments/assets/e30a3c7d-079c-42a6-8969-2c8a445075fa" />
<img width="1838" height="911" alt="data2" src="https://github.com/user-attachments/assets/a93edfe2-19ee-40b6-b3f8-4450f2b8fb05" />
<img width="1839" height="920" alt="dashboard" src="https://github.com/user-attachments/assets/a5745f84-abcf-4e66-b648-0e139ba60d85" />
