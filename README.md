# Developer Portfolio (Vite + React)

This repository contains a Vite + React developer portfolio with a serverless chat API under `api/chat.js`.

Quick local setup

1. Install dependencies

```bash
npm install
```

2. Copy env example and fill keys

```bash
cp .env.example .env
# edit .env and add GROQ_API_KEY
```

3. Start local API server (optional, used for local testing of `/api/chat`)

```bash
npm run start-api
```

4. Start frontend dev server

```bash
npm run dev
```

Deployment to Vercel

1. Push your repository to GitHub

```bash
git init
git add .
git commit -m "Prepare for Vercel deployment"
git remote add origin git@github.com:YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

2. On Vercel:
- Create a new project → Import from GitHub → select this repository
- Set Environment Variables (Project Settings > Environment Variables):
  - `GROQ_API_KEY` = (your Groq API key)
- Build Command: `npm run build`
- Output Directory: `dist`

3. Deploy and verify `https://<your-project>.vercel.app/api/chat` works.

Notes
- Do NOT commit your `.env` file. Use environment variables in Vercel for secrets.
- `server.js` is for local testing only and is ignored for deployment using `.vercelignore`.
# My Portfolio Wesbite - Overview 🚀

If you are copying this code or forking this repo, please give a credit of my name :(

## Instructions 🛠️

I have modified the gsap club plugins with the trial plugins, but with the trial plugin you cannot host it🔴. So for Club plugins, Check out here: https://gsap.com/docs/v3/Installation/

**Techstack** - React, TypeScript, GSAP, ThreeJS, WebGL, HTML, Css, JavaScript

![Protfolio-Preview](https://github.com/user-attachments/assets/3c4557e7-6392-4928-b8a9-7b2476ef4edd)

## License

This project is open source and available under the [MIT License](LICENSE).
