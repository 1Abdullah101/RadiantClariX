# RadiantClariX
RadiantClariX - AI X-Ray Analysis Application

User Manual & Documentation
Version: 1.0.0
Release Date: October 2025
Last Updated: October 30, 2025

Table of Contents
1. Introduction
2. Key Features
3. How to Start the Application
4. User Guide
5. Settings & Features
6. Troubleshooting
7. Technical Specifications
8. Privacy & Security
9. Support
10. Important Disclaimers
11. About the AI Models


    
Introduction
RadiantClariX is an advanced AI-powered medical imaging application that analyzes X-ray
images and provides detailed diagnostic reports. The app uses machine learning models to
detect abnormalities in chest X-rays and identify bone fractures with high accuracy.
Perfect for:
- Healthcare professionals seeking quick preliminary analysis
- Medical students learning radiology
- Clinics needing AI-assisted diagnostics
- Research and educational purposes

  
Key Features
Dual AI Models:
1. Chest X-Ray Analyzer - Generates detailed textual descriptions of chest X-ray images.
Describes visible anatomical features, abnormalities, and medical devices. Provides both
technical medical terminology and plain language explanations. Uses BLIP AI technology for
image captioning
2. Bone Fracture Detector - Identifies seven bone injury types with bounding boxes and
confidence scores. Detects 7 types of bone injuries:
User-Friendly Interface:
- Dark & Light Theme
- Easy Image Upload
- Real-time Analysis
- Scan History
- PDF Export
Secure & Private:
- Authentication system
- Encrypted data storage
- Option to delete accounts and data


How to Start the Application
Step 1: Start the Backend Services
1. Open Project file in VSCode or in any other IDE
2. Navigate to the backend folder:
 cd D:\xray-app\radiantclarix\backend
3. Type “.\start-all-services.ps1” and hit ENTER.
Step 2: Start the Frontend App
1. Open Project file in VSCode or in any other IDE
2. Navigate to app folder:
 cd D:\xray-app\radiantclarix
3. Type: “npm start” and hit ENTER
Step 3: Open the App
Use Expo Go on mobile or emulator/web browser.


User Guide
Registration & Login:
- Register or Login using email and password.
Dashboard:
- Upload & Analyze, View History, Settings, Logout.
Upload & Analyze:
- Select model (Chest/Bone)
- Enter patient name
- Upload image (camera or gallery)
- Analysis starts automatically.
Understanding Results:
- Technical Report (for professionals)
- Plain Language Report (for patients)
- Generate PDF, Start New Scan, View Annotated Image.
Scan History:
- Full record of all scans with reports and dates.
Settings Page:
- Account Info, Theme, Change Password, Delete History, Delete Account, Logout.


Troubleshooting
App Won’t Start:
- Ensure backend services are running.
- Restart both backend and frontend.
Login Issues:
- Check credentials and internet connection.
Upload Issues:
- Grant permissions, restart app, ensure models running.
History Not Updating:
- Refresh or restart app.
Performance:
- Restart backend, use smaller images, clear cache.


Technical Specifications
System Requirements:
Backend - Windows 10/11, Python 3.8+, Node.js 14+, 8GB RAM, 5GB disk.
Frontend - Android/iOS device with Expo Go or browser.
Ports Used:
5000 - Backend
8502 - Chest X-Ray AI Model
8503 - Bone Fracture Model
8081 - Expo Dev Server


Privacy & Security
Data Protection:
- Passwords encrypted and hashed
- MongoDB secure storage
User Rights:
- View, delete, or export data anytime.
Recommendations:
- Use strong passwords
- Logout on shared devices
- Backup reports regularly


Support
Q: Is this suitable for medical diagnosis?
A: No, use for preliminary analysis only.
Q: Offline mode?
A: Internet required.
Q: How many scans can I store?
A: Unlimited. Reports will be available for 15 days only from the time they are generated.
Q: Can I share reports?
A: Yes, via PDF export.
Q: Data privacy?
A: Fully private and user-only access.


Important Disclaimers
Medical Disclaimer:
- Educational use only.
- Do not replace professional diagnosis.
- Consult professionals for treatment.
Accuracy Notice:
- AI confidence scores vary.
- False positives/negatives possible.
- Models updated regularly for improved accuracy.


About the AI Models
Chest X-Ray Model:
- BLIP (Bootstrapping Language-Image Pretraining)
- Detects lung/heart issues, medical devices.
Bone Fracture Model:
- Faster R-CNN with ResNet-50 backbone
- Detects seven fracture types with bounding boxes and confidence scores.
