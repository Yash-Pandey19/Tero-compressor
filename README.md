# Tero-Compressor

**Tero-Compressor** is a full-stack file compression web application that allows users to upload any file and compress it on the server. Built with Node.js and JavaScript, it supports real-time file compression with feedback on compression ratio.

---

## 🚀 Features

- 📁 Upload any file type
- 📉 Server-side compression using `zlib`
- 📊 Displays original size, compressed size, and compression ratio
- 📦 Instant download of compressed files
- 🌐 Simple and responsive web interface
- 🐳 Fully dockerized using Docker and Docker Compose

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express
- **Frontend**: HTML, CSS, Vanilla JavaScript
- **Compression**: `zlib` Node.js module
- **Containerization**: Docker, Docker Compose

---

## 🧪 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/Yash-Pandey19/Tero-compressor.git
cd Tero-compressor
```

### 2. Install Dependencies

```bash
npm install
```
### 3. Run the App

```bash
node server.js
```
#### Visit: http://localhost:3000

---

## 🐳 Docker Setup
### 1. Build and Run Using Dockerfile

```bash
 docker build -t tero-compressor .
```
### 2. Run the container on port 3000

```bash
 docker run -p 3000:3000 tero-compressor
```
#### App will be live at: http://localhost:3000

---

## 📁 Project Structure

```
Tero-Compressor/
├── html/                  # HTML interface files
├── js_files/              # JavaScript files for frontend logic
├── public/                # Static files
├── uploads/               # Stores uploaded files temporarily
├── compressed/            # Stores compressed output files
├── server.js              # Main Express server file
├── package.json           # Node dependencies
├── Dockerfile             # Docker setup
├── docker-compose.yml     # Compose setup
└── README.md              # Project documentation
```

---

## 📌 Notes

- Compression is handled using Node.js `zlib` module.
- You can upload any file type.
- Compression ratio is dynamically shown.
- Compressed files are available for instant download.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

- [Yash Pandey](https://github.com/Yash-Pandey19)
