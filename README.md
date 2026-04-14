# GripMaster — GitHub Pages Website

A complete 5-page product website for the GripMaster Universal Jar & Bottle Opener.

## Pages
| File | Page |
|------|------|
| `index.html` | 🏠 Home — Hero, features, how-it-works preview, reviews strip |
| `about.html` | ℹ️ About — Origin story, mission, who it's for, specs |
| `how-it-works.html` | ⚙️ How It Works — Step-by-step, science, compatibility, tips |
| `reviews.html` | ⭐ Reviews — Rating summary, filter bar, full review cards |
| `support.html` | 🛟 Support — FAQ accordion, contact form, warranty & returns |
| `styles.css` | 🎨 Shared stylesheet for all pages |

## 🖼️ Adding Your Product Images

Place your product images in an `images/` folder:

```
images/
  product-cross-section.png   → Used on Home hero & How It Works
  product-in-use.png          → Used on Home "How It Works" section
```

Export your uploaded images and rename them to match. These are the two key images referenced in the HTML.

## 🚀 Deploy to GitHub Pages

1. Create a new GitHub repository (e.g. `gripmaster-website`)
2. Upload all files:
   - `index.html`
   - `about.html`
   - `how-it-works.html`
   - `reviews.html`
   - `support.html`
   - `styles.css`
   - `images/` folder with your photos
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose branch: `main`, folder: `/ (root)`
6. Click **Save**

Your site will be live at:
`https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## 🎨 Customizing

- **Brand name**: Search & replace `GripMaster` across all files
- **Colors**: Edit CSS variables in `styles.css` (`:root` block)
- **Amazon link**: Replace `https://amazon.com` with your actual product URL
- **Contact email**: Replace `support@gripmaster.com` with your real email
- **Reviews**: Edit the review cards in `reviews.html` with real customer feedback
