# NYBSJ Admin Portal — Mockup

Interactive UI mockup of the NYBSJ admin portal for stakeholder review.

**Live preview:** https://inoviscope.github.io/nybsj-admin-mockup/

## What this is

A static HTML mockup demonstrating the planned admin portal for NYBSJ practice staff to review patient intake submissions. Companion to the patient intake mockup at https://inoviscope.github.io/nybsj-intake-mockup/.

## Screens

1. **Login** — email + password (mock; MFA placeholder)
2. **Submissions queue** — table of intake submissions, auto-filtered by the signed-in admin's allowed locations
3. **Submission detail** — read-only view of a full intake (demographics, insurance, claim details, ROS, acknowledgments + signature, audit log)

## Admin scope (3 tiers)

The mockup demonstrates all three admin tiers via a persona switcher in the top nav:

| Tier | Demo persona | Locations visible |
|---|---|---|
| Single-location | Mayra Bonilla (`mayra@nybsj.com`) | Massapequa Park only |
| Multi-location super-admin | Evelyn Rojas (`evelyn@nybsj.com`) | 9 locations |
| General admin | `admin@nybsj.com` (placeholder, pending NYBSJ confirmation) | All locations (incl. deferred) |

Patient submissions are mock data only. No real PHI.

## Status

- Built 2026-05-01 as v0.1 for Malese + practice manager + Brian (GoImage) review.
- Companion mockup to `inoviscope/nybsj-intake-mockup`.
- Not production code. The real admin portal lives in a private repository.
