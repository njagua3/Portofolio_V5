
# Portfolio V5

Hello, everyone!  
Let me introduce myself, I'm Eki Zulfar Rachman, and today, I'd like to share a portfolio website project I have developed.  

## Tech Stack Used:
- ReactJS  
- Tailwind CSS  
- AOS  
- Firebase  
- Framer Motion  
- Lucide  
- Material UI  
- SweetAlert2  

### Website Link:  
[https://www.eki.my.id/](https://www.eki.my.id/)  

We would appreciate it if you could include our credit when using this project. Thank you! 🙏  

---

# Tutorial: Running the Project  

Here’s a simple guide to run this project.  

## Preparation  

Ensure you have installed:  
- **Node.js**  

## Steps to Run the Project  

1. **Download the project:**  

   ```bash
   git clone https://github.com/EkiZR/Portofolio_V5.git
   ```  

2. **Install all dependencies:**  

   ```bash
   npm install
   ```  
   or alternatively:  

   ```bash
   npm install --legacy-peer-deps
   ```  

3. **Run the project:**  

   ```bash
   npm run dev
   ```  

4. **Open in browser:**  

   Access the application in your browser via the link displayed in the terminal.  

## Creating a Production Build  

To create a production-ready version:  

1. Run the build command:  

   ```bash
   npm run build
   ```  

2. The build files will be saved in the `dist` folder. You can upload this folder to your hosting server.  

---

## Notes  

If you encounter issues while running the project, ensure that:  
- Node.js is properly installed.  
- You are in the correct project folder.  
- All dependencies are installed without errors.  

---

## Firebase Configuration  

To configure Firebase for this project, follow these steps:  

1. **Add Firebase to Your Project:**  
   - Open [Firebase Console](https://console.firebase.google.com/).  
   - Create a new project or use an existing one.  

2. **Select Firestore Database:**  
   - Create a database.  

3. **Go to Project Settings:**  
   - Click the relevant section:  
     ![Screenshot](https://github.com/user-attachments/assets/43243cad-b414-4dd9-8793-d15c401c82fe)  
   - Copy the contents of the Firebase config:  
     ![Image](https://github.com/user-attachments/assets/6d0e158c-1ae0-40c1-8b41-9e53a1c4ccbb)  

4. **Navigate to Rules:**  
   - Change the rules to `true`.  

5. **Adjust the Collection Structure:**  
   Refer to the structure in the images below:  
   ![Screenshot](https://github.com/user-attachments/assets/38580122-08a4-4499-a8fd-0f253652a239)  
   ![Screenshot](https://github.com/user-attachments/assets/d563d7ad-f1ab-46ff-8185-640dcebd0363)  

6. **Open `firebase.js` and `firebase-comment.js`:**  
   - Replace the `firebaseConfig` content with your Firebase configuration.  

---
