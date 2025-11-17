# Personal Website Template - Chi's Sweet Home Style 🐱

A cute, manga-inspired personal academic website with soft colors and smooth scrolling.

## Colors Used
- **Light Blue** (#b8e6f5) - Pages 1 & 4
- **Light Green** (#c8e6c9) - Pages 2 & 5  
- **Light Gray** (#e0e0e0) - Pages 3 & 6

## How to Use This Template

### Step 1: Set Up Your GitHub Repository
1. Go to GitHub and create a new repository named `silbunsa.github.io`
2. Make sure it's set to **Public**
3. Initialize with a README (optional)

### Step 2: Add Your Files
1. Upload these three files to your repository:
   - `index.html`
   - `styles.css`
   - `script.js`

### Step 3: Customize Your Content

#### In `index.html`, replace the placeholders:

**About Section (Page 1):**
- Replace `your-photo.jpg` with your actual photo filename
- Update "Your Name" with your name
- Write your bio in the bio-text section
- Update email, GitHub, LinkedIn, and CV links

**Research Section (Page 2):**
- Add your research areas (e.g., Industrial AI, Medical AI, CEN Architecture)
- Describe each research interest

**Projects Section (Page 3):**
- Add your projects (EcoSorter, Cardiac Arrhythmia Detection, etc.)
- Add project descriptions and tags
- Link to GitHub repos or project pages

**Publications Section (Page 4):**
- List your publications with authors, venues, and years
- Add links to PDFs, code, slides as needed

**Teaching Section (Page 5):**
- Add courses you've taught or TA'd
- Include course descriptions and time periods

**Contact Section (Page 6):**
- Update your email, institution, and location
- Add your social media links

### Step 4: Add Your Photo
1. Upload your photo to the repository
2. Name it something like `profile-photo.jpg`
3. Update the `src="your-photo.jpg"` in index.html to match your filename

### Step 5: Go Live!
1. Go to your repository Settings
2. Scroll to "GitHub Pages"
3. Under "Source," select the main branch
4. Click Save
5. Your site will be live at `https://silbunsa.github.io` in a few minutes!

## Customization Tips

### Change Colors
In `styles.css`, modify the `:root` section:
```css
:root {
    --light-blue: #b8e6f5;    /* Change these hex codes */
    --light-green: #c8e6c9;
    --light-gray: #e0e0e0;
}
```

### Add More Sections
Copy any `<section>` block and change:
- The `id` attribute
- The color class (blue-page, green-page, or gray-page)
- The page number
- Add a corresponding nav link

### Fonts
To use a different font, add a Google Fonts link in the `<head>` of index.html:
```html
<link href="https://fonts.googleapis.com/css2?family=Comic+Neue:wght@400;700&display=swap" rel="stylesheet">
```

Then update the font-family in styles.css.

## Preview Locally
To preview before uploading:
1. Open `index.html` in your web browser
2. Test the navigation and scrolling
3. Make sure all your content displays correctly

## Need Help?
- GitHub Pages Documentation: https://pages.github.com/
- Contact me if you have questions!

---

Enjoy your new website! 🌟
