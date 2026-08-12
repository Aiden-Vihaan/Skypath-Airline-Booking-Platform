# Decision Log

This document records the major design decisions made during the development of the SkyPath Airline Booking Platform.

The purpose is not to document every small visual adjustment. Instead, it captures decisions that affected the structure, interaction model, information hierarchy or overall direction of the experience.

Keeping a decision log also makes it easier to look back at the project and understand how the interface evolved.

---

## Decision 01 — Treat the booking experience as a continuous journey

**Decision:**  
The SkyPath experience will be designed as one connected booking journey rather than as a collection of independent screens.

**Reasoning:**  
Users move through a sequence of related decisions. A choice made during flight selection can affect fare selection, seat selection, optional services and the final price.

Designing these stages independently could create inconsistencies and force users to repeatedly reconstruct information.

**Design implication:**  
The major screens should share consistent terminology, hierarchy, navigation patterns and summaries.

**Status:** Accepted

---

## Decision 02 — Prioritise flight comparison

**Decision:**  
Flight comparison will receive strong emphasis in the search-results experience.

**Reasoning:**  
Selecting a flight often requires users to compare more than just price. Departure time, arrival time, duration, stops and baggage/fare conditions can all influence the decision.

**Design implication:**  
Search-result cards should expose meaningful comparison information without requiring users to open every flight individually.

**Status:** Accepted

---

## Decision 03 — Separate flight selection from fare selection

**Decision:**  
The selected flight and the fare associated with that flight should be treated as two related but distinct decisions.

**Reasoning:**  
A flight schedule and a fare package answer different questions. Combining them too early can make it difficult for users to understand why prices differ.

**Design implication:**  
The interaction should first establish which flight the user wants and then help them understand the available fare options.

**Status:** Accepted

---

## Decision 04 — Make pricing transparency a core design principle

**Decision:**  
Price information should remain visible at important decision points throughout the booking journey.

**Reasoning:**  
Users need to understand how selections affect the total cost before reaching the final payment stage.

Optional services such as baggage, seats or other additions should not feel like unexpected charges.

**Design implication:**  
Price summaries should be present at appropriate stages and the final review should clearly communicate the amount being paid.

**Status:** Accepted

---

## Decision 05 — Distinguish mandatory information from optional choices

**Decision:**  
Required booking information and optional services should be visually and conceptually separated.

**Reasoning:**  
Mixing mandatory information with optional purchases can make the journey feel longer and make users uncertain about what they actually need to complete.

**Design implication:**  
Passenger information should be handled as part of the core booking flow, while optional services should be introduced separately.

**Status:** Accepted

---

## Decision 06 — Use progressive disclosure for complex information

**Decision:**  
Not every available piece of information should be presented at the same level of prominence.

**Reasoning:**  
Airline booking contains a large amount of information. Presenting everything simultaneously can increase cognitive load.

Users should first see the information required to make the current decision, with additional detail available when needed.

**Design implication:**  
Secondary information can be progressively revealed through structured sections, expandable content or detail views where appropriate.

**Status:** Accepted

---

## Decision 07 — Introduce low-fidelity wireframes before visual refinement

**Decision:**  
The interface structure should be explored through low-fidelity wireframes before final visual styling.

**Reasoning:**  
Visual polish can make structural problems harder to recognise. Working in low fidelity allows the project to focus on hierarchy, content grouping and interaction flow without prematurely committing to visual details.

**Design implication:**  
Wireframes become an intermediate stage between information architecture/user flows and the high-fidelity interface.

**Status:** Accepted

---

## Decision 08 — Maintain a consistent interaction language

**Decision:**  
Repeated interaction patterns should behave consistently across the platform.

**Reasoning:**  
Users should not have to relearn how buttons, cards, selection controls, navigation or feedback work from one stage to another.

**Design implication:**  
Reusable components and defined interaction states will be used to support consistency.

**Status:** Accepted

---

## Decision 09 — Treat the review stage as a confidence checkpoint

**Decision:**  
The booking-review stage should provide a clear opportunity to verify important selections before payment.

**Reasoning:**  
The user has accumulated several decisions by this point: flight, fare, passenger information, seats and optional services.

The review stage should therefore help users verify these decisions rather than simply displaying a final price.

**Design implication:**  
The review interface should summarise the major booking components and make important information easy to scan.

**Status:** Accepted

---

## Decision 10 — Provide clear confirmation after booking

**Decision:**  
The confirmation experience should communicate both completion and what the user can do next.

**Reasoning:**  
A successful payment is not the end of the user's relationship with the booking. The traveller may need to retrieve the itinerary, remember the booking reference or access the trip later.

**Design implication:**  
The confirmation state should provide essential booking information and clear pathways to post-booking access.

**Status:** Accepted

---

## Decision 11 — Consider accessibility during design rather than after completion

**Decision:**  
Accessibility considerations should be incorporated throughout the design process.

**Reasoning:**  
Accessibility is closely connected to hierarchy, interaction states, typography, colour, feedback and information structure. Treating it as a final visual check would miss opportunities to improve the underlying experience.

**Design implication:**  
The project considers contrast, readable hierarchy, non-colour-dependent communication, clear labels, focus states and actionable error feedback.

**Status:** Accepted

---

## Decision 12 — Avoid unsupported performance claims

**Decision:**  
The project documentation will distinguish between design intentions, hypotheses and validated findings.

**Reasoning:**  
Because SkyPath is a conceptual UX/UI project, claims such as improved conversion rate, reduced booking time or increased completion rate should not be presented as factual results without appropriate evaluation evidence.

**Design implication:**  
The case study will describe intended outcomes and design hypotheses clearly, while measured results will only be reported when they have actually been evaluated.

**Status:** Accepted

---

## Decision 13 — Keep the project focused on UX and interaction design

**Decision:**  
The project will prioritise the user experience, interaction model and interface design rather than attempting to simulate a complete production airline system.

**Reasoning:**  
A production airline platform would involve complex operational systems, inventory, payment infrastructure, authentication, airline integrations and other technical considerations beyond the scope of this design study.

**Design implication:**  
The repository focuses on the design process and supporting artefacts while clearly distinguishing conceptual functionality from implemented functionality.

**Status:** Accepted

---

## Decision 14 — Document the reasoning behind the final interface

**Decision:**  
The final case study should explain not only what was designed, but why key design decisions were made.

**Reasoning:**  
A polished interface alone does not demonstrate the complete design process. Showing the relationship between user needs, research-informed insights, structure, interaction decisions and final screens provides stronger evidence of design thinking.

**Design implication:**  
The final documentation will include design rationale, iteration, reflection and limitations alongside the final interface.

**Status:** Accepted

---

## Decision 15 — Treat iteration as part of the design process

**Decision:**  
The project will document meaningful changes rather than presenting the final design as the only version that existed.

**Reasoning:**  
Design develops through exploration. Showing how a structure or interaction changed can reveal the reasoning behind the final solution.

**Design implication:**  
Relevant wireframes, iterations and design decisions will be retained as supporting evidence where they contribute to understanding the process.

**Status:** Accepted

---

# Decision Review

The decision log is intended to remain a living document during the project.

If later research, prototyping or evaluation provides evidence that challenges an existing decision, the decision should be revisited rather than preserved simply for consistency.

A future entry should therefore need:
What changed
why it changed
What evidence informed the change
Which part of the experience was affected
Whether related artefacts need to be updated

This keeps the repository aligned with the principle that UX design is an iterative process rather than a linear sequence of predetermined answers.
