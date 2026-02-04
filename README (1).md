# ✨ Studio Salon Odessa - Website

A stunning glassmorphic website for a boutique hair salon in Odessa, Ontario. Features a futuristic UI with email booking integration, Instagram gallery, testimonials, and full pricing tables.

![Studio Salon](https://img.shields.io/badge/Status-Ready%20to%20Deploy-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue)

---

## 🎨 Features

### Core Functionality
- **📧 Email Booking System** - Form submissions sent directly to `jordanch14@gmail.com`
- **📱 Fully Responsive** - Optimized for mobile, tablet, and desktop
- **⚡ Single-File Deployment** - No build process required

### Design Elements
- **Glassmorphism UI** - Frosted glass cards with backdrop blur
- **Animated Gradient Orbs** - Floating atmospheric background effects
- **Particle System** - 50+ floating particles for depth
- **Film Grain Overlay** - Subtle texture for premium feel
- **Gradient Text** - Rose gold to amber transitions

### Sections Included
| Section | Description |
|---------|-------------|
| **Hero** | Full-screen intro with CTAs and social proof |
| **Services** | 6 clickable service cards with booking integration |
| **Pricing** | 3-tier pricing tables (Cuts, Color, Treatments) |
| **Stats** | Animated counters (10+ years, 500+ clients, etc.) |
| **Testimonials** | 5 client reviews with star ratings |
| **Instagram** | 6-post gallery grid with hover effects |
| **About** | Studio story with feature highlights |
| **Contact** | Location, hours, and contact info |

---

## 🚀 Deployment

### Option 1: Netlify Drop (Recommended)
```bash
1. Visit https://app.netlify.com/drop
2. Drag & drop index.html
3. Done! Get your free URL
```

### Option 2: Vercel
```bash
1. Visit https://vercel.com
2. New Project → Upload index.html
3. Deploy
```

### Option 3: GitHub Pages
```bash
1. Create new repository
2. Upload index.html
3. Settings → Pages → Enable
4. Live at: username.github.io/repo-name
```

### Option 4: Traditional Hosting
Upload `index.html` to any web host (GoDaddy, Bluehost, Hostinger, etc.)

---

## ⚙️ Configuration

### Update Email Address
Find this line in the code and replace with your email:
```javascript
window.location.href = `mailto:jordanch14@gmail.com?subject=${subject}&body=${body}`;
```

### Update Contact Information
Search for these placeholders and update:
```html
<!-- Phone Number -->
(613) 555-0123

<!-- Email -->
jordanch14@gmail.com

<!-- Instagram Handle -->
@studiosalonodessa
```

### Update Social Links
```javascript
// Instagram
https://instagram.com/studiosalonodessa

// Facebook
https://facebook.com/studiosalonodessa

// TikTok
https://tiktok.com/@studiosalonodessa
```

### Update Pricing
Modify the `pricingData` object:
```javascript
const pricingData = {
  cuts: {
    name: 'Cuts & Styling',
    services: [
      { name: "Women's Cut & Style", price: '$65 - $85' },
      // Add more...
    ]
  },
  // ...
};
```

---

## 🎨 Customization

### Colors
The site uses a rose-gold and amber palette. Key color classes:
```css
/* Primary gradient */
from-rose-500 to-amber-500

/* Text accent */
text-rose-300

/* Background */
bg-zinc-950
```

### Fonts
```css
/* Display headings */
font-family: 'Cormorant Garamond', serif;

/* Body text */
font-family: 'Outfit', sans-serif;
```

### Adding Real Images
Replace emoji placeholders in the gallery:
```javascript
// Change this:
{ image: '💇‍♀️', likes: '2,847', caption: '...' }

// To this (requires code modification for img tags):
{ image: '/path/to/image.jpg', likes: '2,847', caption: '...' }
```

---

## 📁 File Structure

```
studio-salon-website/
├── index.html          # Complete website (single file)
├── README.md           # This file
└── assets/             # (Optional) Add images here
    ├── gallery/
    ├── testimonials/
    └── logo/
```

---

## 🛠️ Tech Stack

- **React 18** - UI framework (loaded via CDN)
- **Tailwind CSS** - Styling (loaded via CDN)
- **Babel** - JSX transformation (loaded via CDN)
- **Google Fonts** - Cormorant Garamond + Outfit

---

## 📱 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| Mobile Safari | ✅ Full |
| Chrome Mobile | ✅ Full |

---

## 📧 Booking System

The booking form uses `mailto:` links for simplicity:

**Advantages:**
- No backend required
- No hosting costs
- Works offline
- Direct to your inbox

**Email Format:**
```
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
     ✨ NEW BOOKING REQUEST ✨
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

CLIENT DETAILS
──────────────────────────────
Name: [Client Name]
Email: [Client Email]
Phone: [Client Phone]

APPOINTMENT DETAILS
──────────────────────────────
Service: [Selected Service]
Preferred Date: [Date]
Preferred Time: [Time]

ADDITIONAL NOTES
──────────────────────────────
[Client Message]
```

---

## 🔮 Future Enhancements

- [ ] Online payment integration (Stripe/Square)
- [ ] Calendar booking system (Calendly/Acuity)
- [ ] Real Instagram feed integration
- [ ] Google Reviews API integration
- [ ] Multi-language support
- [ ] Dark/Light mode toggle

---

## 📄 License

MIT License - Feel free to use and modify for your business.

---

## 🙋 Support

For questions or customization requests, contact the developer or submit an issue.

---

**Made with ✨ for Studio Salon Odessa**
