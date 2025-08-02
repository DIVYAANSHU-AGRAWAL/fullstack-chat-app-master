# 💬 Full Stack Realtime Chat App

A full-featured real-time chat application built with the **MERN stack**, **Socket.io**, and **Zustand** for global state. This project includes user authentication, image uploads with Cloudinary, live online status, and more.


---

###  Features

-  **Authentication & Authorization** – Secure JWT-based auth with HTTP-only cookies.
-  **Realtime Chat** – Instant messaging powered by Socket.io.
-  **Online Users** – Live user presence tracking.
-  **Global State Management** – Zustand handles client-side app state.
-  **Cloudinary Integration** – Profile picture uploads stored on Cloudinary.
-  **Responsive UI** – Built with Tailwind CSS and Daisy UI.
-  **Clean Architecture** – Modular backend with controller-service-model separation.
-  **Error Handling** – Robust error responses on both client and server sides.
-  **Production Deployment** – Easily deployable using Vercel (frontend) and Render (backend).

---

###  Tech Stack

- **Frontend**: React + TailwindCSS + Zustand
- **Backend**: Node.js + Express + MongoDB
- **Realtime**: Socket.io
- **Image Uploads**: Cloudinary
- **Auth**: JWT in HTTP-only cookies

---

###  Getting Started

#### 1) Clone the Repository

```bash
git clone https://github.com/your-username/fullstack-chat-app.git
cd fullstack-chat-app
```

#### 2) Install Dependencies

```bash
# Install backend packages
cd backend
npm install

# Install frontend packages
cd ../frontend
npm install
```

#### 3️⃣ Setup Environment Variables

Create a `.env` file in the `backend/` directory and add the following:

```env
MONGODB_URI=your_mongodb_uri
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret

NODE_ENV=development
```

---

### ▶️ Run the App

#### Start the backend:

```bash
cd backend
npm start
```

#### Start the frontend (in a separate terminal):

```bash
cd frontend
npm run dev
```



---



### 📸 Demo Screenshots



---





### 🙋‍♂️ About Me

Hi, I'm Divyaanshu Agrawal — a passionate full-stack web developer currently focused on building real-time, scalable apps using modern tech stacks.  
Feel free to reach out or check out more of my work!

---

### 📬 Contact

- LinkedIn: [Your LinkedIn]
- Email: [Your Email]
