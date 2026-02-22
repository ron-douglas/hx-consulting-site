# Phase 1 Website Spec (Mobile-First)

## 1. Purpose
Create a low-profile, credible, mobile-first website for a film/TV consulting practice focused on psychological realism, trauma-informed character development, and authentic portrayal of under-resourced communities.

This site is a Phase 1 business-development asset: concise positioning, clear services, and confidential inbound contact.

## 2. Brand & Positioning
- Working name: `HX Consulting`
- Primary tagline: `Psychological realism for film & TV`
- Positioning statement:  
  `We advise writers and showrunners on character development, trauma realism, and authentic portrayal of under-resourced communities in film and television.`
- Voice: professional, discreet, practical, non-performative.
- Audience:
  - Showrunners
  - Writers’ room teams
  - Producers / development executives
  - Script coordinators and assistants who influence vendor recommendations

## 3. MVP Scope
- Single-page site (no blog, no case studies at launch)
- Mobile-first responsive design
- Lightweight static delivery (plain HTML/CSS/JS, Astro, or Next.js static export)
- Inquiry CTA that routes to email
- No public pricing
- No therapy intake workflows

## 4. Information Architecture
- Hero
- Services
- About
- How It Works
- Contact
- Footer

## 5. Section-Level Content Requirements

## 5.1 Hero
- H1: `Psychological realism for film & TV`
- Supporting copy:  
  `Clinical insight for character development, trauma arcs, and authentic portrayal of under-resourced communities.`
- Primary CTA button: `Request a confidential consult`
  - Action: `mailto:contact@hxconsulting.com?subject=Confidential%20Consult%20Inquiry`
- Optional secondary text link: `View services` (anchor scroll to Services)

## 5.2 Services
- Section title: `Services`
- 3 service cards (stacked on mobile, grid on tablet/desktop):
  1. `Script & Character Notes`  
     Written feedback on pilots, scripts, and story bibles focused on psychological credibility, trauma responses, and character arcs.
  2. `Writers’ Room Consulting`  
     Live sessions with writers’ rooms to workshop character psychology, motivation, and long-arc development.
  3. `On-Call Advisory`  
     Short-term retainers for shows needing ongoing consultation during a season.

## 5.3 About
- Section title: `About`
- Profile block 1:
  - Name: `Melanie Hsu, PhD`
  - Role line: `Clinical psychologist`
  - Bio line: `Specializing in trauma and mental health in under-resourced populations.`
  - Compliance note: avoid wording that implies endorsement by current employer.
- Profile block 2:
  - Name: `Karen Xie, LMFT`
  - Role line: `Licensed Marriage & Family Therapist`
  - Bio line: `Experience supporting individuals, couples, and families navigating trauma and adversity.`
- Joint blurb:  
  `Together, we bring complementary clinical perspectives to help storytellers build emotionally authentic characters and responsible portrayals of mental health.`

## 5.4 How It Works
- Section title: `How It Works`
- 3-step flow:
  1. `Confidential inquiry`
  2. `Scope & format alignment (script notes, room consult, or short retainer)`
  3. `Fixed-scope engagement`
- Supporting note: `Pricing shared after scoping.`

## 5.5 Contact
- Section title: `Get in Touch`
- Contact email (placeholder): `contact@hxconsulting.com`
- CTA: `Email us`
- Disclaimer text (required):  
  `Consulting for creative projects only. Not providing therapy or clinical services through this website.`

## 5.6 Footer
- Copyright line: `© HX Consulting`
- Trust line: `Discretion · Confidentiality · Professional Ethics`

## 6. UX / UI Requirements
- Mobile-first breakpoints:
  - Small: <= 640px
  - Medium: 641px-1024px
  - Large: > 1024px
- Layout:
  - Single column on mobile
  - 2-column blocks where useful on desktop (e.g., About)
- Tap targets >= 44px
- Sticky or easy-return CTA is optional, not required
- Avoid stock photography at launch

## 7. Visual Direction
- Tone: restrained, editorial, premium but understated
- Suggested palette:
  - Charcoal `#1F2328`
  - Off-white `#F7F5F2`
  - Slate blue accent `#4A667A`
  - Secondary neutral `#D9D4CC`
- Typography:
  - Preferred: `Source Sans 3`, fallback `Inter`, then sans-serif
- Background treatment:
  - Clean neutral base with subtle texture/noise optional
- Motion:
  - Minimal fade/slide reveals only
  - Respect reduced-motion preferences

## 8. Accessibility Requirements
- Semantic headings in order (`h1` -> `h2`)
- Color contrast meets WCAG AA
- Keyboard-navigable controls
- Visible focus states
- `aria-label` where needed on icon-only controls
- Reduced-motion support (`prefers-reduced-motion`)

## 9. Non-Functional Requirements
- First meaningful paint target: < 2.5s on mid-tier mobile
- No heavy client-side dependencies required
- Total asset payload target (excluding fonts): < 500KB
- Static hosting compatible (Netlify, Vercel static, GitHub Pages)

## 10. Legal / Risk Guardrails
- Do not present services as clinical care.
- Include explicit creative-consulting-only disclaimer.
- Avoid promises about outcomes or “accuracy guarantees.”
- Ensure bio wording does not imply institutional endorsements.

## 11. SEO / Discovery (Low-Profile)
- Basic metadata only:
  - Title: `HX Consulting | Psychological Realism for Film & TV`
  - Description: concise service summary
- No aggressive content marketing in Phase 1
- Indexing allowed, but no growth-driven SEO work required

## 12. Analytics (Optional in Phase 1)
- If used, privacy-focused analytics only (e.g., Plausible/Fathom)
- Track:
  - CTA clicks
  - Email link clicks
  - Section scroll depth (optional)

## 13. Launch Checklist
- Domain configured
- SPF/DKIM/DMARC set for contact domain email
- All copy approved
- Mobile QA (iOS Safari + Android Chrome)
- Desktop QA (Chrome, Safari)
- Accessibility quick pass completed
- Disclaimer present in Contact section

## 14. Future Enhancements (Phase 2, Not in MVP)
- Downloadable one-pager directly on site
- Private intake form with service type selector
- Trusted-by logos/case snippets (if permission obtained)
- Additional consultants page if firm scales
