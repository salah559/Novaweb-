# Novaweb Portfolio Website - Design Guidelines

## Design Approach
**Reference-Based Approach** inspired by modern tech agencies (Vercel, Linear, Stripe) with bold color usage and clean typography. The design emphasizes Novaweb's technical expertise through precise layouts and strategic use of electric blue as a powerful brand differentiator.

---

## Core Design Elements

### A. Color Palette

**Primary Colors:**
- Electric Blue: `205 100% 55%` - Primary brand color for CTAs, accents, and interactive elements
- Deep Navy: `220 30% 8%` - Primary background for dark sections
- Pure White: `0 0% 100%` - Clean backgrounds and text on dark
- Slate Gray: `220 15% 25%` - Secondary text, borders, subtle backgrounds

**Accent & Utility:**
- Light Gray: `220 10% 96%` - Subtle section backgrounds
- Electric Blue Glow: `205 100% 65%` - Hover states and highlights
- Transparent Overlays: Electric blue at 10-20% opacity for cards and glassmorphism effects

---

### B. Typography

**Font Families (via Google Fonts CDN):**
- Primary: 'Poppins' - Headings, UI elements, primary content
- Secondary: 'Tajawal' - Optional for bilingual support or specific accents

**Type Scale:**
- Hero Headline: 4xl-6xl, font-weight 700, tracking tight
- Section Headings: 2xl-4xl, font-weight 600
- Subheadings: xl-2xl, font-weight 500
- Body Text: base-lg, font-weight 400, line-height relaxed
- Small Text: sm, font-weight 400

---

### C. Layout System

**Spacing Primitives (Tailwind Units):**
Primary spacing: 4, 8, 12, 16, 20, 24
Section padding: py-16 to py-24 (mobile), py-20 to py-32 (desktop)
Component gaps: gap-4, gap-8, gap-12
Container: max-w-7xl with px-4 to px-8

**Grid Strategy:**
- Services: 3-column grid on desktop (lg:grid-cols-3), 1-column mobile
- Portfolio: 2-column grid (md:grid-cols-2), masonry-style layout
- Single column for About Us and Contact sections

---

### D. Component Library

**Navigation:**
- Fixed/sticky header with transparent-to-solid transition on scroll
- Logo left-aligned, navigation links right-aligned
- Smooth scroll behavior to sections
- Mobile: Hamburger menu with slide-in overlay

**Hero Section:**
- Full viewport height (min-h-screen) with centered content
- Large Novaweb logo prominent at top-center
- Headline "Turning Ideas into Reality" in electric blue gradient
- Subtle animated background (grid pattern, particles, or geometric shapes)
- Primary CTA button with electric blue background and glow effect
- Hero does NOT require a large background image - use animated gradient/pattern instead

**Cards (Services & Portfolio):**
- White/dark card backgrounds with subtle border
- Hover effect: Lift (translate-y), electric blue border glow, shadow increase
- Icon/image at top, title, description, optional "Learn More" link
- Border-radius: rounded-lg to rounded-xl

**Contact Form:**
- Input fields with electric blue focus rings
- Dark background inputs with light text
- Submit button matching primary CTA style
- Email display with icon and copyable format

**Footer:**
- Dark navy background
- Two-column layout: Left (copyright), Right (social/Discord links)
- Social icons with electric blue hover states
- Links in slate gray with white hover

---

### E. Animations & Interactions

**Scroll Animations:**
- Fade-in + slight translate-up for sections entering viewport
- Stagger delays for card grids (0.1s increments)

**Hover States:**
- Buttons: Background brightness increase, subtle scale (1.05)
- Cards: Lift effect with enhanced shadow and electric blue border
- Links: Color shift to electric blue, underline animation

**Transitions:**
- Standard: 0.3s ease-in-out
- Quick interactions: 0.15s
- Smooth scroll: behavior smooth for anchor links

**Minimal Animation Principles:**
- No autoplay carousels or excessive motion
- Purposeful animations that enhance hierarchy
- Respect prefers-reduced-motion

---

## Images

**Logo Usage:**
- Provided Novaweb logo displayed in header (h-12 to h-16)
- Also featured prominently in hero section (larger scale, h-24 to h-32)

**Portfolio/Projects Section:**
- Placeholder project cards with modern illustrations or abstract tech visuals
- Consider: Code editor screenshots, device mockups, or abstract geometric compositions
- Each card should have a visual element (icon or small image)
- No large hero background image needed

**About Us Section:**
- Optional: Abstract tech illustration or team-related imagery
- Keep visual hierarchy focused on text content

**Image Treatment:**
- Subtle rounded corners (rounded-lg)
- Optional: Electric blue overlay at low opacity for brand consistency

---

## Section-Specific Guidelines

**Hero:** 80-90vh height, centered content, animated gradient background, large logo, powerful headline, single CTA

**About Us:** Centered text with max-w-3xl, concise 2-3 paragraphs, vision statement highlighted

**Services:** 3-column card grid, icons from Heroicons, clear service descriptions, consistent card heights

**Portfolio:** 2-column masonry grid, project cards with images, hover reveals project details/links

**Contact:** Centered form (max-w-lg), 3 fields (name, email, message), direct email displayed below form, submit button prominent

**Footer:** Full-width dark section, organized link groups, social icons with Discord prominent

---

**Design Philosophy:** Clean, confident, and technically sophisticated. Electric blue as strategic accent, not overwhelming. Generous whitespace. Mobile-first responsive. Every element serves a purpose.