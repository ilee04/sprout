# Sprout — portfolio project starter

An independent, AI-assisted UI/UX concept exploring sustainable home technologies. This is a working prototype, not a commissioned project, a shipped business, or completed user research.

## Problem hypothesis
People exploring unfamiliar home technology may struggle to distinguish what a product does from whether it fits their home. This hypothesis still needs user research.

## Core task
Explore options → narrow by interest and installation needs → understand trade-offs → compare up to three concepts → save a shortlist.

## Design decisions to discuss
- Plain-language product descriptions and consistent setup labels support scanning.
- Filters remain visible and include a reset action and a no-results state.
- Comparison puts limitations next to benefits rather than hiding them.
- The two-question finder asks only for information that changes the results.
- Saving needs no account. The interface explains that choices are browser-local.
- Semantic buttons, labeled inputs, visible focus styles, a skip link, native modal dialogs, status announcements, and reduced-motion support are implemented. These are design provisions, not a claim of certified accessibility.
- Illustrative product data is labeled. No invented impact scores, research findings, customer counts, or conversion results are included.

## A usability study you can conduct
Recruit 3–5 people with different housing situations. Ask consent before taking notes or recording. Avoid explaining the UI during tasks.

1. You rent an apartment and want to understand energy use. Find an option that seems suitable and explain why.
2. Compare two options and describe one limitation of each.
3. Save an option, leave the shortlist, and find it again.
4. Search for something unavailable and recover to a useful result.
5. Complete a discovery task using only the keyboard.

Record completion, points of hesitation, misunderstandings, and participant language. Separate observations from interpretation. Do not add success rates until measured. Revise the design based on actual findings and document before/after screenshots.

## Honest interview framing
“I am developing Sprout as a personal UX concept. I used AI assistance to build this interactive prototype. My next step is testing whether its comparison criteria and guided finder actually help people make sense of unfamiliar technologies.” Update this wording to accurately reflect the work you personally do.

## Local use
Open dist/index.html directly, or serve dist with a static HTTP server. No build or install is required. Fonts load from Google Fonts, with local sans-serif fallbacks. No analytics or accounts are included.
