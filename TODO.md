# TODO.md

Repository purpose
- Public portfolio for Valto Loikkanen: AI-native product builder, UX-driven system architect, multidisciplinary creator.
- Primary goals: hiring (Product Engineer / AI-native builder), credibility for advisory/speaking/coaching, showcase selected private work.

Implementation checklist
- [ ] Create repository (recommended names: `valto-loikkanen.github.io` or `valtoai-portfolio` or `portfolio`)
- [ ] Choose GitHub Pages publishing method (plain static HTML/CSS/JS or Jekyll)
- [ ] Add site-wide metadata (title, description, social meta tags, favicon)
- [ ] Build main navigation and footer
- [ ] Implement pages: Home, Projects, Approach, Speaking, About, Contact
- [ ] Implement responsive layout and typography
- [ ] Implement accessibility basics (semantic HTML, heading order, alt text, focus states, contrast)
- [ ] Add required assets (portrait, project visuals, diagrams, screenshots)
- [ ] Add project case-study entries using the provided template
- [ ] Add contact routes and context-specific contact CTA buttons
- [ ] Performance check (fast load, no heavy deps)
- [ ] Deploy to GitHub Pages and verify URL
- [ ] Optional: configure custom domain (e.g., portfolio.valtoai.com or valtoloikkanen.com)

High-level site map
- / (Home)
  - Hero (headline, subheadline, supporting paragraph)
  - Trust / credibility strip (short signal blocks)
  - Selected areas of work (card grid)
  - Builder narrative (why this portfolio exists)
  - Mini approach (how I work)
  - CTA area (Contact / LinkedIn)
- /projects
  - Intro paragraph explaining private work and case-study focus
  - Project card grid (link to each case study or expanded section)
  - Case-study pages/sections (use consistent template)
- /approach
  - How I work (AI-native development mindset)
  - UX-first system design approach
  - Why multidisciplinary background matters
  - Process / methods (brief steps or cards)
- /speaking
  - Topics (list)
  - Formats (keynotes, workshops, coaching, advisory)
  - Past speaking highlights (select)
  - Contact CTA for booking
- /about
  - Full bio narrative / career arc
  - Photo (professional portrait)
  - Roles summary (founder, CEO, advisor, etc. with builder-first narrative)
  - Quick facts / credibility (years, regions, specialties)
- /contact
  - Contextual contact options (Hiring, Speaking/Advisory, Collaboration)
  - Email link / contact form
  - LinkedIn / GitHub links

Page-by-page required content blocks (concise)

Home
- Hero: Headline, subheadline, 1–2 sentence supporting paragraph
- Primary CTA: View Projects; Secondary CTA: About; optional: Speaking
- Credibility strip: 3–4 short bullets (25+ years, AI-native dev, CX & ecosystems, roles)
- Selected areas: 4 cards (Personal AI & AI Twins; Talking Products & Venues; Customer Experience AI Systems; AI-Native Product Architecture) — each: title + 1-line description
- Builder narrative: short paragraph explaining private work and builder-first identity
- Mini approach: 4–6 short bullets
- CTA block: Contact / LinkedIn

Projects
- Intro explaining private/internal work and focus on product logic, system design, AI patterns
- Project cards with short overview and link
- Case-study template (see below)
- Optional visuals (diagrams, screenshots)

Approach
- Framing: AI-native mindset + UX-first system design
- Process steps: user-first, clarify product logic, leverage AI for prototyping, align UX/business/data, build for practical value
- Examples / short notes about how multidisciplinary background shapes approach
- CTA: Work together / Contact

Speaking
- Short positioning: secondary but credible offering
- Topics and descriptions (AI-native products, conversational systems, CX systems, product architecture)
- Formats & logistics (available formats, audience fit)
- Booking CTA and contact method

About
- Full bio narrative and career arc (concise, humanized)
- Single professional portrait
- Roles summary (founder, CEO, advisor, designer, etc.) with builder emphasis
- Quick credibility bullets (years, geographies, select outcomes)
- CTA: Contact / LinkedIn

