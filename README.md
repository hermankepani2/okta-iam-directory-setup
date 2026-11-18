# okta-iam-directory-setup
# Okta IAM - Identity and Access Management Directory Setup - Kepani Digital

## What I built

- Okta Integrator Free org for Kepani Digital, admin access with Okta Verify
- Test User (test.user@kepanidigital.org) with a forced password change on first login
- Kepani Staff group — a test group for Kepani Digital staff, for learning Okta
- Kepani Digital bookmark app for kepanidigital.org
- App assigned to the group, not to an individual user

## How I proved it

Signed out as admin, signed in as Test User in a normal browser window, changed the password, enrolled Okta Verify as a second account, and opened kepanidigital.org from the app tile on the user dashboard. No Incognito or private browsing was used — see the accessibility rule in the SOP.

## Why it matters

Access follows the group. Add a person to the group and they get its apps. Remove them and the access goes. That is the foundation of Identity and Access Management (IAM), and the first hands-on project in my Identity and Access Management (IAM) learning path.

Full SOP: Okta IAM - Identity and Access Management Directory Setup SOP (PDF, kept with my project files). No passwords or org credentials are included in this project entry.
