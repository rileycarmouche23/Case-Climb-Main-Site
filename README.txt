CASE CLIMB - THE ASCENT

This folder is the whole website. There is nothing to build or install:
upload it to any web host and it runs.

FILES
index.html   the page (its styles and script are inside it)
assets/      logo, icons, sharing image, and the still pictures used when
             a visitor has "reduce motion" turned on
film/d/      the climb as 1,232 frames for laptops, desktops and tablets
film/m/      the same film cropped tall for phones

BEFORE YOU PUBLISH
1. Booking link. Open index.html in a text editor and search for
       var DEMO_URL = '';
   Paste your booking link between the quotes. Every "Book a demo" button
   then opens it. Until you do, the buttons scroll to the summit.
2. Sharing image. Search for og:image and change assets/share.jpg to the
   full address once the site is live, for example
       https://yourdomain.com/assets/share.jpg

PUBLISHING
GitHub Pages: create a repository, upload everything inside this folder
(keep the folders as they are), then Settings > Pages > deploy from the
main branch.
Netlify or Cloudflare Pages: drag this folder onto the dashboard.

Keep index.html, assets/ and film/ side by side. The page looks for them
next to itself.
