# fixture

Fixture repository for Entire's daily acceptance journeys
([entirehq/acceptance](https://github.com/entirehq/acceptance)).

Every day the onboarding journey mirrors this repo into the staging
environment, pushes one heartbeat commit here to exercise the
webhook-driven sync path, verifies the mirror converged, and tears the
mirror down again.

**This repo is intentionally public and intentionally boring.** It contains
no code — just this README and a heartbeat file that changes once a day.
Safe to ignore.
