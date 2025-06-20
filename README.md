# 🔮 Oracle Card Reader

The **Oracle Card Reader** is a full-stack web application that allows users to interact with a custom oracle card system online. Users can draw cards, interpret meanings, save their readings, and revisit their personal oracle history. The application blends spiritual introspection with modern web technology, offering a sleek and intuitive platform for self-guidance and reflection.

## 📌 Project Overview

Oracle cards are a tool for personal reflection, meditation, and insight. This project aims to digitize that experience by providing an interactive interface to draw and interpret oracle cards. Whether for daily guidance or personal journaling, this web app allows users to build a digital history of their readings.

This project was built as part of a full-stack development internship and includes features like user authentication, state management with Redux, and backend integration with MongoDB.

## 🚀 Key Features

- 🃏 **Interactive Card Drawing**: Users can virtually draw cards from a deck for personalized readings.
- 📝 **Card Meanings Display**: Each card comes with a predefined interpretation or description.
- 💾 **Local and Cloud Storage**: Users can save their card readings locally and optionally sync them to a MongoDB database.
- 🔐 **User Authentication**: Secure login and registration system to keep user readings private.
- 📊 **Redux State Management**: Efficient handling of app-wide state, including card selection, user data, and saved history.
- 📱 **Mobile Responsive Design**: Seamless experience across desktops, tablets, and phones.
- 🧠 **High Code Quality**: Exception management, modular file structure, and test coverage using JUnit (for backend).

## 🛠️ Tech Stack

### Frontend
- **React.js** – Component-based user interface
- **Redux** – State management
- **HTML/CSS** – Styling and layout
- **JavaScript** – Client-side logic

### Backend
- **Node.js** – JavaScript runtime
- **Express.js** – Web framework for APIs
- **MongoDB** – NoSQL database for user/card data
- **JWT** – For user session authentication

### Tools & Utilities
- **Git** – Version control
- **VSCode** – Development environment
- **Postman** – API testing
- **Google Apps Script** – Integrated in leaderboard for data sync

## 🧑‍💻 How to Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/PrabhavNasa/Oracle-Card-Reader.git
cd Oracle-Card-Reader
```

### 2. Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the `backend` directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

### 4. Run the App

#### Start Backend

```bash
cd backend
npm run dev
```

#### Start Frontend

Open a new terminal:

```bash
cd frontend
npm start
```

Visit `http://localhost:3000` in your browser.

## 📁 Project Structure

```
Oracle-Card-Reader/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── redux/
│   │   ├── pages/
│   │   └── App.js
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
│
└── README.md
```

## 📈 Future Improvements

- 🌐 Add multilingual support
- 🎨 Add drag-and-drop card layout
- 📊 Visualization dashboard of past readings
- 📦 Export readings to PDF or email
- 📱 Publish mobile app version (React Native)

## 🧪 Testing

- Backend unit testing using **JUnit**
- Manual testing for card flows and authentication
- Postman used for API testing

## 🙋‍♂️ Why This Project?

Oracle cards are used by many for introspection and mindfulness. By digitizing this experience, the Oracle Card Reader allows users to access spiritual tools online in a structured, secure, and beautiful way. The project was also a platform to learn full-stack development practices.

## 👨‍💻 Author

**Prabhav Nasa** – Developer and Designer  
[GitHub](https://github.com/PrabhavNasa) | [LinkedIn](https://linkedin.com/in/prabhavnasa23)

## 📄 License

This project is licensed under the MIT License.

---

Made with ❤️ during my full-stack internship.
