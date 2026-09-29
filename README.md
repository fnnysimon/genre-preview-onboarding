# genre-preview-onboarding

# Genre-Preview Onboarding

An interactive onboarding flow that gives users real-time feedback as they refine their preferences.

## The Problem

Traditional onboarding asks users to fill out preferences blind, then shows results only at the end — no feedback to adjust along the way.

## The Solution

A two-column layout where genre selection on the left updates a live book preview on the right in real time. No "Next" button required.

## Design Decisions

- **Genre matching logic (AND):** When users select multiple genres (e.g., Romance + Fantasy), we show books that match both, not either. This respects the user's intent to combine genres rather than broaden their search.
- **Tight scope:** 2 screens, no authentication, no database. The goal was to prove the interaction pattern, not ship a full product.
- **Live feedback:** Every click updates the preview immediately, reducing cognitive load.

## Live Demo

[https://bookstore-ecru-delta.vercel.app/onboarding](https://bookstore-ecru-delta.vercel.app/onboarding)

## Design File

[Figma](https://www.figma.com/[your-figma-link])

## Built With

- **Frontend:** Next.js, Tailwind CSS, TypeScript
- **Design:** Figma
- **Deployed:** Vercel

## What I Learned

The most interesting decision wasn't visual — it was the genre matching logic. Testing AND vs OR revealed how much the UI teaches users about what the system expects from them.
