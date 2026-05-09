# Airsell — Deploy to airsell.biz

## What's in this folder

airsell/
├── index.html          ← the webpage shell
├── package.json        ← project settings
├── vite.config.js      ← build settings
├── vercel.json         ← hosting settings
├── public/
│   └── favicon.svg     ← browser tab icon
└── src/
    ├── main.jsx        ← app entry point
    └── App.jsx         ← the full Airsell listing app

## How to deploy (3 steps)

### Step 1 — Go to vercel.com
- Create a free account (sign up with Google or email)

### Step 2 — Deploy the folder
- Click "Add New Project"
- Click "Deploy from your computer" or drag this entire folder in
- Click Deploy — takes about 60 seconds

### Step 3 — Connect airsell.biz
- In your project, go to Settings → Domains
- Type: airsell.biz → Add
- Vercel shows you 2 DNS records to copy
- Log into your domain registrar (GoDaddy/Namecheap/etc)
- Go to DNS settings → paste the 2 records Vercel gave you
- Wait 10–30 min → airsell.biz is live

## That's it.
