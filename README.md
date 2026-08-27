# Justus Okoro - Portfolio



Founder & Full-Stack Engineer. Building Quorum—a transparent voting platform for events and elections.

7+ years shipping across mobile, backend, frontend, and product.

## Quick Start

This is a static portfolio hosted on GitHub Pages.

### Local Development
```bash
# Serve locally (if you want to preview)
python -m http.server 8000
# or
npx http-server
```

Open `http://localhost:8000` in your browser.

### Deploy to GitHub Pages

1. Push this repo to GitHub (see instructions below)
2. Go to your repo Settings → Pages
3. Set source to `main` branch, `/root` directory
4. Your site will be live at `https://ReignnRule11.github.io/portfolio`

## How to Update

### Add a New Case Study
Open `index.html` and add a new `<article class="case-study">` section in the case-studies area:

```html
<article class="case-study">
    <h3>Project Name</h3>
    
    <div class="case-study-section">
        <strong>Problem</strong>
        <p>What friction existed? What did you notice?</p>
    </div>
    
    <div class="case-study-section">
        <strong>What I Built</strong>
        <p>Tech stack, your contribution, decisions made.</p>
    </div>
    
    <div class="case-study-section">
        <strong>Outcome</strong>
        <p>What shipped? What proof shows it worked?</p>
    </div>
</article>
```

Then commit and push.

## File Structure
- `index.html` - Main portfolio page (all-in-one)
- `README.md` - This file

That's it. Simple, fast, ships.
