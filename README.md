Setup Instructions
1️⃣ Clone the Repository

git clone https://github.com/fatems/node-docker-app.git
cd node-docker-app

2️⃣ Install Dependencies

npm install

3️⃣ Run Locally

node server.js

🌍 Open http://localhost:3000 in your browser.
🐳 Docker Setup
1️⃣ Build the Docker Image

docker build -t miniapp .

2️⃣ Run the Docker Container

docker run -p 3000:3000 miniapp

Now your app is running inside Docker! 🚀


📜 API Endpoints
Method	Endpoint	Description
GET	/	Returns "heyheyhye world!"
