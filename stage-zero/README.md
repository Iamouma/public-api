# Stage 0 - Public API

##  Project Overview
This is a simple **public API** developed for the **HNG12 Stage 0 Backend Task**. The API returns basic information, including:
- Your registered email address.
- The current datetime in **ISO 8601 UTC format**.
- The GitHub URL of this project.

The API is built using **Node.js** with **Express.js** and is deployed on **Vercel**.

---

##  Live API Endpoint
The API is publicly accessible at:
```plaintext
https://hng12-stage0-api.vercel.app/
```

### Example Request
**Method:** `GET`
```sh
curl -X GET https://hng12-stage0-api.vercel.app/
```

### Example JSON Response
```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
```

---

## Setup Instructions
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/Iamouma/HNG-12.git
cd HNG-12/stage-zero
```

### **2️⃣ Install Dependencies**
```sh
npm install
```

### **3️⃣ Create a `.env` File**
Inside the root directory, create a `.env` file and add your email:
```env
EMAIL=your-email@example.com
GITHUB_URL=https://github.com/yourusername/repo.git
PORT=3000
```

### **4️⃣ Run the API Locally**
```sh
npm start
```
The API will start at `http://localhost:3000`.

### **5️⃣ Test the API**
Open a browser or use **Postman** to test:
```plaintext
http://localhost:3000/
```

---

## 📝 API Documentation
### **Endpoint: GET /**
- **Request:** No parameters required.
- **Response:**
  - `email`: Your registered email.
  - `current_datetime`: Current timestamp in **ISO 8601 format (UTC)**.
  - `github_url`: Link to this repository.

Example response:
```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
```

---

## 🌎 Deployment
This API is deployed on **Vercel**. To deploy your own:
1. Install Vercel CLI:
   ```sh
   npm install -g vercel
   ```
2. Run the deployment command:
   ```sh
   vercel
   ```
3. Follow the prompts to deploy.

---

## 📌 Additional Links
- **Hire Node.js Developers:** [https://hng.tech/hire/nodejs-developers](https://hng.tech/hire/nodejs-developers)
- **Project Repository:** [https://github.com/yourusername/your-repo](https://github.com/yourusername/your-repo)

---

### **🎯 Author**
**[Stepehen Ouma]** – [GitHub](https://github.com/Iamouma) 

