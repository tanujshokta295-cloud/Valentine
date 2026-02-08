# Valentine Card Website - HTML Version

A beautiful, romantic Valentine's Day website where you can create personalized Valentine cards with photos and share them with your loved ones.

## Features

✨ **Simple HTML/CSS/JavaScript** - No build process, no dependencies
💕 **Romantic Design** - Elegant glassmorphism with floating hearts
📸 **Photo Upload** - Add 2 special photos
💌 **Personalized Message** - Include nickname and your story
🎊 **Interactive Experience** - Playful "No" button that dodges the cursor
🎉 **Confetti Animation** - Celebration when "Yes" is clicked
🔗 **Shareable Links** - Share via URL (no database needed)
📱 **Fully Responsive** - Works on mobile, tablet, and desktop

## Files

- `index.html` - Create page (upload photos, add story, generate Valentine card)
- `valentine.html` - Valentine display page (interactive question with dodging "No" button)

## How to Deploy to GitHub Pages

### Step 1: Push to GitHub

1. Create a new repository on GitHub
2. Push these files to your repository:

```bash
git init
git add index.html valentine.html
git commit -m "Initial commit - Valentine website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/valentine-card.git
git push -u origin main
```

### Step 2: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll to **Pages** section (left sidebar)
4. Under "Source", select **main** branch
5. Click **Save**
6. Wait 1-2 minutes for deployment

### Step 3: Access Your Website

Your website will be live at:
```
https://YOUR_USERNAME.github.io/valentine-card/
```

## How to Use

### Creating a Valentine Card

1. Open `index.html` in your browser or visit your GitHub Pages URL
2. Enter their nickname (e.g., "My Love", "Sunshine")
3. Write your story (how you met, what they mean to you, etc.)
4. Upload 2 photos
5. Click "Create Valentine Card"
6. Share the generated link with your Valentine!

### The Valentine Experience

When they open the link:
- They'll see your photos in a romantic stacked layout
- Read your heartfelt story
- Get asked "Will you be my Valentine?"
- The "No" button will dodge their cursor playfully
- When they click "Yes" - confetti celebration! 🎉

## Technical Details

- **No Backend Required** - All data encoded in URL
- **No Database** - Uses Base64 encoding for data sharing
- **Works Offline** - Can be opened directly from file system
- **Free Hosting** - GitHub Pages is completely free
- **CDN Libraries** - Uses canvas-confetti from CDN (no npm install)

## Customization

### Colors
Edit the CSS variables in the `<style>` section:
- Background: `#fff0f3` (soft pink)
- Primary: `#c9184a` (valentine red)
- Text: `#590d22` (dark red)

### Fonts
Using Google Fonts:
- Headings: Playfair Display (elegant serif)
- Body: Lato (clean sans-serif)
- Story: Great Vibes (romantic cursive)

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## No Dependencies!

Unlike the React version, this HTML version has:
- ❌ No Node.js
- ❌ No npm/yarn
- ❌ No build process
- ❌ No MongoDB
- ❌ No backend server
- ✅ Just pure HTML, CSS, and JavaScript!

## Deployment Cost

**100% FREE** - GitHub Pages is completely free for public repositories!

## License

Feel free to use, modify, and share this Valentine website! 💕

---

Made with 💖 for spreading love!
