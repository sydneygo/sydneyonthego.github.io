# Sydney Arin Go - Portfolio Website

A clean, professional portfolio website for content strategist Sydney Arin Go.

## Quick Setup Instructions

### 1. Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click the "+" icon in the top right and select "New repository"
3. Name it: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - Example: If your username is `sydneyaringo`, name it `sydneyaringo.github.io`
4. Make it **Public**
5. **Do NOT** initialize with README
6. Click "Create repository"

### 2. Upload Your Files
1. On the repository page, click "uploading an existing file"
2. Drag and drop ALL these files:
   - `index.html`
   - `blog.html`
   - `resume.html`
   - `styles.css`
   - `headshot.png`
   - `README.md`
3. Scroll down and click "Commit changes"

### 3. Enable GitHub Pages
1. In your repository, click "Settings"
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes for GitHub to build your site
6. Your site will be live at: `https://your-username.github.io`

## How to Update Your Site

### Update Content
1. Go to your repository on GitHub
2. Click on the file you want to edit (e.g., `index.html`)
3. Click the pencil icon (Edit this file)
4. Make your changes
5. Scroll down and click "Commit changes"
6. Changes will appear on your live site in 1-2 minutes

### Add Blog Posts
1. Edit `blog.html`
2. Replace the "coming soon" section with blog post HTML
3. Use this template for each post:

```html
<article class="blog-post">
    <h3><a href="blog/post-title.html">Your Post Title</a></h3>
    <p class="blog-date">October 17, 2025</p>
    <p>A brief excerpt of your post...</p>
    <a href="blog/post-title.html" class="read-more">Read more →</a>
</article>
```

### Update Your Photo
1. Upload a new `headshot.png` file to replace the existing one
2. Make sure it's named exactly `headshot.png`

## File Structure

```
├── index.html          # Homepage
├── blog.html          # Blog listing page
├── resume.html        # Resume page
├── styles.css         # All styling
├── headshot.png       # Your profile photo
└── README.md          # This file
```

## Customization Tips

### Change Colors
Edit `styles.css` and search for these color codes:
- `#333` - Dark text/buttons
- `#666` - Medium gray text
- `#f5f7fa` - Light background
- Change them to your preferred colors

### Add More Sections
Copy and paste existing `<section>` blocks in the HTML files and modify the content.

### Make it Your Own
This site is built with vanilla HTML/CSS - no frameworks, no build process. Edit directly in GitHub or download the files to edit locally.

## Need Help?

- GitHub Pages Documentation: https://docs.github.com/en/pages
- Contact Sydney: sydneyaringo@gmail.com

## License

© 2025 Sydney Arin Go. All rights reserved.
