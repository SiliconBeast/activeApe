# 🦍 activeApe  

activeApe is a gamified productivity Chrome extension that helps users stay focused by blocking distracting websites and requiring AI-powered physical challenges to unlock them.

Instead of simply restricting access, activeApe encourages discipline in a fun, interactive, competitive and engaging way. 

---

## 🚀 Features  

- ⏱️ *Focus Timer* – Set customizable focus sessions (e.g., 25 minutes)  
- 🚫 *Website Blocking* – Automatically blocks distracting websites during sessions  
- 💃 *Silly GIF Challenges* – Mimic movements shown on screen to regain access  
- 🤖 *AI Pose Tracking* – Real-time body movement detection  
- 🎮 *Gamification System* – Earn XP, level up, and track progress
- 👥 *Social Features* - Compete with friends with updated leaderboard feature - brag about how healthy you are becoming rather than flexing about how messed up your sleep cycle is
- 💰 *Ads Available* - Watch Ads to earn bonus XP and level up quickly (coming soon)
- 🍅 *Pomodoro Integration* - Adding Pomodoro technique integrated directly in app 

---

## 🛠️ Tech Stack  

- JavaScript
- HTML5  
- CSS3  
- Chrome Extension Manifest V3  
- Chrome Extension APIs  
- Chrome Storage API  
- Google MediaPipe Pose Landmarker (WASM + GPU acceleration)  
- Cosine Similarity Algorithm for movement comparison
- Firebase 

---

## 🧠 How It Works  

1. The user starts a focus session from the popup UI.  
2. Selected distracting websites are blocked during the session.  
3. If a blocked website is accessed, the user is redirected to a challenge page.  
4. The user must mimic a “Silly GIF” movement.  
5. MediaPipe tracks body pose in real time.  
6. Cosine similarity compares user movement to reference pose data.  
7. If similarity is ~65% or higher, the site unlocks.  
8. XP is awarded and progress is updated.  
9. Compete with friends on leaderboard
    
---

## 📂 Project Structure  


ActiveApe/
│
├── background.js        # Timer and blocking logic
├── popup/               # Extension popup UI
├── blocked/             # Blocked site page
├── challenge/           # AI movement challenge page
├── lib/                 # MediaPipe models
└── manifest.json        # Extension configuration


---

## ⚙️ Installation  

1. Clone the repository:
   bash
   git clone https://github.com/activeApe.git
   

2. Open Chrome and go to:
   
   chrome://extensions
   

3. Enable *Developer Mode* (top right corner).

4. Click *Load Unpacked*.

5. Select the activeApe project folder.

The extension should now be installed and ready to use.

---

## ⚔️ Challenges  

- Integrating real-time pose detection inside a Chrome extension  
- Handling MediaPipe WASM model performance
- Desinging a UI that looks appealing yet simple for efficient performance
- Designing accurate movement comparison logic  
- Managing state across background scripts and UI pages  

---

## 🔮 Future Improvements  

- More challenge variations  
- Adjustable difficulty levels  
- Productivity analytics dashboard  
- Leaderboards and social features  
- Improved pose smoothing and scoring accuracy  
- Monitization via ads
  
---

## 📌 License  

This project was developed for educational and hackathon purposes and can't be forked without permission. Copyright 2026
