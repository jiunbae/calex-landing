# Calex landing

Marketing site for **Calex** — an always-listening, on-device meeting memory app for iPhone, iPad, and Mac.

- **Live:** https://calex.jiun.dev/ (English) · https://calex.jiun.dev/ko/ (한국어)
- Static site, deployed via GitHub Pages. Custom domain in `CNAME`.
- `shots/` — real app captures (mock data), not mockups:
  - `ios-*.png` — iOS simulator captures (`--calex-ui-fixtures`, isolated store)
  - `mac-today-*.png` — headless macOS render (`Calex-macOS --screenshot`, isolated temp store)

Screenshots are regenerated from the app in the `calex` repo, so they never drift from the shipped UI.
