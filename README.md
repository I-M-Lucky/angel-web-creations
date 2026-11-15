# Angel Web Creations

Deploy: upload this folder to Vercel (or any static host). Domain used everywhere: https://angel-web-creations.vercel.app

## Settings (top of the <script> in index.html)
- CH = 2.6           scroll length of each hero chapter (bigger = slower story)
- MIN_STAY = 2000    each hero chapter's text stays on screen at least this many ms
- WHATSAPP           the contact form opens a WhatsApp chat with this number. Kept out of the page text (split in the code so it is not shown or easy to scrape).
- EMAIL              "Or send by email" opens the visitor's mail app to this address. Also kept out of the page text.

## Fonts
fonts/primary.woff   "Angel Bandit Demo" - a DEMO font: digits and punctuation are watermarks, so it is limited to letters
                     (unicode-range in the CSS). Get the full licence to remove this limit.
fonts/secondary.woff "ANGEL FIRE"

## After deploying (SEO)
1. Google Search Console > add https://angel-web-creations.vercel.app > verify.
2. Submit https://angel-web-creations.vercel.app/sitemap.xml
3. URL Inspection > homepage > Request indexing.
4. Search keywords to expect over time: angel web creations, angel web, angel web creations vercel.
