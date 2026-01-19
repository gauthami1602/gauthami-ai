# gauthami.ai - AI Digital Twin Portfolio

A personal portfolio website with an AI-powered chat that responds as me. Built to showcase my PM experience to recruiters in an interactive way.

## 🚀 Live Site
[gauthami.ai](https://gauthami.ai) (or your Netlify URL)

## ✨ Features
- Clean, warm portfolio design
- AI chat powered by Claude that knows my background
- Responds with my communication style (warm, genuine, humble)
- Mobile responsive
- Serverless backend (API key hidden from visitors)

## 🛠 Tech Stack
- HTML/CSS/React (single file)
- Netlify Functions (serverless backend)
- Claude API (AI responses)

## 📁 Project Structure
```
gauthami-ai/
├── index.html              # Main website
├── gauthami.jpg            # Profile photo
├── Resume_Gauthami_PM.pdf  # Resume download
├── netlify.toml            # Netlify configuration
├── netlify/
│   └── functions/
│       └── chat.js         # AI chat backend
└── README.md
```

## 🔧 Setup

### 1. Deploy to Netlify
- Connect this repo to Netlify
- Add environment variable: `CLAUDE_API_KEY` = your key

### 2. Get Claude API Key
- Go to [console.anthropic.com](https://console.anthropic.com)
- Create an API key
- Add it to Netlify's environment variables

### 3. Custom Domain (Optional)
- Add your domain in Netlify's Domain settings
- Update DNS records

## ✏️ Customization

### Change Website Content
Edit `index.html`:
- Intro text: Look for `<div class="intro-card">`
- Skills: Look for `<span class="skill-pill">`
- Colors: Look for `:root {` CSS variables

### Change AI Personality
Edit `netlify/functions/chat.js`:
- Find `GAUTHAMI_PERSONA`
- Update the personality, achievements, or topics

## 📬 Contact
- Email: hgauthamigopal@gmail.com
- LinkedIn: [linkedin.com/in/gauthamihgopal](https://linkedin.com/in/gauthamihgopal)

---
Built with ❤️ using Claude AI
