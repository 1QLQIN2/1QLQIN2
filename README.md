# Grand Portfolio Website

A premium one-page portfolio website with a polished color system, smooth animations, and social-ready metadata.

## Quick Start

Open `index.html` directly in your browser, or run a lightweight local server:

```bash
python3 -m http.server 8080
```

Then open: `http://localhost:8080`

## Customize

- Replace `Your Name`, email, and social links in `index.html`.
- Update case study cards with your real projects.
- Change colors in `styles.css` under `:root`.
- Set your final production URL in the Open Graph tag:
  - `<meta property="og:url" content="https://your-portfolio-url.com" />`

## Host & Share Across Socials

### Option 1: GitHub Pages (Free)

1. Create a GitHub repository and push this project.
2. In GitHub: **Settings → Pages**.
3. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main` and folder `/ (root)`
4. Save and wait for deployment.
5. Your site URL will look like:
   - `https://<username>.github.io/<repository-name>/`

### Option 2: Netlify (Free)

1. Go to Netlify and import your repository.
2. Build command: leave empty.
3. Publish directory: `.`
4. Deploy.

### Option 3: Vercel (Free)

1. Import your repository in Vercel.
2. Framework preset: `Other`.
3. Build settings: none required.
4. Deploy.

## Social Sharing Checklist

Before sharing the link on Instagram bio, X/Twitter, LinkedIn, and Facebook:

- Confirm your live URL is set in `og:url`.
- Add a custom preview image and include:
  - `og:image`
  - `twitter:image`
- Make sure title and description reflect your brand voice.

## Suggested Next Enhancements

- Add a real project gallery with screenshots.
- Add a contact form (Formspree or Netlify Forms).
- Connect a custom domain for better personal branding.
