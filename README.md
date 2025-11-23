# CGPA Converter & Calculator

Free, privacy-friendly academic toolkit for converting CGPA ↔ percentage and calculating SGPA/CGPA. Runs entirely client-side.

## Features

- CGPA → Percentage using official and common standards
- Percentage → CGPA reverse calculation
- SGPA and CGPA calculators with weighted formulas
- Target GPA planner
- Share calculations via unique links (view-only, optional expiry)

## Sharing

- Create shareable links with expiry options: 7 days, 30 days, or never
- View-only access: shared links disable inputs for recipients
- Social buttons: Twitter, Facebook, LinkedIn, WhatsApp, Telegram
- Optional UTM parameters added to measure channel effectiveness

### Analytics

- Local counts stored in `localStorage`
- To send events to your endpoint, set `window.SHARE_ANALYTICS_ENDPOINT` (expects `POST`/Beacon supporting endpoint)

## Development

- Single-page app in `index.html` using TailwindCDN and vanilla JS

## License

MIT — see `LICENSE`.

## Credits

University formulas referenced from official sources; estimates provided where applicable. Use WES or university tools for official conversions.
