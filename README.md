# 🐉 Dragon News - Authentication Integrated News Portal

**Dragon News** is a professional news aggregation platform built with **React**, **Vite**, and **Tailwind CSS**.  
It integrates **Firebase Authentication** to provide secure login and registration and dynamically displays categorized news in a modern, responsive layout.

---

## 🚀 Live Demo


---

## ✨ Key Features

- 🔑 **Firebase Authentication** – Secure login & registration system.  
- 📰 **Dynamic News Feed** – Categorized news sections (World, Sports, Entertainment, etc.).  
- 📱 **Responsive Design** – Fully optimized for mobile, tablet, and desktop screens.  
- 🔒 **Private Routes** – Protect specific news pages and require login to access.  
- ♻️ **Global State Management** – Using **Context API** for user authentication and app-wide state.  
- ⚡ **Fast Client-Side Navigation** – Powered by **React Router DOM**.  
- 🎨 **Modern UI Components** – Built with **Tailwind CSS** and **DaisyUI**.  
- 🖼️ **Reusable Components** – Clean, scalable structure with modular components.

---

## 🛠️ Tech Stack

| Category          | Technology                     |
|------------------|--------------------------------|
| Frontend         | React.js, Vite                 |
| Styling          | Tailwind CSS, DaisyUI           |
| Authentication   | Firebase (Auth)                |
| Routing          | React Router DOM               |
| Icons            | React Icons                    |
| Deployment       | Vercel / Firebase Hosting      |

---

## 📂 Project Structure

```
Dragon-news/
├── public/                # Static assets like news.json and categories.json
├── src/
│   ├── assets/            # Images and media files
│   ├── components/        # Reusable UI components
│   │   ├── homelayout/    # Components specific to the Home layout
│   │   ├── Header.jsx
│   │   ├── Navbar.jsx
│   │   └── NewsCard.jsx
│   ├── firebase/          # Firebase configuration (firebase.config.js)
│   ├── layouts/           # Main layouts (AuthLayout, HomeLayout)
│   ├── pages/             # Page views (Login, Register, Home)
│   ├── provider/          # Context API (AuthProvider) for global state
│   ├── routes/            # Route definitions & PrivateRoute logic
│   ├── App.jsx            # Root component
│   └── main.jsx           # Entry point for React/Vite
├── .gitignore             # Node modules, .env, etc.
├── package.json           # Project dependencies and scripts
└── README.md              # Project documentation
```

---

## 📌 Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/Md-Jahid-Hasan-10/dragon-news.git
```

2. **Navigate to the project directory**
```bash
cd dragon-news
```

3. **Install dependencies**
```bash
npm install
```

4. **Start the development server**
```bash
npm run dev
```

5. **Open in browser**
```
http://localhost:5173
```

---

## 🎯 Learning Outcomes

Through building this project, I gained experience in:

- Implementing **secure authentication** using Firebase.  
- Structuring **React projects** with Context API for state management.  
- Building **private routes** and dynamic navigation using React Router.  
- Creating **responsive layouts** with Tailwind CSS and DaisyUI.  
- Building **reusable components** for scalable front-end development.  
- Handling **real-time dynamic data** in React.  

---

## 📸 Screenshots

*Add screenshots or GIF demos here to showcase your project UI.*

---

## 🔮 Future Enhancements

- Add **news search functionality**.  
- Integrate **pagination or infinite scroll** for news lists.  
- Enable **dark mode toggle** for better user experience.  
- Add **comments or user interactions** on news articles.  

---

## 👨‍💻 Author

**Jahid Hasan**

- GitHub: https://github.com/Md-Jahid-Hasan-10
- LinkedIn: https://www.linkedin.com/in/jahid-hasan-a3b51b3a0/ 

---

⭐ If you find this project useful or impressive, please consider giving it a **star** on GitHub!