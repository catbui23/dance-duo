# DanceDuo: Bridging Human Movement and AI Choreography

DanceDuo is an interactive AI-powered platform for music-driven dance generation and comparison. By leveraging diffusion models and human pose estimation, the system enables users to generate AI choreography and compare it with their own dance performance.

## Features
- 🎵 Music-driven dance generation using diffusion models
- 🕺 Multiple humanoid models
- 📹 Upload and compare personal dance videos
- 📊 Scoring system for performance evaluation
- 🔄 Side-by-side comparison between user and AI

## Design

DanceDuo is designed to bridge AI-generated choreography and human interaction, focusing on engagement, learning, and creativity.

1. Music-to-Dance Generation: Built on a diffusion-based model (DanceFusion)
2. Motion Representation: Uses SMPL (Skinned Multi-Person Linear Model)
3. Pose Estimation from User Video: Uses ROMP (real-time 3D pose estimation)
4. Scoring System: Combines:
   - MPJPE (Mean Per Joint Position Error)
   - MPJAE (Mean Per Joint Angle Error)
   - Transforms similarity into a Beta distribution
   - Keeps scores in a motivating range (≈ 6–8/10)

## Application Flow

<img width="2048" height="655" alt="application_flow" src="https://github.com/user-attachments/assets/9c5fc4a1-3704-4a60-b568-c41bcb2a283b" />

The system follows a user-centric interactive workflow:

1. Select Input
   - Choose a music track
   - Choose a humanoid model
2. Generate Dance
   - AI generates choreography synchronized with music
3. User Interaction
   - Watch generated dance
   - Record or upload personal dance video
4. Pose Estimation
   - Extract 3D pose from user video
5. Comparison & Scoring
   - Compare AI vs user motion
   - Compute similarity score
6. Result Visualization
 - Side-by-side playback
 - Display performance score

## User Study Highlights
- ✅ Users found the system intuitive and engaging
- ⭐ Dance comparison feature is the most appreciated
- 🎵 Variety of music and models improves engagement
- ⚠️ Suggested improvements:
    - Better UI guidance
    - Improved synchronization

## Demo video

[Watch full demo video](/video/danceduo_demo.mp4)

## Screenshots

<p align="center">
 <img width="48%" alt="music" src="https://github.com/user-attachments/assets/5fe20a74-c69e-4a60-a9b7-913de98d5e63" />
 <img width="48%" alt="humanoid" src="https://github.com/user-attachments/assets/ff71961f-618a-4b4f-a4a5-3e74e71e16ae" />
</p>

<p align="center"><sub>Select music and humanoid model</sub></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e750d7b9-7484-48e5-9d14-9e849bff4caf" width="32%" />
  <img src="https://github.com/user-attachments/assets/3001cf16-c7b0-497c-99e1-00e8b4d31a9b" width="32%" />
  <img src="https://github.com/user-attachments/assets/b6632552-60aa-4091-895d-a57ea80d8626" width="32%" />
</p>

<p align="center"><sub>Dance generation • Scoring • Side-by-side comparison</sub></p>
