# docs/requirements.md

## Functional
- Working nav on every page, desktop and mobile
## Functional
- Nav on every page linking all six pages; works on desktop and mobile
- Contact via mailto form on Visit

### Home
- Purpose: catch attention from kids and parents, lead them to Explore, Events and Visit
- Content: "Explore together" tagline, intro copy, 1000-exhibits paragraph, teaser cards
- Actions: go to Explore, go to Events, go to Visit

### Explore
- Purpose: overview of everything in the museum
- Content: For kids copy, Young Stars club, holiday clubs, summaries of exhibitions, events and facilities
- Actions: go to Exhibitions, go to Events, go to Visit

### Exhibitions
- Purpose: show the five permanent exhibition spaces
- Content: Cosmology, Evolution, Biology and Medicine, Robotics and AI, Ecology
- Actions: read, go to Events, go to Visit

### Events
- Purpose: temporary events and exhibitions
- Content: Prof Widnall lectures, Night in the Museum, Energetica on loan
- Actions: read, go to Visit for hours and location, email to book

### Visit
- Purpose: everything needed to plan a trip, plus about and contact
- Content: address, admission and tours, hours table, accessibility, café, shop, mission paragraph, contact form
- Actions: check hours, send email via form, go to Get Involved for group tours

### Get Involved
- Purpose: schools, researchers, supporters and volunteers
- Content: For teachers, Researchers, Support, Volunteer, Internships
- Actions: email to arrange a school visit, email to volunteer or donate
- Mimicked interactions (tickets, signup, etc.) → Coming Soon page
## Technical
- HTML + CSS only; no JS, no frameworks, no CSS/icon libraries (inline SVG for icons)
- Semantic, valid HTML; DRY CSS with :root variables; no unnecessary inline styling
- Layout: CSS Grid for page/section structure, Flexbox for components
- Mobile nav: CSS checkbox hack (hidden input + label toggle, `:checked` sibling selector), reused from the Rainy Days assignment
- Breakpoints (desktop-first): ≤768px mobile, 769–1199px tablet, ≥1200px desktop; container max-width 1200px
- Browsers: latest Chrome, Firefox, Safari, Edge on desktop; Safari iOS and Chrome Android
- Test viewports: 375, 768, 1024, 1440px
- Fonts: Google Fonts via <link>
- Hosting: GitHub Pages, deployed from main
- Tools: VS Code, Figma, Squoosh, W3C validator, WAVE
## Non-functional
- Fully responsive, no horizontal scrollbar
- Images ≤ ~200KB, fast load on slow connections
- WCAG: descriptive alt text, sufficient contrast, semantic HTML
- SEO: unique <title>, <meta name="description">, <h1> per page