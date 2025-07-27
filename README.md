# TRUECODER

**TRUECODER** is a application designed to **verify individuals' problem-solving achievements** and help **recruiters find authentic coding talent**.  
It connects to coding platforms like **Codeforces**, **LeetCode**, and more, then runs **automated verification checks**, **plagiarism detection**, and **behavioral analysis**.

---

## 🚀 What It Does

Debug Me solves a critical problem: **verifying coding credibility**.

- 🔗 Connects with coding platforms (Codeforces, LeetCode, CodeChef, etc.)
- ✅ Confirms profile ownership via custom verification methods
- 🔍 Detects code plagiarism using tools like **MOSS** or **JPlag**
- 📊 Analyzes behavior for suspicious activity (e.g. copy-paste abuse, fake spikes)
- 🧑‍💼 Offers recruiters a dashboard to search, filter, and shortlist verified candidates

---

## 🔧 Tech Stack

| Layer        | Technology                     |
|--------------|--------------------------------|
| Frontend     | React.js, Tailwind CSS, Axios  |
| Backend      | Node.js, Express.js, MongoDB   |
| Auth         | JWT, bcrypt                    |
| Scraping     | Puppeteer, Cheerio             |
| Plagiarism   | MOSS, JPlag (CLI integrated)   |
| Execution    | Judge0 API (optional)          |
| Deployment   | Docker, Vercel/Heroku support  |

---

## 🌐 Core Features

### 👤 User Side
- Connect multiple coding accounts
- Prove ownership via:
  - Solving a system-generated challenge
  - Adding a token to profile bio
- View your trust score and verified badge
- See analytics about your coding behavior

### 🧑‍💼 Recruiter Side
- Browse and search talent by platform, skill, badge
- View full profile including verified achievements
- Export profile to resume (PDF)
- Contact users for interviews (future)

### 🔐 Verification System
- Scrapes public problem-solving data
- Matches coding style for consistency
- Flags copied submissions using Moss or JPlag
- Detects time-based anomalies (e.g. multiple accounts, rapid solving)

---

## 📁 Folder Structure

truecoder/
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── utils/
│ │ ├── scrapers/
│ │ ├── plagiarism/
│ │ └── analyzers/
│ └── server.js
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ └── App.js
├── README.md


## 🧩 Contributing

Welcome contributors! 🎉  
If Want to suggest features, help me with creating this platform and become a member of this project you are welcomed.

## 📫 Contact Us

Got questions or ideas?  
📧 Email: [Pratham](diamond123erock@gmail.com)  
🌐 Website: still in progress...

---
> _“Don't tell them you're a great problem solver. Show them.”_
