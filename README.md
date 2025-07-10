# StaySphere 🏨

StaySphere is a full-stack hotel booking web application that allows users to search for hotels, view room availability, make bookings, and manage reservations. Hotel owners can register hotels, add rooms, and manage availability.


---

## ⚙️ Tech Stack

### Frontend
- React
- Tailwind CSS
- React Router
- Clerk (for authentication)
- Axios

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- Cloudinary (for image upload)
- Nodemailer (email confirmation)
- Clerk Webhooks

---

## ✨ Features

### 👤 User
- Sign up / Sign in via Clerk
- Search hotels by destination
- Book rooms with check-in & check-out dates
- View and manage bookings
- Recent city suggestions

### 🏨 Hotel Owner
- Register hotel
- Add and manage rooms
- Toggle room availability
- View hotel-specific bookings

### Admin (Future Scope)
- Dashboard analytics
- Manage listings and users

---

## 🔐 Environment Variables

> Create a `.env` file in the `/server` directory and add the following:

```env
MONGODB_URL=your_mongo_db_url
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLERK_WEBHOOK_SECRET=your_clerk_webhook_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

SENDER_EMAIL=your_sender_email
SMTP_USER=your_smtp_username
SMTP_PASS=your_smtp_password

```

🤝 Contributing
Contributions, issues and feature requests are welcome!
Feel free to check the issues page.

📄 License
This project is licensed under the MIT License.

👩‍💻 Developed By
N-Shreya-Sai

---

Let me know if you'd like to add badges, deployment links, or more advanced documentation (like Swagger, Postman API docs, etc.).
