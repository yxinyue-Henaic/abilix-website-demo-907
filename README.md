# Abilix PartnerX Website - CH820

A dependency-free, responsive Chinese/English implementation of the Abilix PartnerX website. Chinese is the default language; use the globe button to the right of “About Abilix / 关于能力风暴” to switch languages instantly.

## Run

1. Install Node.js 18 or later.
2. Run `npm start` in this folder.
3. Open `http://localhost:4173`.

You can also open `index.html` directly in Chrome. Make sure the filename extension remains `.html` (not `.heml`). Navigation uses hash routes, so no server rewrites are required. All text files use UTF-8 with BOM for reliable local-file decoding.

## Pages and interactions

- Home: navigation, CTAs, solution links and product carousel.
- Products: a two-path gateway that separates Educational Robots from AI Robots before users enter either catalog.
- Educational Robots: learning-stage filters, product-family cards, education-method context, a four-level competition pathway and model-specific detail routes.
- AI Robots: a standalone Xiaoxing experience covering AI capabilities, the six-course system, the learning loop and a reserved competition channel.
- Curriculum: interactive learning-path accordion.
- WER: external-site CTA opens in a new tab.
- Solutions: Introduction / Explore four environments tabs, the original four accessible solution scenes, and the five educational functions.
- Resources: reordered resource landing cards, searchable two-page FAQ accordions, and the searchable/filterable three-page official download library.
- Xiaoxing: image gallery, quantity control, add-to-bag feedback and recommendations.
- Language: complete Chinese/English switching for navigation, page copy, buttons, labels, filters, FAQ, downloads, feedback messages and accessibility text.

Source artwork was copied at build time from the supplied website and Page Template packages. FAQ and download content comes from the Abilix English support pages referenced in the 0820 brief.
