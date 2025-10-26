# Aegaia API Docs – Enterprise (Scalar 3-panel)

This package publishes your **Forecast** and **Off-Market** APIs with an enterprise-grade OpenAPI and a branded docs shell.

## Files
- `openapi.yaml` — Complete OAS 3.1 for both endpoints.
- `index.html` — Scalar web component wrapper with x-api-key injection for Try-It.
- `theme.css` — Dark theme and layout tweaks.
- `_redirects` — SPA/static hosting helpers.
- Logos under `/docs`.

## Deploy
Upload all files as-is. No edits required.

## Notes
- Auth: `x-api-key` header.
- Entitlement-aware responses.
- Historical value + date + property type → HPI-adjusted valuation.
