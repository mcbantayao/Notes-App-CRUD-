[This is a basic Notes App on AWS]
Serverless API (Lambda + API Gateway + DynamoDB)
Skills: Serverless, API design, NoSQL

🏗️ Architecture Overview
User (Browser)
     ↓
S3 (Static Website - HTML/JS)
     ↓
API Gateway (REST API)
     ↓
Lambda (Python backend)
     ↓
DynamoDB (Notes table)

Architecture:
🌐 Frontend hosted on S3(static website)
⚡ Serverless backend (Lambda) 
🔗 API Gateway + Lambda → backend logic
🗄️ Database: DynamoDB 



🔗 API Gateway integration → REST API

<img width="1079" height="290" alt="image" src="https://github.com/user-attachments/assets/a02e3279-d5d7-4e1a-a991-10ea464ee467" />

<img width="1193" height="471" alt="image" src="https://github.com/user-attachments/assets/b20939a8-7d23-4723-a0cd-db7b178e3ecb" />

