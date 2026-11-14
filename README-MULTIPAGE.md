# 313 Motorsports — Multi-page test build

Upload the **contents** of this folder to the root of a separate GitHub repository, then enable GitHub Pages (Settings > Pages > Deploy from a branch > main / root). Do not upload to the live repository until testing is complete.

Each page is a separate HTML file (`index.html`, `sponsor.html`, `services.html`, `paddock.html`, `gallery.html`, `new-to-karting.html`, `contact.html`). Page content is separately editable in `pages/*.js`; shared layout is in the HTML shells and `style.css`; shared functionality in `site.js`. For editing page copy, edit the matching `pages/*.js` file. This is a first conversion; a future pass can remove the shared header/footer duplication using a static-site generator.

**Important:** The original uploaded repository did not define a Paddock page despite having a navigation link. A basic placeholder was created; review its wording before launch. The new karting glossary and interest form are included. The original ZIP contained no PDF resources, so PDF downloads were not invented or linked.

**Test:** Navigate between all pages, use the gallery, open driver profiles, test the existing contact form and the new karting form, confirm delivery in Formspree, check phone layouts and external links. GitHub Pages URLs will use the test repository's name.
