# HikeSim — Android XR Pipeline [Project Aura Integration]

Migrated the iOS/Apple Watch HikeSim app to Android/Wear via the AI Studio (Preview). Gemini handled the migration perfectly. Added several new features. Features added sharable hikes via text/email, watch simulator to preview hikes, hike cards in View Hikes (Android), new heart rate and altitude change metrics for each mile split and XR Jetpack Libraries.

This repository serves as the official structural showcase for the Google/XREAL 
Android XR Developer Catalyst Program review committee. 

### 📺 Architecture & Simulator Proof Video
https://youtu.be/o_9N987M8GQ?si=F3P8jgFZPdJrX0ty


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
