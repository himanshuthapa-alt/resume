# Himanshu Thapa Portfolio

Single-file personal portfolio built in HTML, CSS, and vanilla JavaScript.

## Overview

This project presents Himanshu Thapa through a cinematic landing flow:

- A Google-style intro with animated typing
- A direct transition into the main portfolio
- Highlight sections for execution, building, mindset, and future goals
- Clickable portfolio cards, social links, and contact actions

## Files

- `himanshu_thapa_portfolio.html`
  Main portfolio page
- `himanshu_thapa_knowledge_graph.html`
  Separate interactive knowledge graph concept
- `WhatsApp Image 2026-04-30 at 7.13.32 PM.jpeg`
  Execution card image
- `WhatsApp Image 2026-04-30 at 7.21.33 PM.jpeg`
  Leadership card image
- `WhatsApp Image 2026-04-30 at 7.39.25 PM.jpeg`
  Mindset card image
- `WhatsApp Image 2026-04-30 at 8.15.58 PM - Edited.png`
  Top-left logo

## How To Run

Open `himanshu_thapa_portfolio.html` in a browser.

No build step, package install, or server is required.

## Main Features

- Animated Google search intro
- Enter key support to open the main site
- Floating clickable logo in the top-left navigation
- Project cards with images and modal details
- External links for website, Instagram, LinkedIn, GitHub, and Gmail
- Gmail compose links for direct contact

## Customize

Edit `himanshu_thapa_portfolio.html` to update:

- Intro typing text:
  `const targetText = "Himanshu Thapa";`
- Hero copy and section text
- Card titles, descriptions, and modal content
- Social links in the ending section
- Gmail compose links:
  `https://mail.google.com/mail/?view=cm&fs=1&to=himanshuthapa476@gmail.com`
- Logo image path in the nav
- Portfolio card images and preview assets

## Notes

- The fake Google results screen markup is still present in the file, but the current interaction skips it and opens the main portfolio directly.
- The video card is prepared for a local muted video file, but no local video source is currently attached.
- External website previews may depend on third-party snapshot services.

## Suggested Next Cleanup

- Remove unused Google results overlay HTML/CSS
- Replace placeholder video with a local `.mp4` or `.webm`
- Normalize any leftover text encoding artifacts
- Add a browser tab favicon if needed
