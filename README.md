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

