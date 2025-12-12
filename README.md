\# Project 1 - ReactJS + NodeJS + MySQL (Docker)



\## 📌 Yêu cầu môi trường

\- Docker Desktop (kèm WSL2)

\- Docker Compose



---



\# 🚀 Cách chạy project



\## 1. Clone project

git clone https://github.com/<your-username>/project1-react-node-mysql.git 

cd project1-react-node-mysql



\## 2. Tạo file `.env`

Copy:

cp .env.example .env

Hoặc tạo thủ công.



\## 3. Khởi chạy Docker

docker compose up --build



\## 4. Truy cập hệ thống

\- Frontend (React): \*\*http://localhost:8080\*\*

\- Backend API (Node): \*\*http://localhost:3000\*\*

\- MySQL (host machine): \*\*localhost:3307\*\*

\- phpMyAdmin (nếu bật): \*\*http://localhost:8081\*\*



---



\# 📂 Cấu trúc thư mục



project1-react-node-mysql/

│── frontend/ # React app + Dockerfile

│── backend/ # NodeJS API + Dockerfile + index.js

│── db/

│ └── init.sql # Tạo database \& bảng mẫu

│── docker-compose.yml

│── .env.example

│── .gitignore

│── README.md



---



\# ⚠️ Lưu ý khi nộp bài

\- ❌ KHÔNG commit `node\_modules`

\- ❌ KHÔNG commit file `.env` thật  

\- ✔ Có file `.env.example`

\- ✔ Có Dockerfile FE + BE

\- ✔ Có docker-compose.yml

\- ✔ Có README.md hướng dẫn chạy

\- ✔ Có db/init.sql



---



Nếu bạn muốn, tôi có thể \*\*kiểm tra lại docker-compose, Dockerfile frontend/backend và index.js\*\* cho bạn để chắc chắn khi nộp không bị lỗi.



Bạn muốn kiểm tra tiếp không?



