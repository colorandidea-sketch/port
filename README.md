# Portfolio Card — Waled Ibrahim (Tasalia-style)

A static, responsive portfolio/contact card web page matching the provided reference design (red header + blue profile section + rounded white cards).

## Completed features

- Red header section with **Tasalia logo** (top-left)
- Blue gradient profile section with:
  - Circular avatar placeholder
  - Name and title
  - Two circular icon buttons
- Rounded white cards with subtle shadows:
  - **Contact Info** card with phone/email/location rows + icons
  - **WhatsApp** card with green CTA button
  - **Visit Website** card with blue CTA button
- Footer text: **Powered by TASALIA SOLUTIONS**
- Responsive layout (mobile-first) with a centered max-width container
- Smooth hover/active effects on buttons
- **Save Contact** button generates and downloads a `.vcf` vCard (client-side)

## Entry URIs (paths)

- `GET /index.html` (main page)

## Not yet implemented

- Real Tasalia logo asset (currently a styled placeholder)
- Real website URL for “Official Online Store” (currently `#`)
- Social media links for the two circular action buttons (currently anchors to contact section)

## Recommended next steps

1. Replace logo placeholder with an actual logo image (e.g., `images/logo.png`).
2. Replace avatar placeholder with a real profile image.
3. Update WhatsApp and website links.
4. Add additional sections (About, Services, Portfolio items) if desired.

## Project goals & main features

Goal: Provide a clean, modern, shareable personal portfolio/contact landing page that visually matches the reference.

Main features: profile header, contact card, WhatsApp CTA, website CTA, vCard download.

## Public URLs

- Production: Use the **Publish tab** to publish the project and get the live URL.
- API endpoints: None (static site only)

## Data models / storage

- No database used
- No RESTful Table API used
- All data is hard-coded in HTML/JS (edit `index.html` and `js/main.js`)
