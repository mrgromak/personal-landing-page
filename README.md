# Personal Landing Page Template

Welcome to your first web development project! This template is a starting point for creating your own personal landing page. You can customize it to be about yourself, or about something you're passionate about (a band, hobby, cause, etc.).

## What's Included

- **index.html** - The structure and content of your page
- **style.css** - The visual design and colors
- **script.js** - The interactive features (like the light/dark mode toggle)

## Understanding the Three Files

**HTML (index.html) - The Structure**
Think of HTML as the skeleton. It defines what content exists and how it's organized (headings, paragraphs, images, links).

**CSS (style.css) - The Style**
CSS is the appearance. It controls colors, fonts, spacing, and layout. Notice how everything is connected to the HTML through classes (like `class="hero"`).

**JavaScript (script.js) - The Behavior**
JavaScript makes things interactive. In this template, it powers the light/dark mode toggle. You don't need to modify it for now—just observe how it works!

## Customization Checklist

- [ ] Update the page title and tagline
- [ ] Replace the hero image with one that fits your topic
- [ ] Customize 2-3 text elements (About section, Highlights, etc.)
- [ ] Experiment with color variables (try both light and dark modes)
- [ ] Update at least one footer link

## How to Customize

### Update the Page Title and Tagline

**File:** `index.html`

1. Find the `<header>` section near the top
2. Change `<h1>Page Title</h1>` to your name or project name
3. Scroll down to the `<section class="hero">`
4. Update `<h2 class="tagline">` with your own description

### Replace the Hero Image

**File:** `index.html`

1. Find a photo that represents you or your topic
   - Free images: [Unsplash](https://unsplash.com)
   - Right-click an image → "Copy image address"
2. In the `<div class="hero-image">` section
3. Paste the URL into the `src=""` attribute, replacing the existing URL
4. Update the `alt=""` text to describe your image

### Customize Text Elements

**File:** `index.html`

**About Section:**
- Find `<section class="about">`
- Replace the two paragraphs with your own text
- Make it personal and interesting!

**Highlights Section:**
- Find `<section class="highlights">`
- Customize the four highlight items
- Ideas: favorite albums, books, games, hobbies, skills, current projects, interests
- Change the emoji icons to match your categories
- Update both the `<h4>` titles and `<p>` descriptions

### Experiment with Color Variables

**File:** `style.css`

1. Open `style.css` and find the `:root` section (around line 6)
2. Click on any color chip in Phoenix Code to open the color picker

**Light Mode Colors:**
```css
--bg-primary: #faf8f5;        /* Main background color */
--bg-secondary: #ffffff;      /* Card/section backgrounds */
--text-primary: #2d3142;      /* Main text color */
--text-secondary: #4f5d75;    /* Secondary text (slightly lighter) */
--accent-primary: #0d7377;    /* Main accent color (teal) */
--accent-secondary: #e76f51;  /* Secondary accent (coral) */
```

**Dark Mode Colors:**
- Scroll down to `[data-theme="dark"]` (around line 25)
- Customize the dark theme colors the same way

**Color Tips:**
- Use the color picker by clicking color chips in Phoenix Code
- Make sure text is readable against your background colors
- Try changing both light and dark mode colors

### Update Footer Links

**File:** `index.html`

1. Find the `<footer>` section near the bottom
2. Update the three links:
   - Change `href=""` to your actual URLs
   - Change the link text to match (Portfolio, GitHub, Instagram, etc.)
   - You can remove links you don't want to include

## Preview Your Changes

1. **Save your files** (Cmd/Ctrl + S)
2. **Open Live Preview** - Click the lightning bolt icon in Phoenix Code
3. **See updates in real-time** as you make changes
4. **Test the theme toggle** - Click ☀️/🌙 to see both light and dark modes

## Tips for Customization

- **Experiment!** Try changing things and see what happens. You can always undo (Cmd/Ctrl + Z)
- **Save often** - Get in the habit of saving after each change
- **Use the color picker** - Phoenix Code shows color chips next to hex codes in CSS
- **Keep it readable** - Make sure text colors contrast well with backgrounds
- **Have fun** - This is YOUR page. Make it reflect your personality or interests!

## What's Next?

Once you're happy with your customizations, you'll learn how to:
1. Save your changes using Git
2. Push to GitHub
3. Publish your page live on the internet with GitHub Pages

---

**Need help?** Ask your teacher or check the [Phoenix Code documentation](https://docs.phcode.dev/).
