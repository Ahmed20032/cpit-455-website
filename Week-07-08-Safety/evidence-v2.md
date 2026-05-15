# Week 07-08 Evidence V2

## Topic
Safety engineering, hazards, accidents, damage, ALARP, and fault tree thinking.

## Final V2 Submission
- I defined the main portfolio hazard as "required evidence is missing, unclear, or inaccessible during review."
- A possible accident is an incomplete or invalid submission.
- The damage is losing marks, wasting review time, or giving a weak impression of the work quality.

## Text Fault Tree
- Top event: portfolio review fails
  - Required evidence is missing
  - Reflection file is missing
  - Reviewer cannot verify the proof
    - Unclear file naming
    - No evidence label or explanation
  - Link exists but points to the wrong location
  - Final project proof is not attached before submission

## Fault Tree Analysis (Deductive)
- Start from the top event: `portfolio review fails`.
- Deduce the direct failure paths under it:
  - Required evidence is missing
  - Reflection is missing
  - Reviewer cannot verify the proof
  - Link points to the wrong target
  - Final project proof is absent
- In the OR example, any one direct cause can trigger the top event.
- One branch is expanded with an `AND` gate:
  - Unclear file naming
  - No evidence label or explanation
- In the AND example, both underlying issues must happen together before proof verification fails.
- This is deductive because the analysis begins with the failure outcome and works downward to the possible causes.

## ALARP Controls
- Use one fixed folder structure
- Use direct links from the main page
- Keep one evidence V2 file per week
- Add a reflection file every week
- Review the portfolio once before submission day

## Safety Case Statement
The portfolio is safer for review because it separates direct OR failure paths from one combined AND case, making the weak points easier to understand and control.