Contact
- Context-specific contact options (checkbox or labeled buttons)
  - Hiring & product roles: email + resume link
  - Speaking/advisory: booking email / topics
  - Collaboration / partners: short form or direct email
- Minimal contact form (optional) + mailto fallback
- Links to LinkedIn / GitHub

Project case-study template (use for each project)
- Title
- Short overview (1–2 lines)
- Problem / Opportunity
- What the system does
- My role (concise responsibilities)
- Product / UX perspective (key design challenges and solutions)
- AI / architecture perspective (patterns, data/model considerations)
- Outcomes / learnings (metrics or qualitative takeaways if possible)
- Visuals: diagram(s), screenshots (annotated where helpful)
- Tags: area (Personal AI / Talking Products / CX / Ecosystem)

Tone constraints (site-wide)
- Clear, modern, grounded, intelligent, builder-focused
- Avoid overhype, excessive buzzwords, founder ego, company-specific identity, heavy jargon, inflated or vague claims
- Practical, evidence-based, slightly premium and refined — not flashy or sterile
- Keep language concise and outcome-oriented

Must-have assets
- Professional portrait (high-res, cropped appropriately for web)
- Short resume / CV (PDF) or summary page
- Project visuals: diagrams for systems, annotated screenshots, architecture sketches (not necessarily production code)
- Short testimonials or speaking credits (optional)
- Links: LinkedIn URL, GitHub URL, ValtoAI.com, contact email
- Favicon and simple logo/monogram (optional)
- Site metadata images for social sharing (Open Graph)

Technical & UX constraints
- Platform: GitHub Pages (static HTML/CSS/JS or Jekyll)
- Keep stack minimal: no heavy frameworks, avoid JS bundlers unless needed
- Responsive layout, mobile-first CSS
- Typography: modern sans-serif via Google Fonts (heading + body)
- One restrained accent color (prefer blue related to ValtoAI), white/light background, dark text
- Accessibility: semantic HTML, headings H1..Hn in order, alt text, keyboard-accessible nav, visible focus states
- Performance: minimal assets, optimized images, avoid large animations
- Navigation: Home, Projects, Approach, Speaking, About, Contact; optional top-right icons for LinkedIn/GitHub/ValtoAI.com
- Footer: one-line positioning + links + email + copyright

Repository structure suggestion
- /index.html (Home)
- /projects/index.html (Projects list)
- /projects/<slug>/index.html (Case studies) or single projects page with sections
- /approach/index.html
- /speaking/index.html
- /about/index.html
- /contact/index.html
- /assets/
  - /css/
  - /js/ (minimal)
  - /img/ (portraits, project visuals, favicon)
  - /meta/ (og images)
- /_includes/ and /_layouts/ (if Jekyll used)
- README.md (repo info)
- TODO.md (this file)
- robots.txt, sitemap.xml (optional)

Acceptance criteria (basic QA)
- Home clearly communicates: what Valto builds, why his background is valuable, builder-first identity within 3–5 seconds
- Projects page shows concrete case studies with product + architecture thinking
- Approach explains how he builds (AI-native + UX-first)
- Speaking page shows topics and formats; doesn’t overshadow builder identity
- About page provides coherent career arc and humanizes author
- Contact page provides context-specific routes and works (mailto/form)
- Site passes basic Lighthouse checks (performance/accessibility)
- Navigation is keyboard accessible and semantic headings are correct

Deployment checklist
- [ ] Add CNAME if using custom domain
- [ ] Enable GitHub Pages on repo (branch: main or gh-pages)
- [ ] Verify deployed URL and Open Graph preview
- [ ] Test on mobile and desktop; run accessibility and performance audits

Notes / priorities
- Prioritize clarity and speed over visual ornamentation
- Use project case studies to compensate for private code by demonstrating product logic, architecture, and impact
- Keep content concise and factual — avoid grandiose claims
- Iterate: get an initial static version live quickly, then enhance visuals and add case-study depth
