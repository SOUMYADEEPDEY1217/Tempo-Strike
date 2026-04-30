# ⚡ Tempo Strike

**Tempo Strike** is a high-octane, browser-based rhythm game where your body is the controller. Using advanced hand-tracking AI, you slash through "Sparks" in a 3D environment to the beat of the music.

![App Preview Placeholder](https://via.placeholder.com/800x450.png?text=Tempo+Strike+Gameplay+Preview)

## 🚀 Features

- **AI-Powered Hand Tracking:** Built with [MediaPipe](https://google.github.io/mediapipe/), allowing for real-time interaction without the need for VR controllers.
- **Immersive 3D Experience:** Rendered using [React Three Fiber](https://r3f.docs.pmnd.rs/) and [Three.js](https://threejs.org/).
- **Dynamic HUD:** Real-time scoring, combo systems, multipliers, and health tracking.
- **Haptic Feedback:** Physical vibration support for hit impacts (on supported devices).
- **Webcam Integration:** Low-latency video processing for precise gesture detection.

## 🛠️ Tech Stack

- **Framework:** React 19
- **3D Engine:** React Three Fiber (@react-three/fiber, @react-three/drei)
- **AI/Vision:** MediaPipe Hands (@mediapipe/tasks-vision)
- **Styling:** Tailwind CSS
- **Bundler:** Vite
- **Icons:** Lucide React

## 🎮 How to Play

1. **Setup:** Ensure you have a working webcam and enough light.
2. **Positioning:** Stand back so your hands are clearly visible in the webcam preview at the bottom left.
3. **Action:** Slash the incoming "Sparks" using your left (red) and right (blue) virtual sabers.
4. **Scoring:** The more accurate your cuts and the higher your combo, the more points you earn. Keep your "System Integrity" (health) up by not missing notes!

## 📦 Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/tempo-strike.git
   cd tempo-strike
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```

4. **Open in browser:**
   Navigate to `http://localhost:3000`.

## 📂 Project Structure

- `/src/components`: React components for the UI and 3D scenes.
- `/src/hooks`: Custom hooks (e.g., `useMediaPipe` for hand tracking logic).
- `/src/constants.ts`: Game configuration, beatmaps, and asset URLs.
- `/src/types.ts`: TypeScript interfaces and enums.

## 📜 License

This project is licensed under the Apache-2.0 License. See the [LICENSE](LICENSE) file for details.

## 🤝 Credits

- Originally created by Soumyadeep Dey
- Built with Google AI Studio.

---

*Note: For the best experience, use a modern browser like Chrome or Edge and ensure your webcam is positioned to see your full upper body.*
