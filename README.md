# Your Friend in China — Landing Page

> We handle the sourcing. You handle the sales.

A clean, conversion-focused landing page for a China sourcing + QC + shipping service targeting US Shopify store owners.

## 🚀 Deploy to Vercel (30 seconds)

1. **Push to GitHub**
   ```bash
   cd landing-page
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/landing-page.git
   git push -u origin main
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repo
   - Click "Deploy" — done!

That's it. Vercel will auto-detect it's a static HTML site and deploy it instantly.

## 📁 Project Structure

```
landing-page/
├── index.html    # The complete landing page
└── README.md     # This file
```

## ✏️ Customizing

### Brand & Contact
Search and replace these values in `index.html`:

| What | Replace With |
|------|-------------|
| `hi@yourfriendinchina.com` | Your actual email |
| `Your Friend in China` | Your brand name |
| `500+ shipments handled` | Your real stats |
| `Marcus T. / Sarah L. / James K.` | Real testimonials |
| `Atlanta GA / Austin TX / Chicago IL` | Real locations |

### Colors
Edit the CSS variables at the top of `<style>`:

```css
:root {
  --purple: #a78bfa;       /* Primary accent */
  --green: #4ade80;        /* Success / checkmarks */
  --yellow: #fbbf24;        /* Stars / warnings */
  --bg: #0a0a0f;            /* Background */
  --surface: #12121a;        /* Card backgrounds */
}
```

### Pricing
Edit the pricing cards in the `#pricing` section. All prices and features are plain HTML.

## 🎯 Sections

- **Hero** — Brand + tagline + social proof stats
- **Pain Points** — 6 cards showing problems we solve
- **How It Works** — 4-step process
- **Pricing** — 3 tiers (Starter $49 / Growth $149 / Pro $399)
- **Testimonials** — 3 real-sounding quotes
- **FAQ** — 7 common questions
- **CTA** — Final call to action

## 📊 Analytics

Add your tracking code to the `<head>` section:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

Or add a Vercel Analytics snippet for built-in analytics.

## 🌐 Custom Domain

After deploying to Vercel:
1. Go to Project Settings → Domains
2. Add your custom domain (e.g., `yourfriendinchina.com`)
3. Vercel handles SSL automatically

---

*Built with vanilla HTML/CSS/JS — no build step required.*
