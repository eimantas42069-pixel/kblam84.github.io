KBLAM84 — research section update
==================================

UPLOAD TO GITHUB
1. Open https://github.com/eimantas42069-pixel/kblam84.github.io
2. Choose Add file > Upload files.
3. Upload the six website files from this ZIP directly into the repository root:
   index.html
   leader-alus-5-1l.png
   leader.png
   donation-button.png
   sitemap.xml
   robots.txt
4. Commit the changes and allow GitHub Pages to deploy.
5. Leave your existing CNAME file alone. Do not upload the README unless you want it in the repository.
6. Visit https://kblam84.website/ and scroll down. Test the PayPal link.

WHAT CHANGED
- The original KBLAM84 stage, five bottle images, text, font and spinning
  CSS are preserved. The main image has non-visible width/height attributes.
- A wrapper makes the original first screen at least one viewport tall.
- A second section starts immediately beneath the first screen.
- The donation graphic is your exact supplied PNG, not a recreated image.
- The image has an opaque checkerboard background baked into the supplied file.
- The PayPal link opens in a new tab. No payments are processed by this site.
- Existing Google SEO metadata, canonical URL, social previews, JSON-LD,
  sitemap and robots.txt are retained.
- No autoplay, analytics, ad-network scripts or additional ads were added.

EASY SETTINGS
Open index.html in a plain text editor, such as Notepad. Search for:
  --spin-speed: 500ms;
Change 500ms to 200ms, 1000ms, 2000ms, etc. This controls all four corners.
  --research-top-padding: 16px;
Change this to adjust the gap at the start of section 2.
  --donation-image-width: 480px;
Change this to adjust the donation image's maximum displayed width.

To change the payment link, search for:
  https://www.paypal.com/paypalme/EimantasPuzinas
Replace only the URL inside href="...". Do not change the image src.
To edit the text, find the RESEARCH SECTION near the bottom of index.html.
To change the donation image, replace donation-button.png with a new PNG
using the same filename. The current checkerboard is part of the image.

GOOGLE SEARCH CONSOLE
Your homepage is already indexed according to your screenshot.
Check that these files load after deployment:
  https://kblam84.website/leader-alus-5-1l.png
  https://kblam84.website/sitemap.xml
  https://kblam84.website/robots.txt
Submit sitemap.xml in Search Console if you have not already done so.
Use URL Inspection > Test Live URL > Request Indexing once after meaningful
updates. In Performance, select Search type: Image to watch image impressions,
queries and clicks. No metadata or sitemap guarantees rankings or image inclusion.

PAYPAL
The button is a normal external link to the exact PayPal.Me URL you supplied.
Check the public payment page and your account's identity-verification status
before accepting tips. A link does not bypass PayPal account limitations.
The donation is described as supporting the site's creator, not a real charity.
