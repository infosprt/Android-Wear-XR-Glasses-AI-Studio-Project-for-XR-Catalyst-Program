# HikeSim — Android XR Pipeline [Project Aura Integration]

Migrated the iOS/Apple Watch HikeSim app to Android/Wear via the Android Studio (Quail Preview). Gemini handled the migration perfectly. Added several new features. Features added sharable hikes via text/email, watch simulator to preview hikes, hike cards in View Hikes (Android), new heart rate and altitude change metrics for each mile split and XR Jetpack Libraries.

This repository serves as the official structural showcase for the Google/XREAL 
Android XR Developer Catalyst Program review committee. 

### 📺 Architecture & Simulator Proof Video
https://youtu.be/kqPfrSi3KM4?si=0R2ulnZhYYpfeZLQ

Prior video that demonstrated the ability for the user to create and share hikes.
https://youtu.be/AvANEHC-6qc?si=61Nxze50PheCPPyz


### 🛠️ Architecture Overview
HikeSim utilizes a synchronized multi-device topology built natively for the Android XR ecosystem:
1. Wear OS Module: Low-power sensory data capture and tracking stream.
2. Android Compute Hub (Puck): Core mapping processing engine utilizing Jetpack XR Core / SceneCore libraries.
3. Spatial Display (Project Aura): Dynamic 3D canvas window positioning and vector mapping output.
4. HikeSim photo hikes running in Android Studio for both XR (xReal) and Android AI Display glasses.

---
🔐 CODE ACCESS NOTE FOR REVIEWERS:
To protect proprietary mapping algorithms, the compiled source code is maintained in a 
secure, private repository. If you are a Developer Relations representative from Google 
or XREAL reviewing this Catalyst application, please contact me at acgross144@gmail.com or invite 
my GitHub handle directly for immediate access to the core repository branches.

June 28, 2026 update.
1. Inclusion of Android AI Display glasses.
2. User text/audio included as part of the hike. Users can give additional details about a particular spot in the hike as well as an overview of the hike. This textual/audio capability could be automatically created by Google Gemini or via user entered text. In both cases the text is displayed and the audio (text to speech) is played.
3. A glasses reset capability.
4. Minor UI changes for useablility. 

May 26th update.
Implemented screen mirroring for the XR Glasses. The youtube video shows a demo of the current project.

May 27, 2026 update.
Completed XR portion to allow for simulated hikes on the Android phone as well as the XR glasses. All app features are present in this version. The demonstration video explains how the app was created.

May 30, 2026 update.
All features of the App are now implemented and tested in Android Studio Preview.
