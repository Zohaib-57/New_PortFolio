# Muhammad Zohaib Abbas — Portfolio

A modern, high-performance, responsive static portfolio website.

## 🚀 Key Features

- **Performance & Zero Bundling:** Pure semantic HTML5 + CSS3 + Vanilla JavaScript. No `npm install`, node modules, or build steps required.
- **Design & Typography:** Dark slate theme (`#0b0c10`) with neon lime accents (`#bcf34a`) utilizing `Manrope` and `DM Mono`.
- **Accessibility & UX:** Skip-to-content keyboard link, `:focus-visible` styling, responsive mobile drawer menu, motion-reduced support, and an interactive copy-to-clipboard button with toast feedback.
- **SEO & Social Cards:** Comprehensive Open Graph (OG), Twitter summary cards, and an embedded SVG Favicon (`ZA.`).
- **Visitor & Platform Detection:** Built-in visitor detection that captures operating systems, browsers, screen resolutions, and referring platforms (LinkedIn, GitHub, Twitter, Google, etc.).

---

## 🔔 How to Receive Real-time Visitor Notifications

The portfolio comes with an embedded visitor detector inside the `<script>` tag of [`index.html`](file:///home/muhammad-zohaib-abbas/Downloads/Muhammad-Zohaib-Abbas-Portfolio/index.html). Whenever anyone opens the portfolio, it detects:

- **Origin Platform:** LinkedIn, GitHub, Google, Twitter, or Direct.
- **Device & OS:** Windows, macOS, Linux, iOS, or Android.
- **Browser:** Chrome, Safari, Firefox, Edge.
- **Screen & Timezone:** Viewport resolution and local visitor timezone.

### Setting Up Free Instant Alerts (Discord Webhook):

1. In your Discord app, open any private server channel (or create a free private server).
2. Go to **Channel Settings** > **Integrations** > **Webhooks** > **New Webhook**.
3. Copy your **Webhook URL** (starts with `https://discord.com/api/webhooks/...`).
4. In [`index.html`](file:///home/muhammad-zohaib-abbas/Downloads/Muhammad-Zohaib-Abbas-Portfolio/index.html), locate line ~646:
   ```javascript
   const DISCORD_WEBHOOK_URL =
     "https://discord.com/api/webhooks/1573799992781439047/14_6MmsjhCgyT6lLxuvzBF3yLsAZjU_8RhlMt8ft8ShUIUHjr-cIHbW4vvz4JhiA9Mzh";
   ```
   Paste your URL inside the quotes:
   ```javascript
   const DISCORD_WEBHOOK_URL =
     "https://discord.com/api/webhooks/YOUR_ID/YOUR_TOKEN";
   ```
5. Now, whenever a recruiter, client, or visitor lands on your site, you will immediately receive an alert on your phone/desktop!

---

## 📈 Alternative: Free Web Analytics Dashboards

If you prefer a visual web dashboard with live world maps and retention graphs:

- **[PostHog](https://posthog.com/):** 1,000,000 free events/month. Offers session replay (see mouse movements & clicks), referrer tracking, and geography.
- **[Cloudflare Web Analytics](https://www.cloudflare.com/web-analytics/):** 100% free, privacy-first, zero cookies, no setup.
- **[Umami](https://umami.is/):** Clean, modern, open-source alternative to Google Analytics.

---

## 🌐 How to Deploy

Upload or push this folder to any static hosting provider:

- **GitHub Pages:** Push to a repository, go to **Settings > Pages**, choose the `main` branch root.
- **Vercel:** Drag and drop this folder at [vercel.com/new](https://vercel.com/new).
- **Netlify:** Drag and drop this folder at [app.netlify.com/drop](https://app.netlify.com/drop).
