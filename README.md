# HikeSim — Android XR Pipeline [Project Aura Integration]

Migrated the iOS/Apple Watch HikeSim app to Android/Wear via the AI Studio (Preview). Gemini handled the migration perfectly. Added several new features. Features added sharable hikes via text/email, watch simulator to preview hikes, hike cards in View Hikes (Android), new heart rate and altitude change metrics for each mile split and XR Jetpack Libraries.

This repository serves as the official structural showcase for the Google/XREAL 
Android XR Developer Catalyst Program review committee. 

### 📺 Architecture & Simulator Proof Video
https://youtu.be/AvANEHC-6qc?si=t_4x48fE3xOqpe7_


### 🛠️ Architecture Overview
HikeSim utilizes a synchronized multi-device topology built natively for the Android XR ecosystem:
1. Wear OS Module: Low-power sensory data capture and tracking stream.
2. Android Compute Hub (Puck): Core mapping processing engine utilizing Jetpack XR Core / SceneCore libraries.
3. Spatial Display (Project Aura): Dynamic 3D canvas window positioning and vector mapping output.

---
🔐 CODE ACCESS NOTE FOR REVIEWERS:
To protect proprietary mapping algorithms, the compiled source code is maintained in a 
secure, private repository. If you are a Developer Relations representative from Google 
or XREAL reviewing this Catalyst application, please contact me at acgross144@gmail.com or invite 
my GitHub handle directly for immediate access to the core repository branches.

May 26th update.
Implemented screen mirroring for the XR Glasses. The youtube video shows a demo of the current project.

May 27, 2026 update.
Completed XR portion to allow for simulated hikes on the Android phone as well as the XR glasses. All app features are present in this version. The demonstration video explains how the app was created.

May 30, 2026 update.
All features of the App are now implemented and tested in Android Studio Preview.
