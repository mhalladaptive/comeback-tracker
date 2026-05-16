# Comeback Tracker — v2 ideas

Ideas that surfaced during the v1 build and were parked for a future version.
The original v1 boundary list (caber, projections, trend charts, accounts,
multi-athlete, etc.) lives in the spec at
`../Higgins Method/comeback-tracker-spec-v1.md`. This file captures ideas that
came up *during construction* rather than in the original planning.

Add to this list freely as new ideas come up.

---

## UX

- **View as a dedicated nav tab.** The View button currently lives inside the
  Past Sessions list on the Log Session page. Promote the read-only session
  browser to its own top-level nav entry between Log Session and See the Gap,
  so reviewing prior sessions has a peer-level home in the app.

## Distribution

- **Lightweight usage analytics on the public version.** Add a privacy-friendly
  analytics service (e.g. Cloudflare Web Analytics — free, no cookies, no
  Personally Identifiable Information) to the deployed v2 build so the
  community-shared release surfaces basic numbers: total page views, unique
  visitors per week, which pages get loaded most. Useful for the v2 generic
  version where there isn't direct contact with every user. Skip on personal
  v1 — at friends-and-family scale, asking is more reliable than a dashboard,
  and adding tracking subtly changes the project's character.
