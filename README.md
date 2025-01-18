  ---

# 🚀 **Automated Upload & Capture-Upload Triggered by Wrong Password By User** 🎯

![Project Screenshot](./screenshot.png)  

---

## 🎨 **Project Overview**

This project captures images using a webcam whenever an incorrect password attempt is detected. It automates the process of:
- 📸 Capturing the user's image.
- 🌐 Uploading the captured image to a specified URL.
- 🗃️ Organizing images into folders for easy management.

---

## 🗂️ **Project Structure**  

```plaintext
📦 capture-upload-triggered-by-wrong-password
 ├── 📁 .idea                  # Project configuration files for IDE
 ├── 📁 camera                 # Folder for the camera's original image files
 ├── 📁 uploads                # Folder to store successfully uploaded files
 ├── 📁 captures               # Folder for captured images triggered by wrong passwords
 ├── 🐍 monitorCameraFolder.py # Main Python script for monitoring and capturing
 └── screenshot.png            # Project structure screenshot
```

---

## ⚙️ **Features**

1. ✅ **Password Monitoring**: Detects failed password attempts.  
2. 📷 **Automatic Capture**: Captures a picture using a webcam.  
3. 🔄 **Automatic Upload**: Uploads captured images to a specified remote server.  
4. 📂 **File Management**: Organizes files into dedicated folders for clarity.

---

## 🛠️ **Getting Started**

### 📥 **Installation**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo-url/capture-upload.git
   ```
2. **Install Dependencies**:
   - Make sure Python 3.x is installed.
   - Install required libraries:
     ```bash
     pip install opencv-python
     ```

---

### 🚀 **Usage**

1. **Run the Script**:
   ```bash
   python monitorCameraFolder.py
   ```
2. **Monitor Password Attempts**:
   - The script will monitor for incorrect password attempts.  
3. **Capture and Upload**:
   - Captured images are saved in the `captures` folder and uploaded to the configured server.  

---

## 🌟 **Customization**

1. **Update the Upload URL**:  
   Modify the `upload_url` variable in the script to your server's endpoint.  

2. **Adjust Folders**:  
   Customize folder paths (`captures`, `uploads`) as needed.  

---

## 📌 **Future Improvements**

- **Log Parsing**: Add real-time password monitoring from system logs.  
- **Enhanced Security**: Encrypt image uploads for added security.  
- **Multi-Camera Support**: Enable simultaneous captures using multiple webcams.  

---

## 💻 **Contributors**

- **[Your Name]** ✨ - Developer  
- **[Contributor 2]** 💡 - Idea/Testing  

---

## 📄 **License**

[MIT License](LICENSE)

---

> **✨ Tip**: Keep your project organized and updated. Contributions are welcome! 🎉  

--- 

Feel free to modify this as needed! Let me know if you'd like additional sections.
