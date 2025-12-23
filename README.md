# Drywall Repair Landing Page

High-converting landing page for OnPoint Pros Drywall Repair service, designed for Google Ads traffic.

## Features

- ✅ Mobile-first responsive design
- ✅ Fast loading (no external dependencies)
- ✅ Clean, professional layout
- ✅ Multiple CTAs throughout
- ✅ Lead capture form
- ✅ Trust signals and testimonials
- ✅ Before/After gallery
- ✅ Sticky mobile CTA

## Deploy to GitHub Pages

### Option 1: Quick Deploy (via GitHub)

1. Create a new repository on GitHub:
   - Go to https://github.com/new
   - Name it `drywall-landing-page` (or any name)
   - Make it **Public**
   - Click "Create repository"

2. Push this code to GitHub:
   ```bash
   cd drywall-landing-page
   git remote add origin https://github.com/YOUR_USERNAME/drywall-landing-page.git
   git branch -M main
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to your repo → **Settings** → **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select **main** branch and **/ (root)**
   - Click **Save**

4. Your site will be live at:
   ```
   https://YOUR_USERNAME.github.io/drywall-landing-page/
   ```

### Option 2: Custom Domain (Recommended for Ads)

1. After enabling GitHub Pages, add a custom domain:
   - Go to Settings → Pages
   - Enter your custom domain (e.g., `drywall.onpointprostx.com`)
   - Click Save

2. Add DNS records at your domain provider:
   ```
   Type: CNAME
   Name: drywall (or @ for root)
   Value: YOUR_USERNAME.github.io
   ```

## Customization

### Update Phone Number
Search and replace `(512) 701-8183` and `+15127018183` with your actual phone number.

### Update Form Submission
The form currently uses Formspree. To make it work:
1. Go to https://formspree.io
2. Create a free account
3. Create a new form
4. Replace `your-form-id` in the form action with your actual Formspree ID

### Add Real Images
Replace the placeholder divs with actual `<img>` tags pointing to your photos:
- Hero image of technician
- Before/after gallery photos

## Performance Tips

- Page is fully self-contained (no external CSS/JS)
- Optimized for Core Web Vitals
- Mobile-first design
- No render-blocking resources

## License

© 2024 OnPoint Pros. All Rights Reserved.
