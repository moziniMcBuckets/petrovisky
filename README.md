# petrovisky

Here’s a very detailed Product Requirement Document (PRD) you can provide to Kiro.dev to scaffold your full public website for Petrovisky Solutions (marketing site only). You can paste this into Kiro under “Spec Mode” and it will generate structured tasks, design, and code.

⸻

Petrovisky Solutions — Website PRD

Project Name: Petrovisky Public Website
Owner: Petrovisky Solutions (Seattle / King County based)
Date: 2025-11-10
Version: 1.0
Purpose:
Build a professional, conversion-focused SaaS website that introduces Petrovisky Solutions’ generative AI automation platform for small and medium-sized businesses. The website should be visually polished, brand-consistent, mobile responsive, and optimized for demo sign-ups and lead capture.

⸻

1. Objectives & Success Metrics

Objectives:
	•	Clearly communicate what Petrovisky Solutions offers (AI automations for SMBs)
	•	Build trust and credibility (enterprise-quality, secure, local support)
	•	Drive conversions: “Book a Free Demo”, “Get Started”
	•	Provide clear service offering breakdown and pricing
	•	Prepare for future integration of customer portal login (but not built yet)

Success Metrics:
	•	Demo CTA click-through rate ≥ 10% of visitors
	•	Bounce rate < 60% on key landing page
	•	Mobile conversion rate within 80% of desktop
	•	Page load time < 3 seconds on average

⸻

2. Target Audience
	•	Small and medium business owners (10-200 employees) in King County / USA
	•	Industries: Accounting & Tax Firms, Service Businesses (gyms, salons), Retail/Fitness Studios, Real Estate Teams
	•	Non-technical decision makers: want simple, reliable automation solutions
	•	Concerned about cost, complexity, data security, and usability

⸻

3. Brand & Design Guidelines

Brand Colors:
	•	Primary Color: #0073BB (Deep Blue)
	•	Accent Color: #D1A73E (Gold)
	•	Backgrounds & Cards: White #FFFFFF, Light Grey #F5F6F8
	•	Dark Mode Option (future): Nav Dark Navy #0D1B2A, Content Dark #1E293B, Text Light Grey #E5E7EB

Typography:
	•	Headings: Inter SemiBold or Poppins SemiBold
	•	Body Text: Inter Regular or Poppins Regular
	•	Font weights: H1=700, H2=600, etc.

Imagery & Style:
	•	Modern business-workplace photography (business owners with laptops, teams collaborating)
	•	AI/automation abstract visuals (lines, overlays, subtle motion)
	•	Clean cards, generous whitespace, minimal decorative elements

Tone & Voice:
	•	Professional but approachable
	•	Clear & benefit-driven (“Automations that write emails, track documents, and summarize your operations”)
	•	Trust-oriented (“Enterprise-grade tech made for SMBs”, “Local King County support”)

⸻

4. Sitemap & Page Structure

Main pages / sections:
	1.	Home / Landing
	2.	Services / Features
	3.	How It Works
	4.	Industries We Serve
	5.	Pricing
	6.	About / Company
	7.	Contact / Lead Form
	8.	Footer (global)
	9.	Privacy & Terms (legal)

⸻

5. Page & Section Specifications

5.1 Home / Landing
	•	Hero Section:
	•	Headline: “Generative AI That Works for Your Business.”
	•	Subheading: “Automations that write emails, track documents, and summarize your operations — so you can focus on clients.”
	•	CTA Buttons: Primary (Gold) “Book a Free Demo”; Secondary (Outlined in Blue) “See How It Works”.
	•	Hero image/illustration: Business owner at laptop with AI overlay.
	•	Features/Services Section: 4-card grid as described.
	•	How It Works: 4-step flow with numbered icons.
	•	Industries We Serve: 4-tile grid.
	•	Testimonials/Social Proof: 3 cards with logo/avatar + quote.
	•	Why Choose Us: 3 icon + text cards.
	•	CTA Banner (Full Width): Blue background, white text, CTA button.
	•	Footer: Logo, nav links, email, copyright.

5.2 Services / Features
	•	Page or section with expanded detail for each of the 4 offerings (Content & Reputation Automation; Lead-to-Client Flow; Weekly Business Digest; Custom AI Workflows).
	•	Each offering: icon, headline, supporting paragraph, optional screenshot/illustration.

