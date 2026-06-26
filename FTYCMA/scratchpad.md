# Doenet Talk — build notes

## Format decision
- Deliverable MUST import into slides.com → build a **real reveal.js deck** (standalone HTML, CDN reveal core + custom dark theme). NOT a deck-stage / DC (those won't import).
- Motion is **import-safe only**: reveal-native fragments, auto-animate, slide/zoom/fade transitions, background transitions. No bespoke JS animation.
- 1920×1080, center:false, sections styled as full-height flex frames.

## System — "Graph & Ink"
- BG: deep navy `#0d1626` (primary), darker `#091020` (dividers/demos).
- Graph-paper grid overlay, faint: `rgba(120,160,220,.06)`.
- Accents: teal `#34d4bf` (primary), coral `#fb7185` (emphasis). Same chroma family.
- Text: `#eaf0fa` primary, `#90a4c4` muted.
- Type: IBM Plex Sans (display/body, 600/700) + IBM Plex Mono (labels, times, data, URLs, slide tags). Open-source fonts = on-theme with FOSS.
- Motifs: graph grid, route polyline (echoes the commute + "plotting"), mono tags `[ 03 / 64 ]`.

## Slide / title sequence (chapters readable alone)
1. A story about two students
2. They couldn't afford the book
3. So this was their morning
4. The commute (step-reveal over map)
5. Two hours. Each way.
6. I never forgot what that cost  (pivot; "this was me/my friend" → speaker notes)
7. TITLE — Finally, Tech You Create, Modify & Adapt
8. Hello — and thank you  (PBSC, no photo)
9. On the surface
10. Underneath the surface
11. Your turn: A Tale of Two Squares  (live embed + URL, 7 min)
12. What I actually believe  (divider/framing)
--- TOP-DOWN VIEW ---
13. (divider) Top-Down View
14. Free and open source is better
15. Coerced adoption is bad
16. Productive struggle is good
17. Working in groups is good
18. I want to hold the marker less
19. Show me the notation first
20. Equations are not expressions
21. (demo) Live Demo 01
22. (demo) Live Demo 02
--- PRE-CLASS PREP ---
23. (divider) Pre-Class Prep
24. Nothing here is AI-proof
25. Earn the next step
26. Ideas should return unexpectedly
27. (demo) Cascade: Radical Equations
28. (demo) Grid Sum Pro Max
29. (demo) Parsons: Order of Operations
--- IN CLASS ---
30. (divider) In Class
31. Discovery before vocabulary
32. Make it costly not to take notes
33. (demo) Pretzels with Distractors
34. Everyone gets a different problem
35. Hide things in plain sight
36. Worksheets are necessary
37. (demo) Factoring Crossword
38. (demo) Algebra Food Truck
39. Don't make them wait for me
40. (quote) Bernard Suits — unnecessary obstacles
41. (demo) Create Your Own Equation
42. (demo) KenKen
43. (demo) The Last of Us
--- ASSESSMENT ---
44. (divider) Assessment
45. Customized beats mass-produced
46. Same problem, new numbers — tests nothing
47. Can you solve something semi-novel?
48. (demo) Linear Function FEQ
49. (demo) The Compound / PDF
--- THE PUDDING ---
50. (divider) The Pudding
51. 35% → 55%
52. 94% follow-through, three institutions
--- JOIN US ---
53. (divider) Join Us
54. FOSS people are good people
55. Good acts beget good acts
56. (CTA) Come build with us — July 14–17
57. (close) Tech you create, modify & adapt

## Claim layout (parallel across all)
mono kicker `BELIEF 0X / 20` · large statement · optional supporting line as fragment · accent rule. Bottom breathing room intentional.

## Demo slide (full-bleed, name only)
darker bg, faint grid, mono kicker `LIVE DEMO ↪ doenet`, big activity name, thin accent underline reveals. Presenter switches to live activity.
