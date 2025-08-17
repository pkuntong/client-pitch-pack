# Designer Pitch Pack — Landing Page

A conversion-optimized landing page for selling your designer pitch pack digital product.

## Quick Setup

### 1. Replace Payment Link
- Open `index.html`
- Find the comment `<!-- PAYMENT LINK: Replace PAYMENT_LINK_HERE...`
- Replace `PAYMENT_LINK_HERE` with:
  - PayPal.me: `https://paypal.me/yourusername/10`
  - Gumroad: `https://gumroad.com/l/your-product`

### 2. Set Up Google Form for Email Capture
1. Create a Google Form at forms.google.com
2. Add fields: Email (required), Name, Design Niche, Biggest Challenge, Want Review (Yes/No)
3. Click Send → Embed → Copy iframe code
4. In `index.html`, find `<!-- GOOGLE FORM: Replace GOOGLE_FORM_EMBED_SRC_HERE...`
5. Replace `GOOGLE_FORM_EMBED_SRC_HERE` with the `src` URL from your iframe

### 3. Upload Your Product Files
- **Option A (Gumroad)**: Upload PDF + video, buyers get automatic download
- **Option B (Google Drive)**: Upload files, set sharing to "Anyone with link"
- Include: PDF with templates, Google Docs links, video walkthrough

### 4. Replace Preview Image
- Replace `assets/preview-image.svg` with a 1200x630px preview image
- Update Open Graph image URLs in the HTML head section

## Deploy to GitHub Pages
1. Create new GitHub repository
2. Upload all files to repository
3. Go to Settings → Pages
4. Select "Deploy from branch" → main branch
5. Your site will be live at `https://yourusername.github.io/repository-name`


## Email Autoresponder Setup
When someone requests a preview, use this auto-reply:

**Subject:** Your Designer Pitch Pack preview is here 🎨

**Body:** Thanks — your Designer Pitch Pack preview link is on the way. Quick start: personalize 2 lines, send to your warmest lead, follow up in 48 hours.

[Include preview PDF link]

Ready for the complete pack? Get it here: [PAYMENT_LINK_HERE]

## Testing Your Setup
1. Test payment link by making a small purchase yourself
2. Submit the Google Form to verify email capture works
3. Check mobile responsiveness on your phone
4. Verify all links work correctly

## Troubleshooting
If your page doesn't appear after 5-10 minutes: (1) **GitHub Pages**: Verify Pages is enabled in Settings → Pages, ensure branch is set to "main", confirm file is named exactly `index.html`. (2) **Netlify**: Re-drag the file if deployment failed, check deploy log for errors. (3) **Both**: Clear browser cache, try incognito mode, verify HTML opens locally.