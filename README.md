HikeSim — Android XR Pipeline [Project Aura Integration]
Migrated from iOS/watchOS to the Android XR platform via Android Studio (Quail Preview). Utilizing the Jetpack XR SDK, HikeSim features a synchronized multi-device topology that bridges contextual smart eyewear and immersive wired XR glasses.

This repository serves as the official structural showcase for the Google/XREAL Android XR Developer Catalyst Program review committee.

📺 Architecture & Simulator Proof Video
Latest Demo (Android AI Display & XR Glasses): https://youtu.be/kqPfrSi3KM4

Core Feature & Share Flow Demonstration: https://youtu.be/AvANEHC-6qc

🛠️ Architecture Overview
HikeSim utilizes a synchronized multi-device topology built natively for the Android XR ecosystem:

Wear OS Module: Low-power sensory data capture and fitness tracking stream (capturing real-time metrics including heart rate and elevation change per mile split).

Android Compute Hub (Puck/Phone): Core mapping, processing, and localized simulation engine.

Wired XR Glasses Track (Project Aura): High-fidelity, immersive spatial canvas rendering utilizing Jetpack XR Core and SceneCore libraries for stereoscopic 3D telemetry visualization.

Intelligent Eyewear Track (Display/Audio Glasses): Glanceable, heads-up notification layer for outdoor real-time navigation.

🚀 Technical Milestones & Capability Updates (June 2026)
Cross-Form-Factor Compatibility: Seamlessly scaled the pipeline to support both immersive XR displays (Project Aura) and lightweight Android AI Display smart glasses, complete with a hardware-agnostic Glasses Reset orientation capability.

Multimodal Asset Interaction: Integrated user text and audio overlays into the spatial hike framework. Telmetry points support text-to-speech engine playback alongside custom textual data layers.

Generative AI Integration Layer: Architected an interface for Google Gemini agents to automatically generate contextual overview descriptions and localized environmental details for newly created hikes based on telemetry data.

Hardware Control Surfaces: Implemented a low-latency Wear OS touch controller surface, enabling the wearable device to function as a peripheral input to navigate and control the glasses' spatial display windows.

Screen Mirroring Pipeline: Fully realized an optimized screen-mirroring and casting framework from the compute hub to the XR glasses environment, demonstrated successfully within the Android Studio emulator environment.

🔐 CODE ACCESS NOTE FOR REVIEWERS:
To protect proprietary mapping algorithms, the compiled source code is maintained in a secure, private repository. If you are a Developer Relations representative or technical reviewer from Google or XREAL evaluating this Catalyst application, please contact me at acgross144@gmail.com or invite my GitHub handle directly for immediate access to the core repository branches and build variants.

