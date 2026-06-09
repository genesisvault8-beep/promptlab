# PromptLab

AI Prompt Engineering Workspace — by GenesisVault

## Files
```
promptlab/
├── index.html      ← Landing page
├── app.html        ← Main app (BYOK + compare + library + saved)
├── manifest.json   ← PWA manifest
├── sw.js           ← Service worker (offline support)
└── icons/
    └── icon.svg    ← App icon
```

## Deploy to GitHub Pages

1. Create a new repo: `genesisvault8-beep/promptlab`
2. Push all files to `main` branch
3. Go to Settings → Pages → Deploy from main branch
4. Add `CNAME` file containing: `promptlab.genesisvault.xyz`
5. In Dynadot DNS, add:
   - Type: CNAME
   - Name: promptlab
   - Value: genesisvault8-beep.github.io

## Features
- BYOK (Bring Your Own Key) — users paste their Anthropic API key
- Real AI compare scoring — Claude judges which prompt wins
- 15 prompt templates across 5 categories
- Save/export prompts to JSON
- PWA installable on mobile
- Zero backend, zero accounts, zero cost to you
