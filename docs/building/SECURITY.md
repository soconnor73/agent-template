# Data sensitivity
What data this system touches and its classification (public, internal,
confidential, regulated). Be specific — "user data" is not a classification.

# Auth model
Who/what can authenticate, how, and what each role/principal can access.
Note any trust boundaries (e.g. "requests from service X are trusted,
requests from the public internet are not").

# Threat model
Realistic threats for this project specifically — not a generic OWASP
checklist. What's actually at risk here, and what's out of scope and why.

# Known constraints
Compliance requirements, required encryption, retention limits, anything
that shapes how code must be written rather than just what it does.
