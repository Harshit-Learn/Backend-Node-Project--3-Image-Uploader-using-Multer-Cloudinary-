## Image Uploader - Multer & Cloudinary


````markdown
# 📸 Image Uploader - Multer & Cloudinary

This project is a simple **Node.js + Express** backend where users can upload images.  
The images are stored securely on **Cloudinary** instead of the local system.  
We use **Multer** as middleware to handle file uploads.

---

## 🚀 Live Demo
🔗 [Image Uploader](https://image-uploader-khaki.vercel.app/)

---

## ⚙️ Tech Stack
- **Node.js** - JavaScript runtime  
- **Express.js** - Backend framework  
- **Multer** - Middleware for handling multipart/form-data (file uploads)  
- **Cloudinary** - Cloud storage for images  

---

## 📂 Features
- Upload images from your device  
- Store images directly in Cloudinary  
- Secure and scalable image hosting  
- API-based implementation for easy integration  

---

## 📸 Workflow
1. User selects an image.  
2. Multer handles the file upload.  
3. Image is sent to **Cloudinary**.  
4. Cloudinary returns a hosted **URL** of the uploaded image.  

---

## 🛠️ Installation & Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/image-uploader.git
   cd image-uploader
````

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file and add your Cloudinary credentials:

   ```env
   CLOUD_NAME=your_cloud_name
   CLOUD_API_KEY=your_api_key
   CLOUD_API_SECRET=your_api_secret
   ```

4. Run the server:

   ```bash
   npm start
   ```

---

## 📌 API Endpoints

### Upload Image

`POST /upload`

* **Body (form-data):**

  * `image` → File (required)

* **Response:**

  ```json
  {
    "url": "https://res.cloudinary.com/your-cloud/image/upload/xyz.png"
  }
  ```

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📜 License

This project is licensed under the **MIT License**.



