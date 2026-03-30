# Consultancy Landing Page

## Overview

Single-page landing site for a Claude implementation consultancy owned by Francisco Turdera ("Alas"). Target audience: enterprise decision-makers (CTOs, VP Eng) evaluating Claude Enterprise. Goal: visitor → understands offering → books intro call.

This is for a Claude Partner Network application and Anthropic Services Partner Directory listing.

## Technical Requirements

- **Single `index.html` file** — CSS and JS inline/embedded. No build step.
- Deploy to Netlify or Cloudflare Pages from this repo.
- No backend, no forms. Calendly handles scheduling, email handles async.
- Must load in under 2 seconds on mobile.
- Add placeholder comment for Plausible/Fathom analytics script. No Google Analytics.
- SEO: proper meta title, description, Open Graph tags mentioning Claude, MCP, enterprise AI.

## Key Conventions

- Use "I" not "we" — this is a solo practitioner, own it.
- No hype words ("revolutionary," "cutting-edge," "unlock the power of").
- Technical and specific: mention MCP, Claude Code, model routing, HL7/FHIR by name.
- Confident but not arrogant tone.

## Running

Open `index.html` in a browser. No build step needed.