5.3 How It Works
	•	Horizontal flow or vertical steps (responsive) with numbered steps: Discovery Call → Pilot Setup → Go Live → Scale & Support.
	•	Each step: icon, title, short description.

5.4 Industries We Serve
	•	Grid or list of industries.
	•	For each: industry name, brief description of how Petrovisky helps, representative image.

5.5 Pricing
	•	3-tier pricing table: Starter (Free/entry), Growth ($99/mo), Pro ($249/mo) or similar.
	•	Each plan card with features bullet list, price toggle monthly/annual, CTA button.
	•	Highlight Growth tier (accent gold).

5.6 About / Company
	•	Company story: “We’re a Seattle-based team helping local SMBs use AI to grow efficiently…”
	•	Image of team or workspace.
	•	Mission, values, local presence.

5.7 Contact / Lead Form
	•	Simple form: Name, Email, Business Name, Message, CTA “Send Message”.
	•	Include optional calendar/booking link.
	•	Provide phone/email contact info.

5.8 Footer
	•	Compact design: Logo, nav links, social icons (if any), contact email, copyright.
	•	Links: About | Services | Contact | Privacy Policy.

5.9 Legal Pages (Privacy / Terms)
	•	Standard layout, clean typography. Linked in footer.

⸻

6. UX / Responsive Behaviour
	•	Desktop first (width ~1440px) then breakpoints at 1024px, 768px, 480px.
	•	On mobile:
	•	Collapse nav into hamburger.
	•	Grid cards stack vertically.
	•	Buttons full width.
	•	Text size reduces (H1 ~2rem on mobile).
	•	Maintain whitespace and readability.
	•	Animations:
	•	Subtle hover lifts for cards.
	•	Scroll-fade/slide for hero image and step icons.
	•	Accessibility:
	•	Contrast ratio compliant (WCAG AA).
	•	Semantic HTML structure.
	•	Alt-text on images.

⸻

7. Technical / Implementation Notes
	•	Build using React + Tailwind CSS (or equivalent CSS-in-JS) or using Framer (since you will use Kiro to scaffold).
	•	Use design tokens (CSS variables) for brand colours, typography, spacing.
	•	Deployable as static site (Next.js SSG) or via Framer publishing.
	•	Optimise for performance: lazy-load images, compress hero graphic, use proper meta tags for SEO.
	•	Provide clean file structure: pages/, components/, styles/, assets/.
	•	Provide Figma/Framer design file and code export.

⸻

8. SEO & Analytics
	•	Meta tags on every page: title, description, open-graph tags, structured data (Organization schema).
	•	Use Google Analytics or equivalent tracking.
	•	Blog (optional) support for content marketing.
	•	Sitemap.xml + robots.txt.

⸻

9. Deliverables
	•	Figma or Framer design file with all pages, components, and responsive variants.
	•	Code scaffold (React/Next.js or Framer) with styling, components, home page, services page.
	•	Design tokens file (colors, typography, spacing).
	•	Usability test script for major flows (demo booking).
	•	Documentation: README with deployment instructions, environment, naming conventions.
	•	Version 1.0 of website ready for review.

⸻

10. Timeline & Milestones
	•	Week 1: Finalise brief, brand tokens, home page design.
	•	Week 2: Complete Services, How It Works, Industries, Testimonials sections.
	•	Week 3: Pricing, About, Contact, Footer & legal pages. Mobile responsiveness & QA.
	•	Week 4: Code export, deployment, SEO setup, launch.

⸻

11. Constraints & Assumptions
	•	Dashboard/portal login and automations integration not included in this phase.
	•	Visuals and imagery may use stock placeholders initially.
	•	Content (text) will be provided by Petrovisky; design to accommodate moderate edits.
	•	Hosting/domains already provisioned (petrovisky.ai).
	•	Budget & performance constraints: page load under 3s.

⸻

12. Approval & Review Process
	•	Design review at end of Week 1 & Week 3.
	•	Stakeholder (Petrovisky founder) approval required before moving to implementation.
	•	Code review and QA before deployment.

⸻

