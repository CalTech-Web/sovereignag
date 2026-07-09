# Sovereign Agricultural Group — Redesign Brief

## Context
The current live site (https://sovereignag.vercel.app, local copy at /Users/brandonhopkins/Projects/sovereignag/site/) is a pixel-faithful recovery of an old WordPress/Elementor site. The client's agency (Ken, Avalanche Marketing) has asked for a COMPLETELY NEW, modern design that:
- Keeps ALL existing content (copy) as-is
- Keeps the same pages and URL structure
- Keeps the same navigation
- Does NOT try to mirror the old layout in any way. Fresh, modern, 2026-quality design.

## Business
Sovereign Agricultural Group is a private equity firm that invests in American family farms and ranches to keep them out of foreign ownership, champion sustainable/regenerative agriculture, and preserve US agricultural heritage. Tone: institutional, trustworthy, patriotic-but-tasteful, land-and-heritage focused. Audience: farm/ranch owners considering selling or partnering, and accredited investors.

## Brand
- Logo: /Users/brandonhopkins/Projects/sovereignag/site/_assets/sovereignag.com/wp-content/uploads/2024/09/Sovereign-Logo-1024X480.png (also other sizes in same folder; look for Sovereign-Logo*)
- Colors: harvest gold #C3921C (primary accent), deep field green #325C00, near-black #1F2124 / #3A3A3A, white, warm neutrals. You may extend the palette (tints/shades, cream backgrounds) but gold + deep green must stay the recognizable brand core.
- No em dashes anywhere in content. Never use the — character.

## Navigation (preserve exactly)
Header: Home /, Who We Are /who-we-are/, What We Do /what-we-do/, Partner With Us /partner-with-us/, Investors /investors/, Contact /contact/, plus a prominent CTA button "Sell Your Business" -> /sell-your-business/
Footer: same links + Privacy Policy /privacy-policy/, email info@SovereignAG.com, social icons (Facebook, X, LinkedIn, Instagram).

## Content
Full extracted copy for every page is in /Users/brandonhopkins/Projects/sovereignag/redesign/CONTENT.md. Key home stats: 1.89M US Family Farms, 879M Controlled Acres, 90% Of Production.

## Imagery
Reuse images from /Users/brandonhopkins/Projects/sovereignag/site/_assets/sovereignag.com/wp-content/uploads/ (agricultural photos, logo). Reference them with relative paths into that tree or copy them next to your file. These are stand-in photos; the agency will replace them later, so treat imagery as swappable.

## Technical constraints for mockups
- Single self-contained index.html per option (inline CSS in a <style> block, system/Google-safe font stacks via local fallbacks only, no external CDNs, no build step).
- Fully responsive (375px, 768px, 1280px+).
- Real content from CONTENT.md for the homepage, not lorem ipsum.
- Working anchor hrefs to the real URL paths for nav (they will 404 in the mockup; that is fine).
- Modern touches expected: generous whitespace, strong typographic hierarchy, large hero, stat counters, card layouts, sticky header, tasteful hover states. CSS-only animation is fine.
