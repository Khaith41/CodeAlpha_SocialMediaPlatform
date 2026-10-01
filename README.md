# CodeAlpha_SocialMediaPlatform (Task 2: Social Media Platform)

Full-Stack Mini Social Media Application built for the **CodeAlpha Full Stack Development Internship (Task 2)**.

## ✨ Features Implemented
- **User Profiles**: View & edit display name, handle, bio, and avatar, plus live Post/Follower/Following counters and instant profile switching.
- **Posts & Comments**: Create posts with text and optional media attachments, and reply with comments on any post.
- **Like & Follow System**: Like/unlike posts with real-time counter updates, follow/unfollow creators, and switch between the **For You** and **Following** feeds.

## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3, Vanilla JavaScript (`public/index.html`, `public/styles.css`, `public/app.js`)
- **Backend**: Node.js & Express.js (`server.js`)
- **Database**: Persistent JSON Store (`database.json`) for Users, Posts, Comments, and Followers

## 🚀 How to Run

### Option 1: Run Full-Stack with Node.js & Express
```bash
cd CodeAlpha_SocialMediaPlatform
npm install
npm start
```
Then open `http://localhost:4000` in your browser.

### Option 2: Instant Browser Preview (Zero Setup)
Open `public/index.html` directly in any web browser. The frontend automatically falls back to `localStorage` persistence if the Express server is not running.
