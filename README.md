# Get More6

- `index.html` — the Get More6 agency website.
- `detailer-template/` — a ready-made website for detailing clients.
- `detailing-leads.xlsx` — 50 detailer leads to contact.
- `ads/` — Meta ad images and ad copy for Get More6.

## Make a website for a new detailer

1. Copy the `detailer-template` folder and rename it after the business (e.g. `maddog-mobile-detailing`).
2. Open its `index.html` and edit only the `SITE = { ... }` block near the top:
   name, city, phone, email, Instagram, booking link, brand color, packages, prices, reviews and FAQs.
3. Remove anything that isn't true for that business (for example "Fully insured", or sample reviews).
   Use their real Google reviews.
4. Open the file in a browser to check it, then publish it (Netlify Drop, GitHub Pages or Vercel all work for free).

Tips:
- Leave `bookingUrl` empty and the "Book" buttons will open a text message to their phone.
- Add photo links to `gallery` and a `heroImage` to show their real work.

## Get More6 site settings

- Live site: https://getmore6marketing.com (served by GitHub Pages from this repo, so pushing to `main` updates it)
- Free trial: every "Start free trial" button scrolls to the GoHighLevel booking calendar on the homepage ("Getmore6 strategy call"). The Detailer Application questions show first, then the time picker. Change the questions or calendar in GoHighLevel, not here.
- Trial offer: 7 days free (client pays ad spend to Meta), then $500/month.
- Calendly (no longer on the site): https://calendly.com/getmore6marketing/30min
- Email: getmore6marketing@gmail.com
- Instagram: https://www.instagram.com/gettmore6/
- Founding offer: $500/month (ad spend paid separately by the client), first five clients. Edit the "Founding-client offer" section of index.html when the spots fill up.
