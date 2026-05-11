# Zaik Family Tree — SEO Chronicle Layer

A design prototype for the dual-view SEO layer built for the Zaik family tree on MyHeritage.

## What is this?
A proof-of-concept showing how to make a JavaScript-rendered family tree 
indexable by Google bots, while keeping the original interactive tree 
experience for users.

## How it works
- **Tree view** — the existing interactive canvas (placeholder in this demo)
- **Chronicle view** — a static HTML narrative layer, fully crawlable by Google

## Live preview
👉 https://gilizaik-hue.github.io/zaik-family-tree

## Tech highlights
- JSON-LD structured data (Person schema) in the `<head>`
- Static HTML in DOM on page load — no JavaScript needed for bots
- CSS toggle between views — both panels indexed by Google
- Zero external dependencies — fully standalone HTML file
- All living people removed for privacy
