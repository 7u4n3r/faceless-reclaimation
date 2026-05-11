# DESIGN_REBUILD_PLAN.md

## Purpose

This plan protects the uploaded page design and turns it into a clean rebuild path.

The goal is not to flatten the page into a plain landing page.

The goal is to recover the living design and rebuild it with clean project boundaries.

## Core decision

The uploaded design should become the source for a larger public surface:

# Faceless Reclaimation Digital Home

This is different from a simple zine page.

It can hold multiple rooms, tools, and public-facing materials while keeping related projects labeled correctly.

## Design language to keep

Preserve:

- dark app-like background
- neon/gradient energy
- cyan, purple, pink, rose, and blue accents
- rounded cards
- pill buttons
- soft glow / radial gradient feel
- visual sense of an actual product surface
- interactive multi-page navigation
- project cards on the home page
- strong emotional-tech hybrid identity

## Structure to keep if rebuilt as React app

Potential pages:

- Home
- About
- Language of Liberation
- Shadow Work
- AI Training
- Living Lexicon or DisLexicon-related page
- Tools index

Potential future pages only if source exists or is rebuilt cleanly:

- Fear Differential
- Symptom Checker
- The Mirror
- Survival Science
- Trinity Method

## Boundary rules

Faceless Reclaimation may host related rooms, but it must not claim every related room is the same project.

Perspection remains governance and observation infrastructure.

Trinity remains structure and movement logic.

System Analysis Reference remains evidence/template structure.

KY County Map remains ABLE-KY county navigation.

## Required cleanup before publishing

- Replace `Faceless Reclamation` with `Faceless Reclaimation` unless intentionally quoting archived source.
- Remove placeholder product links.
- Remove unfinished routes or replace them with coming-soon/disabled states.
- Confirm all imported components exist.
- Confirm the app builds cleanly.
- Confirm no private material is included.
- Confirm no legal/evidence material is accidentally exposed.
- Confirm related projects are labeled as related, not absorbed.

## Implementation options

### Option A: Static rebuild

Create one strong static `index.html` that copies the loved visual language without requiring React routing.

Best if speed matters.

Tradeoff: less interactive, fewer rooms.

### Option B: React app rebuild

Create a proper React/Vite app inside this repo using the uploaded components as source reference.

Best if this becomes the real Faceless Reclaimation Digital Home.

Tradeoff: requires dependencies, routes, components, and build workflow.

### Option C: Sandbox first

Move the app into `Trinity-tools` or a new sandbox branch first, rebuild there, then copy the stable output back.

Best if experimentation continues.

Tradeoff: slower path to public page.

## Recommended path

Option B, but carefully.

Build a real Faceless Reclaimation Digital Home using the uploaded design language.

Start with routes that have source files:

- Home
- About
- Language of Liberation
- Shadow Work
- AI Training

Hold missing routes until their source exists.

## Do not do

- Do not overwrite the live page with a plain placeholder.
- Do not deploy the uploaded export without rebuilding.
- Do not publish placeholder links.
- Do not merge Perspection, Trinity, and Faceless Reclaimation into one identity.
- Do not remove the emotional/design intensity that made the page feel alive.

## Rebuild prompt summary

Rebuild the uploaded Faceless Reclaimation page as a clean React/Vite app.

Preserve the visual identity: dark surface, gradients, rounded cards, pill buttons, app-like polish, emotionally alive structure.

Fix spelling to Reclaimation.

Use only routes with available source.

Keep Perspection, Trinity, System Analysis, and KY County Map related but separate.
