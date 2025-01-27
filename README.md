# post_images

# 🚀 Firebase User Management App  

This project is a 🔥 Firebase-based user management system that allows users to:  
- Sign in seamlessly via Google Authentication.  
- View a list of registered users fetched from Firestore.  
- Manage user details, including profile picture uploads and deletions.  

The app integrates **Google Authentication**, **Cloud Firestore**, and **Imgur API** for an enhanced user experience.  

---

## ✨ Features  

### 🔑 Sign-In  
- ✅ **Google Authentication** using Firebase for a secure and smooth login.  
- 🔐 **SHA Integration** for added security.  

### 🏠 Home Page  
- 📋 Displays a list of users stored in **Cloud Firestore**.  
- Each user entry includes:  
  - 📧 **Email**  
  - 👤 **Name**  
  - 🖼️ **Profile Picture** (hosted via **Imgur API**).  

### 👤 User Detail Page  
- View detailed information about individual users.  
- 🖼️ **Upload Images**: Add profile pictures through a `POST API`.  
- 🗑️ **Delete Users**:
  - Delete a user via a **Delete API**.  
  - Deletes the user's data from both the **server** and **Firebase**.  

### ✋ Long-Press Functionality  
- 🔥 **Long Press on Images**: Hold an image to delete it from the server and Firebase seamlessly.

---

## 🛠️ Technical Details  

- **Database**:  
  - 🔗 **Cloud Firestore** for storing user data.  
- **Authentication**:  
  - 🔐 **Google Authentication** via Firebase.  
- **Image Hosting**:  
  - 🖼️ Images are hosted using the **Imgur API**.  
- **Backend APIs**:  
  - Add and delete users.  
  - Upload images and store metadata in Firestore.  

---

## 🚀 Getting Started  

1. Set up Firebase:
  - Create a Firebase project in the Firebase Console.
  - Enable Google Authentication and Firestore in your project.
  - Add the SHA-1 key in Firebase settings.
    
2. Configure the Imgur API:
   - Get your Imgur API key from Imgur Developer Portal.
   - Add it to your .env file.

## 📷 Screenshots
<br>
<br>
<img src = "https://github.com/user-attachments/assets/4fc43e70-f8b0-4b12-a3f5-0548e192cf2a" height = 60% >
<br>
<br>
<img src = "https://github.com/user-attachments/assets/92674ed7-09df-4db9-8b37-ebd0bbcbb1c3" height = 60% >
<br>
<br>
<img src = "https://github.com/user-attachments/assets/28db60cf-3d62-4ef6-9667-0ea5ccf99272" height = 60% >
<br>
<br>
<div align="center">
<img src = "https://github.com/user-attachments/assets/f08d3589-c5f5-461e-9ce9-d6da3f68a279" height = 65% width = 25%>
<img src = "https://github.com/user-attachments/assets/d994b32b-5c54-48aa-9b80-131efb0d2dfc" height = 65% width = 25%>
<img src = "https://github.com/user-attachments/assets/4c592d1a-dbdf-4b1e-a35f-e41e9976c455" height = 65% width = 25%>
</div>

<br>

<div align="center">
<img src = "https://github.com/user-attachments/assets/b01960e8-0542-444f-bc62-30e1c26629d7" height = 65% width = 25%>
<img src = "https://github.com/user-attachments/assets/4d5d2ba1-83c9-4ce4-b6d9-0a4892566267" height = 65% width = 25%>
<img src = "https://github.com/user-attachments/assets/0aa93e3f-7778-404c-ac8f-6d71f120408e" height = 65% width = 25%>
</div>

### 📽️ Demo

<div align="center">
  <video height="450" controls src="https://github.com/user-attachments/assets/b46e4b88-f395-4af4-9a01-f9afe6acca4c"></video>
</div>


















