# 🩸 BloodCare — Blood Donation Platform

**BloodCare** is a full-stack blood donation platform built with the **MERN stack** that connects blood donors with patients in need. The platform enables users to register as donors, create and manage donation requests, search for donors by location and blood group, donate funds via Stripe, and manage the entire system through role-based dashboards (Donor, Volunteer, Admin).

## 🔗 Live Site

**Live Link:** [https://bloodcare-11.netlify.app/](https://bloodcare-11.netlify.app/)

## 📁 Repositories

| Side | Repository |
|------|------------|
| Client | [Blood-Care-client](https://github.com/KhanIsrakAhmed/Blood-Care-client) |
| Server | [Blood-Care-server](https://github.com/KhanIsrakAhmed/Blood-Care-server) |

## 🔑 Demo Credentials (For Testing)

| Role | Email | Password |
|------|-------|----------|
| Admin | `israk.ahmed275@gmail.com` | `Admin321` |
| Volunteer | `israk.ahmed38@gmail.com` | `Volunteer321` |
| User | `uzumakiisrak@gmail.com` | `User321` |

## ✨ Key Features

### 🌐 Public Features
- User Registration & Login (Donor role by default)
- Search Donors by Blood Group, District, and Upazila
- View Public Pending Donation Requests
- View Donation Request Details (Login Required)
- Funding Page with Stripe Payment Integration

### 🩸 Donor Features
- Create Donation Requests
- View & Manage Own Donation Requests (Pending, In-progress, Done, Canceled)
- Update Profile (Name, Avatar, Blood Group, Address)
- Edit / Delete Own Donation Requests
- Dashboard with Recent 3 Requests

### 🤝 Volunteer Features
- View & Update Status of All Donation Requests
- View Platform Statistics (Total Users, Funding, Requests)

### 🛡️ Admin Features
- Manage All Users (Block / Unblock, Change Roles: Donor → Volunteer → Admin)
- Full Control Over All Donation Requests
- View Platform Statistics (Total Users, Total Funding, Total Requests)
- View & Manage All Funding Records

### ⚙️ Additional Features
- Role-based Access Control (RBAC)
- JWT Authentication (Protected Routes & APIs)
- Pagination & Filtering (Requests & Users)
- Responsive Dashboard with Sidebar Navigation
- Clean & Consistent UI/UX with Animations
- Secure Environment Variables for Firebase & MongoDB
- Image Upload via ImgBB API

## 🛠️ Tech Stack

### Frontend
- React 19 + Vite 7
- React Router v7
- Tailwind CSS 4 + DaisyUI 5
- Framer Motion (Animations)
- Recharts (Dashboard Charts)
- React Hot Toast (Notifications)
- React Icons + Lucide React
- React Hook Form
- React Helmet (SEO)
- Axios
- Stripe (Payment)
- Firebase (Authentication)

### Backend
- Node.js + Express.js
- MongoDB
- JWT Authentication
- Stripe Payment Integration
- CORS + Dotenv

### Deployment
- **Frontend:** Netlify
- **Backend:** Vercel

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/KhanIsrakAhmed/Blood-Care-client.git
cd Blood-Care-client

# Install dependencies
npm install
```

### Environment Variables

Create a `.env` file in the root directory:

```env
VITE_apiKey=your_firebase_api_key
VITE_authDomain=your_project.firebaseapp.com
VITE_projectId=your_project_id
VITE_storageBucket=your_project.appspot.com
VITE_messagingSenderId=your_sender_id
VITE_appId=your_app_id
VITE_measurementId=your_measurement_id
VITE_IMGBB_KEY=your_imgbb_api_key
```

### Run Development Server

```bash
npm run dev
```

The app will be available at `http://localhost:5173/`

### Build for Production

```bash
npm run build
```

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |

## 👤 Author

**Khan Israk Ahmed**
- GitHub: [@KhanIsrakAhmed](https://github.com/KhanIsrakAhmed)

## 📄 License

This project is open source and available for personal and educational use.
