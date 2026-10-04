# Report of revisions

This document lists every modification requested by the three external reviewers and how it was handled. Pages in the comment refer to the manuscript sent for review and pages in the reply refer to the revised manuscript.

## Reviewer 1

1. **Discuss more thoroughly what the methods could achieve with fewer, scarcer, or more fragmented data than those of Barcelona.**
  (p. 167). A new limitation was added at the start of *Limitations* (Sec. 10.4). For each contribution it states the minimum data required and how the method would degrade with less data quality or volume.
2. **Chapters 7, 8, and 9 (operations) are more compact than Chapter 6 (station planning) and could be improved editorially.**
  (pp. 109–151). Those chapters were not lengthened to match Chapter 6 as they follow the content of already published papers. However, they have been revised to clarify where the text was hard to follow (see the annotated-PDF comments below).

## Reviewer 2

### General comments

1. **Some sections of the introduction repeat content and findings; revise to avoid this (also pp. 30, 33, and 110 in the annotated PDF).**
  (pp. 30, 33, 34, and 110). Repeated passages now point back to the first mention instead of restating the same facts.
2. **Do not repeat a full introduction and state of the art in each chapter. The manuscript should have a single introduction and a single state-of-the-art section; contributed chapters may keep only a short contextual paragraph and chapter-specific data.**
  This was not followed. The three contributions share a city and a system, but they are not sequential steps of one study: station planning, mobility and batteries, and predictive maintenance each stand on their own. For that reason each chapter keeps the literature that belongs to it, next to the methods and results to make the chapter easier to follow, while the common background remains in Part II.
3. **Define acronyms the first time they are used, not only in the list of abbreviations (also p. 69 in the annotated PDF).**
  Acronyms are already defined at first appearance and collected in the list of abbreviations.
4. **Add personal thoughts and opinions about bike-sharing in the closing reflections.**
  A first-person section, *A personal note* (Sec. 10.6), was added before the formal closing. It gives a personal view of bike-sharing and of *Bicing* in Barcelona, of the role of data and AI, and of the political and operational will needed to improve the service.

### Annotated PDF (comments in red)

1. **Define rebalancing (p. 42).**
  (p. 14). A definition was added at first use, in *What are BSSs?*
2. **Wrong figure panel for *Bicing* stations (p. 67).**
  (p. 67). The reference was changed from Figure III.1C to Figure III.1F.
3. **Introduce how citizens use *Bicing*; consider moving that text here (p. 67).**
  (p. 67). The detailed account of how citizens use *Bicing* stays in Part IV, where the system and its mobility patterns are developed. From the Barcelona use case in Part III, the reader is now pointed there, so that use of the system can be followed without repeating the same text.
4. **Neither experiment uses solely the bike network? (p. 77).**
  (p. 77). The text now states that the OSM ‘bike’ network includes all streets where cycling is permitted.
5. **No indent after the equations (pp. 80, 122, and 129).**
  (pp. 80, 122, and 129). The paragraph break between each equation and the following “where” line was removed.
6. **Do not overclaim the gain from α in scenario S1 (p. 91).**
  (p. 91). “Substantially boosts” was replaced by “increases” ($S_{\mathrm{acc}}$ from 0.75 to 0.91).
7. **Compare the station-planning results with other approaches (p. 98).**
  (p. 97). A full comparison was not added in the Results. It was added as future work in the Discussion.
8. **Rename “History and evolution” to “Introduction” (p. 105).**
  (p. 105). The original title was not a good fit, as the reviewer noted, but it was not replaced with “Introduction”. Part III presents *Barcelona as a case study* as a continuous text, without subsection titles. *Bicing as a case study* in Part IV is the parallel opening of the operational chapters, so the titles were removed and transitions were added. The two use-case sections now have the same form.
9. **Correct the y-axis of Fig. 7.1A and clarify the colour scale of Fig. 7.2 (pp. 113–114).**
  (pp. 113–114). The y-axis of Fig. 7.1A now matches the caption (weekly trips per bike). The colour-bar of Fig. 7.2 is labelled, and the caption defines trip elevation.
10. **The incoming/outgoing asymmetry is unclear; control the elevation analysis by hour of day as well? (pp. 114–115).**
  (pp. 114–115). The explanation was rewritten: arrivals at high-altitude stations are mostly uphill; departures are mostly downhill. The analysis was not split by hour of day. Daily peaks are already shown earlier in the chapter, and the point of this figure is the relationship between bike model and height, which would be lost if the same data were cut again by time of day.
11. **Better introduce the battery chapter and contextualize the location-prediction objective (pp. 117 and 119).**
  (pp. 118 and 120). The opening now explains why a mobility model is needed, then outlines the chapter. A sentence was added to Sec. 8.2.2: battery forecasting needs future locations, not those already observed.
12. **Model accuracy should sit closer to the model; how is the predicted battery variation in Fig. 8.3B obtained? (pp. 123 and 127).**
  (pp. 122 and 127). The fit was left in Results, because it is a result, and the optimal parameters were moved next to it so that the model and its accuracy sit together. The caption of Fig. 8.3 now states that battery variation is the change in battery level between consecutive snapshots.
13. **For chains, the comparison is in distance; in time the conclusion may differ (p. 144).**
  (p. 143). Both measures are now stated. The wheel-spoke comparison notes that m-bike units are too scarce to compare.
14. **Table 9.3 is confusing; Table 9.4 is missing units (pp. 147–148).**
  (pp. 147–148). Table 9.3 reports means and standard deviations, not the strength of the fit. The Pearson correlation between predicted and actual survival (0.96–0.97) is given in the text and shown in Fig. 9.3. The caption of Table 9.3 now also says that, for censored units, “actual survival” is the observed time, not the unknown failure date. In Table 9.4 the error row had no unit; it is now labelled as the absolute difference, in days.
15. **Cumulative distance is the top SHAP predictor; is that related in the way claimed? (p. 150).**
  (p. 150). The text has been revised to better explain why cumulative distance comes first in the ranking and why the relation is positive.

## Reviewer 3

1. **No modifications.**
  No changes were made in response to this report.

