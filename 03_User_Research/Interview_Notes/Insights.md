# SkyPath — Research Insights

## 1. Overview

The research synthesis converts the SkyPath research objectives, competitive observations and planned user investigation into a set of actionable UX insights.

The purpose of this document is to identify recurring themes that can guide the subsequent persona, journey-mapping, information-architecture and interaction-design stages.

The insights should be treated as design hypotheses until supported by direct participant evidence.

---

# 2. Insight 01 — Travellers Compare More Than Price

Flight selection is rarely determined by ticket price alone.

Relevant decision factors can include:

- Departure time
- Arrival time
- Journey duration
- Number of stops
- Airline
- Baggage allowance
- Fare flexibility
- Airport convenience
- Seat availability

### Design implication

SkyPath should allow users to compare multiple decision factors without forcing them to navigate between different screens.

---

# 3. Insight 02 — The Cheapest Flight Is Not Always the Most Valuable

A lower advertised fare may become less attractive when additional costs or restrictions are considered.

Potential additional considerations include:

- Baggage
- Seat selection
- Change restrictions
- Cancellation conditions
- Additional services

### Design implication

SkyPath should communicate the relationship between price and included value clearly.

---

# 4. Insight 03 — Fare Differences Require Explanation

Multiple fare options can create uncertainty when users understand the price difference but not the practical difference.

Users need to understand:

- What is included
- What is excluded
- What flexibility is provided
- What baggage is included
- Which restrictions apply

### Design implication

Fare comparison should focus on meaningful differences rather than presenting fare names and prices alone.

---

# 5. Insight 04 — Information Overload Can Increase Decision Difficulty

Flight booking contains a large amount of information.

Presenting all available information simultaneously can make comparison harder rather than easier.

### Design implication

SkyPath should use:

- Information hierarchy
- Progressive disclosure
- Grouped content
- Clear visual prioritisation
- Expandable details

The goal is to preserve useful information while reducing unnecessary cognitive load.

---

# 6. Insight 05 — Users Need Persistent Context

The booking process contains several interconnected decisions.

Important information can include:

- Selected flight
- Travel dates
- Passenger count
- Fare
- Baggage
- Seat
- Current total

### Design implication

Critical booking information should remain visible or easily accessible throughout the booking journey.

---

# 7. Insight 06 — Optional Services Should Not Compete With Core Decisions

Seats, baggage and additional services can be useful, but they are not equally important to every traveller.

### Design implication

SkyPath should clearly distinguish:

**Required booking information**

from

**Optional services**

The user should remain in control of whether optional services are added.

---

# 8. Insight 07 — Repetitive Data Entry Creates Friction

Passenger information is an important part of the booking process, but repeatedly entering similar information can increase effort and error risk.

### Design implication

A future SkyPath implementation could support reusable traveller information while giving users control over what information is stored and reused.

---

# 9. Insight 08 — Confidence Is an Important Booking Outcome

Completing a transaction is not the only measure of a successful booking experience.

Users should also feel confident that:

- The correct flight was selected
- The fare is understood
- The passenger information is correct
- The baggage requirement is satisfied
- The total price is understood
- The booking can be managed afterwards

### Design implication

The final review stage should provide a clear opportunity to verify all major decisions before payment.

---

# 10. Insight 09 — Booking Does Not End at Payment

The traveller's relationship with the product continues after the booking has been completed.

Post-booking needs may include:

- Itinerary access
- Booking reference
- Flight information
- Seat information
- Baggage information
- Check-in
- Changes or cancellation

### Design implication

SkyPath should treat confirmation as a transition into post-booking management rather than the end of the experience.

---

# 11. Insight 10 — Flexibility Can Be Valuable but Can Also Increase Complexity

Flexible search features can help users discover better options.

However, additional choices can also increase the number of decisions users need to make.

### Design implication

Flexibility should be introduced progressively.

Users who want a straightforward search should be able to complete one without navigating through advanced options.

---

# 12. Insight 11 — Trust Depends on Transparency

Users are more likely to feel confident when the interface clearly communicates:

- Price
- Fare conditions
- Included services
- Booking details
- Payment amount
- What happens next

