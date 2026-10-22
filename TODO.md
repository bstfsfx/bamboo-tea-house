# TODO

- [x] **Reference-matched identity, header, and responsive navigation**
  - Reproduce the supplied reference’s warm ivory, deep forest-green, and charcoal palette; restrained spacing; image-led composition; section order; and refined Japanese/Traditional Chinese-inspired typography.
  - Include a slim header with brand identity and usable section navigation; simplify the menu on mobile.
  - Preserve the reference’s visual hierarchy and adapt layout and image crops across desktop, tablet, and mobile.

- [x] **Bamboo-path and tea-house hero**
  - Reproduce an immersive bamboo-path/tea-house hero with a Traditional Chinese headline, supporting copy, and two clear, usable calls to action.
  - Reuse or crop suitable photography embedded in the supplied reference image.

- [x] **Featured tea products**
  - Present tea cards with photographs, product names, descriptions, and prices, matching the reference’s featured-product section.
  - Make product cards clickable/interactive.

- [x] **Brand story**
  - Reproduce the reference’s split photographic-and-copy layout with Traditional Chinese storytelling about Arashiyama, the bamboo path, and tea.

- [x] **Tea-house experiences**
  - Present experience cards that introduce different tea or space experiences and provide usable interactive entry points.

- [x] **Shop location and directions**
  - Show the tea house’s address, operating information, and a way to get directions in the location section.
  - Keep the location/map presentation consistent with the supplied reference.

- [x] **Footer and complete landing-page flow**
  - Provide a deep-green footer containing brand, navigation, and basic contact information.
  - Keep the page’s section sequence consistent with the supplied reference: header, hero, featured teas, brand story, experiences/location, and footer.

- [x] **Four-language internationalization**
  - Provide Japanese, Traditional Chinese, Simplified Chinese, and English versions of the website’s visible navigation, headings, descriptions, product and experience details, location information, calls to action, and footer.
  - Make the language selector switch the displayed language and document language, and remember the visitor’s selection across visits.

- [x] **Expand the featured-tea photo grid from four to eight teas**
  - Add four distinct tea cards with their own tea photography, names, descriptions, prices, and usable links to the existing “Guest favorites / Kyoto teas, thoughtfully selected” section.
  - Provide localized names, descriptions, and image alt text for Japanese, Traditional Chinese, Simplified Chinese, and English.
  - Keep the eight-card grid readable and responsive on desktop, tablet, and mobile.

- [x] **Localize menu currency by language**
  - Display menu amounts in NTD for Traditional Chinese, RMB for Simplified Chinese, USD for English, and Japanese yen (JPY/¥) for Japanese.
  - Convert from the existing NTD base amounts using a clearly documented indicative rate snapshot and round amounts appropriately for each displayed currency.

- [x] **Add French and Spanish internationalization**
  - Provide French and Spanish translations for visible navigation, headings, descriptions, products, image alt text, search, experiences, location information, calls to action, footer, and page metadata.
  - Recognize French and Spanish browser-language preferences, update the document language, and remember the visitor’s selected locale.
  - Display French and Spanish menu prices in euros, converted from the NTD base using a documented indicative rate snapshot.

- [x] **Revise the language switcher for six locales**
  - Offer Japanese, Traditional Chinese, Simplified Chinese, English, French, and Spanish in the native language names, with an accessible, compact control that remains usable at desktop and mobile widths.

- [x] **Save all website photos and images locally**
  - Copy the page’s photos, map, logo/favicon, and social-preview image into a project-local `public/images/` directory.
  - Update website image references to use those local files and verify each referenced asset is present and served successfully.

- [x] **Add subtle hero-background parallax**
  - Move only the bamboo-path hero background at a slower rate than page scrolling; keep hero copy and calls to action stationary and readable.
  - Keep motion restrained and disable the effect when the visitor prefers reduced motion.

- [ ] **Add soft section-reveal effects**
  - Fade major content groups upward as they enter view, with a brief stagger for tea cards.
  - Keep content in the document and reveal it on keyboard focus; disable the motion for reduced-motion preferences and when IntersectionObserver is unavailable.
