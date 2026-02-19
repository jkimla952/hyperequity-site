# Hyperequity

**Own the Third Wave** — AI advisory and education by John Kim.

A clean, dark editorial static site rebuilt from the original Wix-hosted hyperequity.co.

## Stack

- **HTML/CSS/JS** — No framework, maximum performance
- **Google Fonts** — Instrument Serif + DM Sans
- **Vercel** — Static hosting with edge CDN

## Local Development

```bash
npm run dev
# Opens at http://localhost:3000
```

## Deploy to Vercel

### Option 1: Via GitHub (recommended)

1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import the GitHub repository
4. Vercel auto-detects the `vercel.json` config
5. Click **Deploy**

### Option 2: Via Vercel CLI

```bash
npm i -g vercel
vercel
```

## Custom Domain

After deploying to Vercel:

1. Go to **Project Settings → Domains**
2. Add `hyperequity.co`
3. Update DNS records as instructed by Vercel

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `public/index.html` | Hero + brand statement + services + origin |
| AI Academy | `public/ai-academy.html` | Course details and enrollment |
| About | `public/about.html` | John Kim's background |
| Connect | `public/connect.html` | Contact form |

## Design Tokens

| Token | Value |
|-------|-------|
| Primary Red | `#D62B20` |
| Background | `#0E1217` |
| Text | `#E8ECF1` |
| Display Font | Instrument Serif |
| Body Font | DM Sans |