### Design implication

SkyPath should avoid hiding important decision information behind unnecessary interactions.

---

# 13. Insight 12 — Different Travellers Have Different Priorities

A traveller booking a low-cost student trip may prioritise price.

A business traveller may prioritise time.

A family traveller may prioritise baggage and seating.

A frequent traveller may prioritise efficiency.

### Design implication

SkyPath should provide flexible comparison criteria rather than assuming that every traveller evaluates flights in the same way.

---

# 14. Emerging Behavioural Themes

The research framework currently identifies six major themes.

## Theme 01 — Decision Confidence

Users need enough information to feel comfortable committing to a booking.

## Theme 02 — Price Transparency

The relationship between advertised price and final cost should remain understandable.

## Theme 03 — Comparison

Users need to evaluate several flight attributes simultaneously.

## Theme 04 — Cognitive Load

Complex information should be structured rather than simply removed.

## Theme 05 — Booking Continuity

Important decisions should remain connected across the journey.

## Theme 06 — Post-Booking Support

The experience should remain useful after payment.

---

# 15. Insight-to-Opportunity Mapping

| Research Insight | User Need | Design Opportunity |
|---|---|---|
| Travellers compare multiple factors | Easy comparison | Structured comparison cards |
| Cheapest is not always best | Understand value | Effective-cost visibility |
| Fare differences can be confusing | Understand trade-offs | Fare comparison |
| Information overload increases difficulty | Manage complexity | Progressive disclosure |
| Users need persistent context | Remember decisions | Persistent itinerary summary |
| Optional services add decisions | Maintain control | Separate add-on stage |
| Repetitive entry creates friction | Reduce effort | Traveller profiles |
| Confidence matters before payment | Verify decisions | Booking review |
| Booking continues after payment | Manage travel | Post-booking dashboard |
| Flexibility can increase complexity | Explore without overload | Progressive flexible search |

---

# 16. Research Hypotheses

The following hypotheses should be validated through direct user research and usability testing.

### H1

Users will make faster and more confident decisions when flight comparison includes the attributes most relevant to their travel priorities.

### H2

Users will have greater confidence when fare differences and included services are presented in a structured comparison.

### H3

Showing the effective booking cost before payment will reduce uncertainty about the final transaction.

### H4

Persistent itinerary context will reduce the need for users to remember previous booking decisions.

### H5

Separating optional services from mandatory booking steps will reduce perceived complexity.

### H6

A structured final review will increase confidence before payment.

### H7

Post-booking access to itinerary and travel information will improve the continuity of the overall experience.

---

# 17. Evidence Status

The current insights should be interpreted according to their evidence source.

| Insight Category | Current Status |
|---|---|
| Competitive observation | Supported by competitive analysis |
| UX principle | Supported by established usability principles |
| User behaviour | Requires participant validation |
| User preference | Requires participant validation |
| Design hypothesis | Requires usability testing |
| Final product decision | To be validated |

This distinction prevents assumptions from being presented as confirmed user research findings.

---

# 18. Research-to-Design Traceability

The synthesis establishes the following relationship:

**Research Question**

→

**Evidence**

→

**Insight**

→

**User Need**

→

**Design Opportunity**

→

**Design Decision**

→

**Usability Validation**

This traceability will be maintained throughout the SkyPath design process.

---

# 19. Key Insight

The strongest emerging insight is that flight booking is fundamentally a **decision-support problem**.

Travellers do not simply need access to flight information.

They need to understand the trade-offs between available options well enough to make a confident decision.

This leads to the central SkyPath research hypothesis:

> **A flight-booking experience should reduce uncertainty by making the most important trade-offs visible at the moment they influence the user's decision.**

---

# 20. Next Research Stage

The next stage is to validate these insights through participant evidence.

The findings should then be synthesised through:

**Participant Evidence**

→

**Affinity Mapping**

→

**Behavioural Patterns**

→

**Validated Insights**

→

**Personas**

→

**Journey Map**

→

**Design Requirements**

The final SkyPath interface should reflect validated user needs rather than assumptions alone.
