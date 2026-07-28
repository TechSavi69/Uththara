# Uththara (උත්තර) — A/L Past-Paper Tutor 📚

Welcome to **Uththara**, an intelligent, beautiful, and completely free AI-powered tutor designed for Sri Lankan G.C.E. Advanced Level students. Uththara uses the Google Gemini API to analyze photos of past paper questions and teaches the student how to solve them step-by-step using a specialized 5-step pedagogy method.

## 🚀 Features

- **5-Step Pedagogy Engine:** Teaches the *method*, never just the final answer. (Read back, Topic, Plan, Steps, Check).
- **Multilingual Support:** Works natively in Sinhala (සිංහල), Tamil (தமிழ்), and English.
- **Image Recognition:** Snap a photo of a past paper and drag-and-drop it.
- **Live Streaming:** Answers are streamed real-time like chalk on a blackboard.
- **Mathematical Rendering:** Full KaTeX support for rendering complex equations and formulas.
- **Zero Cost (BYOK):** "Bring Your Own Key" architecture. Users securely provide their own free Gemini API key to use the app, meaning zero hosting/API costs for you!

## 🛠️ How to Run Locally

Since this is a lightweight Vanilla HTML/JS app, you can run it easily:

1. Clone or download this repository.
2. Open `uththara.html` in your browser. (Note: For the camera/clipboard to work best, use a local web server like `npx serve` or VS Code Live Server).
3. Paste your Gemini API key in the top right drawer.

## 💰 Monetization (Adsterra / Monetag)

I have already added **Direct Link** buttons to the UI under the Question Desk. 
To start earning:
1. Go to your Adsterra or Monetag dashboard.
2. Generate a "Direct Link".
3. Open `uththara.html` and search for `YOUR_ADSTERRA_DIRECT_LINK_HERE`.
4. Replace that text with your actual generated URL.

## 🔒 Security & Code Protection (Obfuscation)

Since this app is built entirely on the frontend (HTML/JS), anyone can view your source code (`Ctrl + U`). If you want to protect your "secret sauce" (the prompts and logic) from being easily copied, you can **obfuscate** the code before uploading to Vercel/Netlify.

I have created a script called `build.js` to do this for you automatically.

### How to protect your code:
1. Make sure you have [Node.js](https://nodejs.org/) installed on your computer.
2. Open the terminal in this folder and run: `npm install javascript-obfuscator`
3. Run the build script: `node build.js`
4. This will create a new file called `index.html`. 
5. **Upload `index.html` to Vercel/Netlify!** (Keep `uththara.html` safe on your PC for future edits).

## 🚀 How to Host on Vercel or Netlify
1. Create a free account on [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/).
2. Drag and drop your project folder (or connect your GitHub repository).
3. Vercel/Netlify will automatically give you a free, fast URL!

---
*Built with ❤️ for Sri Lankan Students.*
