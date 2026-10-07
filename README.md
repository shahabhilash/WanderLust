# 🌍 WanderLust

WanderLust is a full-stack web application designed to let users explore, create, and manage beautiful property and travel listings worldwide.

## 🚀 Features

- **Complete CRUD Functionality:** Seamlessly browse, create, edit, and delete property listings.
- **RESTful API Architecture:** Clean, predictable, and standard routing for all resources.
- **Robust Error Handling:** Utilizes a custom `ExpressError` class and an async wrapper to catch and handle database or server errors gracefully without crashing.
- **Dynamic Server-Side Rendering:** Uses EJS templating for dynamic data injection directly into the views.

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Frontend:** HTML, EJS (Embedded JavaScript)
- **Development Tools:** Nodemon, dotenv

## ⚙️ Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shahabhilash/WanderLust.git
   cd WanderLust
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up Environment Variables:**
   Create a `.env` file in the root directory and configure your MongoDB connection and port:
   ```env
   MONGO_URL=mongodb://127.0.0.1:27017/wanderlust
   PORT=8080
   ```

4. **Initialize the Database (Optional):**
   To populate the database with dummy listings, run the initialization script:
   ```bash
   node init/index.js
   ```

5. **Start the Development Server:**
   ```bash
   npm run dev
   ```
   The application will be running at `http://localhost:8080`.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).