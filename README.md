# 🎤 SlideVo – AI Self-Presenting Slides

SlideVo is a web application that transforms PowerPoint presentations into **self-presenting slide decks** with **AI-generated narration**, **automatic slide transitions**, **interactive playback controls**, and **video export through screen recording**.

Users can simply upload a PPT file, generate narration, and watch the presentation run automatically—just like a virtual presenter.

🌐 **Live Demo (Public)**  
👉 https://spiko-presenter.netlify.app

---

## ✨ What You Can Do

- 🧠 Upload PowerPoint (PPT) files for presentation
- 🔊 Generate AI narration for each slide
- ▶️ Auto-play narration with automatic slide advancement
- ⏸️ Play, pause, next, and previous slide controls
- 🖥️ High-fidelity slide rendering using **OnlyOffice VM**
- 🎥 Record the presentation with system audio
- ⚡ No installation required – works directly in the browser

---

## 🧑‍💻 How to Use (Public App)

1. Open the live Netlify link
2. Upload your PPT file using **Choose File**
3. Enable **Enhance narration using AI** to generate narration via OpenAI
4. Click **⚡ Generate narration for all slides** and wait for completion
5. Enable **Auto play narration on slide change** for PowerPoint-like auto transitions
6. Click **Record**
   - Share the SlideVo window
   - Enable **Also share system sound**
7. Click **Play** to start narration
8. Slides will automatically present with narration
9. Click **Fullscreen** for an immersive presentation view
10. Use **Pause / Next / Previous** anytime to control playback

> 💡 Best experience on desktop browsers (Google Chrome recommended)

---

## 🎮 Presentation Controls

| Control | Function |
|-------|---------|
| ▶️ Play | Starts narration |
| ⏸️ Pause | Stops narration and enables manual navigation |
| ⏭️ Next | Move to next slide |
| ⏮️ Previous | Move to previous slide |
| 🔁 AutoPlay | Automatically advances slides after narration |
| 🎥 Record | Records the presentation with audio |

---

## 🔊 Audio & Browser Permissions

- Audio playback requires **user interaction** due to browser policies
- Ensure **system sound is enabled**
- If narration does not play:
  - Click anywhere on the page once
  - Check browser audio permissions
  - Confirm system sound sharing during recording

---

## 🛠️ Tech Overview

- **Frontend:** React + TypeScript
- **Slides Engine:** OnlyOffice VM (PPT rendering)
- **AI Narration:** OpenAI + Browser Text-to-Speech
- **Recording:** Browser Screen Recording API
- **Deployment:** Netlify

---

## 🌍 Availability

- Publicly accessible
- No login required
- No local setup needed

---

## 🚧 Current Limitations

- Mobile browser support is limited
- Direct video export is not available (screen recording required)
- Internet connection required for AI narration features

---

## 🛣️ Planned Enhancements

- ✨ Advanced AI-enhanced presentation text
- 🎯 Highlight active slide regions during narration
- 📤 Shareable presentation links
- 🎥 Direct MP4 video export

---

## 🤝 Feedback & Contributions

Feedback and contributions are welcome!  
If you find bugs or have feature ideas, feel free to open an issue or submit a pull request.

---

## 👨‍💻 Author

**Kisalay Pan**  
📧 kisalay.pan003@gmail.com  
🔗 LinkedIn: https://linkedin.com/in/kisalay-pan  
🐙 GitHub: https://github.com/kisalaypan001

---

⭐ If you like this project, consider starring the repository!
