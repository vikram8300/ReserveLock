# ReserveLock PWA

Irrevocable deposit platform for high-demand restaurants.

## Quick Deploy (Recommended)

### Option 1: Netlify Drop (Fastest - 30 seconds)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag this entire `reservelock-pwa` folder onto the page
3. Done! You'll get a URL like `https://random-name-123.netlify.app`

### Option 2: Vercel (1 minute)
1. Go to [vercel.com/new](https://vercel.com/new)
2. Click "Upload" and select this folder
3. Click "Deploy"

### Option 3: GitHub Pages (Free, permanent)
1. Create a new GitHub repo
2. Upload all files from this folder
3. Go to Settings → Pages → Select "main" branch
4. Your site will be at `https://yourusername.github.io/reponame`

## Install on iOS

Once hosted:
1. Open the URL in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. The app will work offline after first load

## Files Included

```
reservelock-pwa/
├── index.html      # Main app (all-in-one)
├── manifest.json   # PWA configuration
├── sw.js           # Service worker (offline support)
├── icon-192.png    # App icon (small)
├── icon-512.png    # App icon (large)
└── README.md       # This file
```

## Features

- **Landing Page** - Value prop, pricing, payment rails
- **Guest Booking** - Full reservation + deposit flow
- **Restaurant Dashboard** - Deposit management, analytics
- **Architecture Docs** - API specs, implementation code

## Tech Stack

- Vanilla JavaScript (no build step)
- Tailwind CSS (via CDN)
- Lucide Icons
- PWA-ready (installable, works offline)

## Customization

Edit `index.html` to customize:
- Restaurant name and branding
- Deposit amounts
- Payment methods
- Cancellation policies
