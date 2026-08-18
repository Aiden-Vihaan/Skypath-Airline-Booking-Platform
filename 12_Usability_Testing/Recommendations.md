# SkyPath — UX Recommendations

## 1. Purpose

The recommendations document translates usability evidence and research observations into actionable design priorities.

Recommendations should be prioritised according to user impact, frequency, implementation complexity, and strategic importance.

---

## 2. Prioritisation Framework

| Priority | Definition |
|---|---|
| P0 — Critical | Prevents successful completion or creates serious trust/accessibility problems |
| P1 — High | Significantly affects efficiency, comprehension, or confidence |
| P2 — Medium | Creates friction but does not prevent task completion |
| P3 — Low | Minor refinement with limited behavioural impact |

---

## 3. Recommendation Areas

### REC-001 — Strengthen Fare Comparison

**Priority:** P1

Fare options should expose the most decision-relevant differences using concise, scannable information.

The design should avoid forcing users to repeatedly open or inspect individual fare options to understand important differences.

**Recommended focus:**

- Price
- Baggage
- Seat selection
- Refund/change conditions
- Included services

**Validation:**  
Compare task completion and comprehension during fare-selection testing.

---

### REC-002 — Make Baggage Costs Explicit

**Priority:** P1

Baggage information should clearly distinguish included allowance from optional paid baggage.

Users should be able to understand the resulting price before confirming their selection.

**Recommended focus:**

- Weight
- Number of bags
- Passenger association
- Included versus additional baggage
- Price impact

---

### REC-003 — Maintain Persistent Cost Visibility

**Priority:** P1

The interface should provide clear feedback whenever an optional service changes the booking price.

This reduces the risk of users reaching payment and discovering an unexpected total.

---

### REC-004 — Improve Error Recovery

**Priority:** P1

Users should be able to return to previous booking stages without losing information unnecessarily.

Where a change affects price or availability, the interface should clearly communicate the consequence of the change.

---

### REC-005 — Strengthen Post-Booking Navigation

**Priority:** P2

Functions such as check-in, booking management, refund, and loyalty should remain discoverable after the booking process has been completed.

The navigation model should distinguish between:

- Booking
- Manage trip
- Check-in
- Support
- Loyalty

---

### REC-006 — Support Family Travel Needs

**Priority:** P2

Family-specific needs should be surfaced at relevant points rather than isolated in a separate section.

Relevant considerations include:

- Child passengers
- Seating
- Baggage
- Food
- Travel assistance
- Accommodation/support information where applicable

---

### REC-007 — Improve Accessibility Discoverability

**Priority:** P1

Accessibility requirements should be available at an appropriate stage of the booking journey and should not depend entirely on users finding a support page.

The interface should communicate available assistance clearly and avoid ambiguous terminology.

---

### REC-008 — Preserve Responsive Consistency

**Priority:** P2

The mobile experience should preserve the conceptual structure of the desktop booking journey while adapting interaction patterns to smaller screens.

Responsive design should not simply scale desktop components down.

Particular attention should be given to:

- Navigation
- Flight comparison
- Fare comparison
- Seat maps
- Forms
- Booking summary
- Error messages

---

## 4. Recommended Validation Sequence

The next usability iteration should prioritise:

1. Flight and fare comparison
2. Baggage selection
3. Seat selection
4. Booking-cost review
5. Error recovery
6. Post-booking navigation
7. Family travel scenarios
8. Accessibility scenarios

---

## 5. Definition of Done

A recommendation should not be considered validated merely because the interface has been visually updated.

A recommendation is considered validated when:

- The design change has been implemented.
- The relevant task has been retested.
- The intended usability problem has measurably reduced or disappeared.
- No significant new usability problem has been introduced.
- The decision and evidence have been recorded in the iteration log.

---

## 6. Closing Principle

SkyPath should evolve through evidence-based iteration rather than aesthetic refinement alone.

The objective of future iterations is to reduce cognitive load, increase transparency, improve accessibility, and support confident decision-making throughout the complete airline-booking journey.
