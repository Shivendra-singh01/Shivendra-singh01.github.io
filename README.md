# Portfolio site

Plain HTML and CSS. No build step, no JavaScript, no third-party requests.

## Files
- index.html: home page
- privacy.html, terms.html: legal pages (linked from every footer)
- 404.html: not-found page
- favicon.svg, favicon.ico, apple-touch-icon.png: favicon set
- style.css: all styling, light and dark themes

## Before launch
- [ ] Connect your custom domain at your host (see below)
- [ ] Favicon: included and linked on every page
- [ ] No "Made with" badge: none exists in this code. Check your host does not inject one (some free plans do)
- [ ] Privacy policy and terms pages: included. Read them once and confirm they match your situation
- [ ] Optional: add a resume PDF link (your resume includes a phone number, so decide whether to publish it)

## Custom domain
GitHub Pages: push these files to a repo, enable Pages, add your domain under Settings > Pages, then create the DNS records GitHub shows you.
Cloudflare Pages or Netlify: upload the folder, then add the domain in the project's domain settings.
After the domain is live, add `<link rel="canonical" href="https://YOURDOMAIN/">` to each page head, and a sitemap.xml if you want one.
