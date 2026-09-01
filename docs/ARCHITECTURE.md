# Architecture Overview

PoribohonBD is a public-facing transport information and journey-intelligence platform. This document intentionally provides a high-level description only.

## Public layers

- Public web experience for transport and journey information
- Public APIs/endpoints that are intentionally exposed by the production service
- Source-aware/public information presentation
- Safety and operational information surfaces

## Engineering boundary

The production application and its deployment pipeline remain in the private project repository. This public evidence repository is not a source-code mirror and does not expose implementation secrets or private infrastructure.

## Verification principle

Architecture statements published here should stay at the level supported by the public product and verified project records. Internal implementation details are not inferred from the public UI.
