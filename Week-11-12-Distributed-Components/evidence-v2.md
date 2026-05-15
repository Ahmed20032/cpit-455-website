# Week 11-12 Evidence V2

## Topic
Distributed systems thinking, component-based engineering, and architecture design.

## Final V2 Submission
- I described the portfolio using simple architectural components:
  - Main web page for navigation
  - Weekly folders for content storage
  - Evidence files for proof
  - Reflection files for learning record
  - Assets such as the profile image
- This separation makes the portfolio easier to maintain and easier to verify.

## Component-Based View
- UI component: `Portfolio_AhmedAljohani.html`
- Content component: weekly Markdown evidence files
- Reflection component: weekly reflection files
- Support component: project folder for final packaging

## Architecture Benefit
- One broken item does not force all other weekly content to change.
- Navigation stays simple because the main page only indexes the evidence.
- The same model can later scale to the final project documentation pack.
