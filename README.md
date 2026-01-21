# Mindful Moms Website - Kata Vajda

A professional, modern website for your holistic wellness business in Dubai.

## 📁 Project Structure

```
mindful-moms-website/
├── index.html          # Main website file
├── styles.css          # All styling
├── script.js           # Interactive features
└── README.md           # This file
```

## 🎨 Design Features

- **Warm, earthy color palette** - Professional yet approachable
- **Fully responsive** - Works on desktop, tablet, and mobile
- **Smooth scrolling navigation**
- **Clean, modern layout** with clear sections
- **Placeholder areas** for your photos and videos

## 📝 What You Need to Add

### 1. Images
Replace the placeholder boxes with your actual images:
- **Hero image**: Main inspiring photo (you training, running, or with clients)
- **About photo**: Professional headshot
- **Testimonial photos** (optional): Client photos

### 2. Contact Information
Update the contact section with:
- Your email address
- Phone number
- WhatsApp number
- Social media links (Instagram, Facebook, LinkedIn)

### 3. Testimonials
Add real client testimonials in the testimonials section. Format:
```html
<div class="testimonial-card">
    <div class="testimonial-text">
        <p>"Client's testimonial here..."</p>
    </div>
    <div class="testimonial-author">
        <strong>Client Name</strong>
        <span>Program: Package Name</span>
    </div>
</div>
```

### 4. Videos
Add your video testimonials or intro videos:
- Upload videos to YouTube or Vimeo
- Replace video placeholders with embed codes

## 🚀 How to View Locally

1. Navigate to the folder in Terminal:
```bash
cd ~/Python/mindful-moms-website
```

2. Open the website in your browser:
```bash
open index.html
```

Or simply double-click `index.html` in Finder.

## 🌐 How to Publish Online (FREE)

### Option 1: GitHub Pages (Recommended - FREE)

1. **Create a GitHub repository:**
   - Go to github.com/vajdbal
   - Click "New repository"
   - Name it: `mindful-moms-website`
   - Make it public
   - Don't initialize with README

2. **Push your code:**
```bash
cd ~/Python/mindful-moms-website
git init
git add .
git commit -m "Initial commit - Mindful Moms website"
git branch -M main
git remote add origin https://github.com/vajdbal/mindful-moms-website.git
git push -u origin main
```

3. **Enable GitHub Pages:**
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: Select "main" branch
   - Click Save
   - Your site will be live at: `https://vajdbal.github.io/mindful-moms-website/`

4. **Add custom domain (optional - ~$12/year):**
   - Buy domain (e.g., mindful-moms.com) from Namecheap, GoDaddy, etc.
   - In GitHub Pages settings, add your custom domain
   - Update DNS settings at your domain registrar

### Option 2: Netlify (Also FREE)

1. Go to netlify.com
2. Sign up with GitHub
3. Click "Add new site" → "Import an existing project"
4. Connect to your GitHub repo
5. Deploy! You'll get a free URL like: `mindful-moms.netlify.app`
6. Can add custom domain later

## 📧 Setting Up Contact Form

The contact form currently shows an alert. To make it actually send emails:

### Option A: Formspree (Easiest - FREE for 50 submissions/month)
1. Go to formspree.io and sign up
2. Create a new form, get your form ID
3. Replace the form in `index.html` with:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### Option B: EmailJS (FREE for 200 emails/month)
1. Sign up at emailjs.com
2. Follow their setup guide
3. Update the JavaScript in `script.js`

### Option C: Netlify Forms (if using Netlify)
Simply add `netlify` attribute to your form tag.

## 🎨 Customizing Colors

To change the color scheme, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #8B7355;      /* Main brown */
    --secondary-color: #C4A57B;    /* Light brown */
    --accent-color: #E8B4A0;       /* Peachy accent */
}
```

## 📱 Responsive Design

The website automatically adjusts for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## ✅ Before Going Live Checklist

- [ ] Add all your photos
- [ ] Update contact information
- [ ] Add real testimonials
- [ ] Update social media links
- [ ] Test contact form
- [ ] Add your email address in footer
- [ ] Review all text for accuracy
- [ ] Test on mobile device
- [ ] Check all links work

## 🛠 Need Help?

Common issues and solutions:

**Q: How do I add an image?**
A: Replace the placeholder div with:
```html
<img src="path/to/your/image.jpg" alt="Description">
```

**Q: How do I change text?**
A: Open `index.html` in any text editor and modify the content.

**Q: The site looks broken**
A: Make sure all three files (index.html, styles.css, script.js) are in the same folder.

## 📈 Next Steps

Once live, you can:
1. Connect Google Analytics to track visitors
2. Add booking calendar integration (Calendly, Acuity)
3. Set up email marketing (Mailchimp)
4. Add blog section for content marketing
5. Integrate payment system for package purchases

---

**Created:** January 2025  
**Built for:** Kata Vajda - Mindful Moms, Dubai
