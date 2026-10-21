# KPCAA Waterproofing & Leakage Solutions Platform

A full-stack web application designed for Karnal Pest Control Associate Aligarh (KPCAA) Waterproofing Services. The platform enables clients to request service estimates, report leakages with image attachments, and track inquiries, while providing admins with a secure dashboard to manage service leads.

## 🚀 Key Features

- **Lead & Inquiry Management:** Integrated SMTP email notifications via Nodemailer for incoming customer leads.
- **Leakage Photo Uploads:** Integrated Cloudinary cloud storage to handle customer-uploaded site leak photos.
- **Admin Dashboard & Auth:** Secure JWT-based administrative access and user authentication powered by `bcryptjs` and NextAuth.
- **Dynamic & Interactive UI:** Smooth animations using Framer Motion alongside clean styling with Tailwind CSS.
- **Database Integration:** MongoDB database managed seamlessly through Mongoose ORM.

## 🛠️ Tech Stack

- **Framework:** Next.js (App Router), React
- **Styling:** Tailwind CSS, Framer Motion, Lucide Icons, React Icons
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT (`jsonwebtoken`), `bcryptjs`, NextAuth
- **Cloud Storage:** Cloudinary
- **Email Delivery:** Nodemailer

## 💻 Getting Started

### 1. Clone the repository
```bash
git clone [https://github.com/YOUR_USERNAME/waterproofing-app.git](https://github.com/YOUR_USERNAME/waterproofing-app.git)
cd waterproofing-app
