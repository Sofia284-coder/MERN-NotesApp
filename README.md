# 📝 MERN Stack Note Taking App ✨

This repository contains a full-stack Note-Taking application built as a guided learning project. I developed this by following a detailed tutorial to transition from theoretical knowledge to practical implementation of the MERN stack.

The focus of this project was not just on building a CRUD app, but on understanding **professional-grade concepts** and modern industry standards for web applications.

---

## 🎓 What I Learned

By following this tutorial, I gained hands-on experience with several advanced concepts that are essential for real-world development:

### 1. The MERN Ecosystem
Successfully integrated all four components of the stack: **MongoDB** (Database), **Express** (Backend Framework), **React** (Frontend Library), and **Node.js** (Runtime Environment).

### 2. Modern API Communication
* **Axios:** Learned how to use Axios to handle asynchronous HTTP requests, manage headers, and handle responses/errors gracefully on the frontend.
* **REST API Design:** Built and tested routes for GET, POST, PUT, and DELETE methods using proper status codes (200, 201, 400, 500, etc.).

### 3. Database Management
* **MongoDB Atlas:** Set up a cloud database, configured network access, and handled connection strings.
* **Mongoose:** Used schemas to enforce data structure in a NoSQL environment.

### 4. Advanced Backend Concepts
* **Rate Limiting with Upstash:** Implemented a real-world security layer using Redis to prevent API abuse and manage traffic.
* **File Structure:** Instead of putting everything in one file, I learned how to organize code into a scalable architecture using folders for `models`, `routes`, and `controllers`.
* **Environment Variables:** Used `.env` files to keep sensitive information like database URIs and API tokens secure.

### 5. Frontend & UI
* Learned how to build a **completely responsive UI** that adapts to different screen sizes.
* Managed application state in React to reflect database changes in real-time.

---

## 🔧 Installation & Setup

### 1. Clone the repository
```bash
git clone <your-repository-url>
cd <repository-folder-name>

```

### 2. Backend Setup (`/backend`)

Create a `.env` file in the backend folder and add your credentials:

```env
MONGO_URI=<your_mongo_uri>
UPSTASH_REDIS_REST_URL=<your_redis_rest_url>
UPSTASH_REDIS_REST_TOKEN=<your_redis_rest_token>
NODE_ENV=development

```

**Run the backend:**

```bash
cd backend
npm install
npm run dev

```

### 3. Frontend Setup (`/frontend`)

**Run the frontend:**

```bash
cd frontend
npm install
npm run dev

```

---

## 📜 Acknowledgments

* This project was built as part of a tutorial to master full-stack fundamentals.
* Special thanks to the original tutorial creator for providing the roadmap to explore these concepts.
* Developed for educational purposes to strengthen my portfolio in web development.

```
https://github.com/burakorkmez/mern-thinkboard
https://youtu.be/F9gB5b4jgOI?si=SfUsDz98UI2HBI5_
```
