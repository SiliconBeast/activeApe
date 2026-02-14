# 🦍 activeApe  

*(Gen Alpha desciption at the end)*

activeApe is a gamified productivity Chrome extension that helps users stay focused by setting timer based usage to website and requiring AI-powered physical challenges to unlock them - this makes our product fun, distracting (in a healthier way) and stands out as a perfect app for non-uncs.

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

```text
ActiveApe/
│
├── background.js        # Timer and blocking logic
├── popup/               # Extension popup UI
├── blocked/             # Blocked site page
├── challenge/           # AI movement challenge page
├── lib/                 # MediaPipe models
└── manifest.json        # Extension configuration

```
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

"Gen Alpha"-ed description
## 🦍 activeApe: The Ultimate Aura Booster

**activeApe** is the first productivity Chrome extension that isn't mid. We’re stopping the infinite scroll and the brain rot by locking your distractions behind real-life side quests. If you want to get back to the 10-hour "Sigma Male Core" loops on YouTube, you’re gonna have to move for it.

No more unc-coded screen time limits. We’re gamifying your focus so you can lock in, stack XP, and stop being a professional yapper.

---

## 🚀 The Glow Up (Features)

* ⏱️ **The Lock In Timer** – Set your focus sessions so you don’t lose your streak.
* 🚫 **Opp Stopper** – Automatically blocks the sites that are killing your productivity.
* 💃 **Silly GIF Emote Challenges** – To unlock your site, you have to mimic the GIF on screen. It’s basically TikTok dances but for your grades.
* 🤖 **AI Pose Tracking** – Real-time body detection. If your form is an L, you stay blocked.
* 🎮 **XP & Leveling** – Stop flexing your messed up sleep schedule and start flexing your level.
* 👥 **The Leaderboard** – Compete with the squad. Brag about your health instead of how much you’ve rotted.
* 💰 **Infinite Money Glitch (Coming Soon)** – Watch ads to farm bonus XP and level up your profile faster.
* 🍅 **Pomodoro Mode** – Standard focus intervals, but with more main character energy.

---

## 🛠️ The Build (Tech Stack)

* JavaScript, HTML5, CSS3 (The OG trio)
* Chrome Extension Manifest V3 (Keeping it modern)
* **Google MediaPipe Pose Landmarker** (High-tier AI tracking)
* **Cosine Similarity Algorithm** – Maths to make sure your emotes are actually valid:


* **Firebase** – For the cloud and the vibes.

---

## 🧠 The Lore (How It Works)

1. You start a session in the UI. **Lock in starts now.**
2. Your "guilty pleasure" sites get sent to the shadow realm (blocked).
3. If you try to sneak onto a blocked site, you get redirected to the **Challenge Arena**.
4. You have to hit a "Silly GIF" movement in front of the camera.
5. MediaPipe tracks your bones in real-time.
6. If your movement is a **65% match or higher**, you’ve cooked. Site unlocked.
7. Earn XP, update your rank, and mog the leaderboard.

---

## 📂 Project Tree

```text
ActiveApe/
│
├── background.js        # The brain (Timer + Blocking)
├── popup/               # The drip (UI)
├── blocked/             # The "Go touch grass" page
├── challenge/           # Where the AI judges your emotes
├── lib/                 # The secret sauce (MediaPipe)
└── manifest.json        # The ID card

```

---

## ⚙️ How to Join the Tribe

1. Clone the repo: `git clone https://github.com/activeApe.git`
2. Go to `chrome://extensions` (don't be a bot, use the URL bar).
3. Toggle **Developer Mode** on.
4. Hit **Load Unpacked**.
5. Select the `activeApe` folder and prepare to lock in.

---

## ⚔️ The Final Bosses (Challenges)

* Getting AI pose detection to run inside a browser without making your PC sound like a jet engine.
* Making sure the UI looks clean and not like it was made in 2012.
* Coding the math so the AI knows when you’re actually dancing vs. just flailing.
* Managing the state across the extension so it doesn't forget you're mid-session.

---

## 🔮 Roadmap to 5-Star Aura

* More emote variations (including Griddy support).
* Difficulty levels: From "Noob" to "Gym Rat."
* Analytics dashboard to see your productivity peak.
* Official monetization so you can flex your premium status.

---

## 📌 The Fine Print

Developed for the grind (hackathons). No forking without permission or you lose 1,000 aura points. **Copyright 2026.**

---

