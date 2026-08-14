# Skyscanner — Competitive Research

## 1. Overview

Skyscanner is a travel search platform focused on helping users discover and compare flights across airlines and travel providers.

Its experience is particularly relevant to SkyPath because it places strong emphasis on price discovery, flexible travel planning and comparison across a large number of providers.

Skyscanner describes itself as a travel search engine and states that it compares flight deals from more than 1,200 airlines and travel providers. 

For this competitive analysis, the focus is on the flight-search and decision-making experience.

---

# 2. Competitive Role

Skyscanner represents the **travel comparison and price-discovery** category.

Its major strengths include:

- Cross-provider comparison
- Flexible-date discovery
- Destination exploration
- Price alerts
- Nearby-airport exploration
- Search filtering
- Travel-provider comparison
- Flexible booking options
- Saved travel options

This makes Skyscanner a particularly important benchmark for understanding how users can be supported when price and flexibility are major decision factors.

---

# 3. Core Search Experience

Skyscanner's flight search allows users to enter:

- Departure city or airport
- Destination city, airport or country
- Departure date
- Return date
- Number of travellers
- Cabin class

After searching, users receive a list of available flight options.

Skyscanner also provides filters such as number of stops and departure time. 1

### UX Observation

The basic search model is familiar and relatively direct.

However, Skyscanner's competitive differentiation becomes more apparent when users move beyond fixed searches into flexible exploration.

---

# 4. Flexible Date Discovery

Skyscanner provides a Flexible Dates or Whole Month experience that allows users to compare prices across multiple dates.

The interface can display prices in a calendar or grid so users can identify potentially cheaper travel dates at a glance. 2

### Strength

This transforms the date from a fixed input into a decision variable.

Instead of asking:

> "What is the price on this date?"

the experience can help answer:

> "Which date is likely to give me a better price?"

### SkyPath Implication

For flexible travellers, visual date comparison can reduce repeated searches.

However, the feature should clearly communicate that monthly prices may be indicative rather than guaranteed live prices.

Skyscanner explicitly states that prices shown in its flexible-date calendar can be based on recent searches and may change before booking. 3

---

# 5. Cheapest Month

Skyscanner allows users with flexible schedules to search across an entire month or identify a cheapest month.

This is particularly useful for budget-conscious travellers who have flexibility around their travel dates.

### UX Value

The feature reduces the number of individual searches required to discover a lower-cost travel period.

### Potential Trade-off

A broader search space can increase decision complexity.

Users may discover many attractive prices without having a clear way to determine which option best fits their other priorities.

### SkyPath Opportunity

SkyPath can combine price flexibility with other decision variables such as:

- Duration
- Stops
- Baggage
- Convenience
- Fare conditions

This would move beyond price discovery toward multi-factor decision support.

---

# 6. Everywhere Search

One of Skyscanner's most recognisable discovery features is **Everywhere**.

Users can specify their departure point without committing to a specific destination.

Skyscanner then presents destinations ordered by price. 4

### User Value

Everywhere is particularly useful for:

- Flexible travellers
- Budget travellers
- Exploratory travellers
- Users without a fixed destination
- Users looking for travel inspiration

### UX Observation

This reverses the traditional search model.

Traditional search:

**Destination → Dates → Flights**

Everywhere:

**Origin → Flexibility → Destinations**

### Design Learning

This demonstrates how a product can support users who have an intention but not a fully formed plan.

---

# 7. Search Filters

Skyscanner provides filters to narrow flight results.

Examples include:

- Number of stops
- Departure time
- Airlines
- Cabin class
- Region
- Other flight preferences

Skyscanner's documentation describes filtering as a way to help users find flights that better match their requirements. 5

### UX Strength

Filters reduce the number of options users need to evaluate simultaneously.

### Potential Challenge

Filters can become difficult to manage when many constraints are applied simultaneously.

Users may also lose awareness of alternatives that were excluded by their current filter configuration.

### SkyPath Principle

High-priority constraints should remain visible while secondary filters remain accessible without dominating the primary decision flow.

---

# 8. Flight Comparison

Skyscanner's core value proposition is based on comparing flights from multiple providers.

Users can select a flight and then see airlines and travel agencies through which they can book. 6

### Competitive Strength

The comparison model reduces the need to visit multiple airline websites independently during the discovery stage.

### UX Opportunity for SkyPath

Comparison should not stop at displaying different prices.

A useful comparison should help users understand:

- Total cost
- Duration
- Stops
- Baggage
- Fare conditions
- Booking flexibility
- Additional services

This reinforces the SkyPath focus on **meaningful comparison rather than simple price ranking**.

---

# 9. Price Transparency

Skyscanner currently promotes transparent pricing and states that the price shown during search represents the price users will pay, while also noting that prices can change because of availability and other factors.

Its help documentation explains that prices can change frequently and that indicative prices shown in flexible-date views are not guaranteed. 7

### UX Observation

Price transparency is particularly important for a comparison platform because users are making decisions based on relative cost.

If the displayed price changes later, trust can be affected.

### SkyPath Opportunity

SkyPath should distinguish clearly between:

**Displayed fare**

**Included services**

**Optional additions**

**Current total**

and

**Final payable amount**

The goal is to make price changes understandable rather than surprising.

---

# 10. Price Alerts

Skyscanner allows users to create Price Alerts for routes and dates they are interested in.

When prices change, users can receive notifications by email. 8

Skyscanner also allows users to manage their saved alerts through their account. 9

### UX Strength

Price alerts extend the relationship beyond a single search session.

The user does not need to repeatedly return to the platform and manually check the same route.

### SkyPath Opportunity

A future SkyPath experience could support similar decision continuity.

However, alerts should remain contextual and controllable rather than becoming excessive notifications.

---

# 11. Saved Flights

Skyscanner provides a Saved experience that allows users to retain flights they are interested in.

Its current product information describes Saved as a travel wishlist that can help users organise and compare flights and hotels by trip. 10

### UX Value

Saving reduces the need to repeat a search when the user is still considering alternatives.

### Design Learning

A user's journey does not necessarily follow:

**Search → Decide → Book**

It can instead be:

**Search → Compare → Save → Reconsider → Track → Book**

SkyPath can benefit from recognising this non-linear decision process.

---

# 12. Price Alert Limitations

Skyscanner's documentation provides an important example of a trade-off in its alert system.

Price Alerts are based on the selected route and dates and remember traveller count and direct-flight preference, but certain additional search filters are not carried into the alert. 11

### UX Observation

This illustrates a common challenge in persistent search systems:

The user's original search context is not always completely preserved.

### SkyPath Opportunity

If SkyPath introduces saved searches or alerts in the future, preserving important user constraints should be considered part of the experience design.

---

# 13. Nearby Airports

Skyscanner allows users to consider nearby airports as an alternative when searching for potentially lower fares.

The platform specifically identifies nearby airports as one method for finding more cost-efficient options. 12

### UX Strength

This increases the number of possible solutions without requiring users to manually search every nearby airport.

### Potential Risk

Airport flexibility can introduce:

- Additional ground travel
- Longer journeys
- Increased complexity
- Different departure locations

### SkyPath Principle

Alternative airports should therefore be presented with their practical trade-offs rather than only their price advantage.

---

# 14. Booking Handoff

Skyscanner primarily operates as a comparison and search platform.

After selecting a flight, users can be shown airlines and travel agencies where they can complete the booking. 13

Skyscanner explains that users will usually book directly with one of its airline or travel partners.

### UX Implication

This creates a transition between:

**Discovery**

and

**Booking**

The user may therefore move from Skyscanner's interface into another provider's experience.

### SkyPath Opportunity

SkyPath is designed around a more continuous booking journey:

**Search → Compare → Select → Configure → Review → Pay → Confirm → Manage**

Maintaining context throughout this journey becomes a central differentiating principle.

---

# 15. Flexible Booking Options

Skyscanner also promotes flexible flight options that can help travellers reduce risk when plans change.

The platform describes flexible flight deals as a way to help users avoid losing out when flights are changed or cancelled. 14

### UX Observation

Flexibility is not simply a product feature.

It is a risk-management decision.

Users may be willing to pay more for a fare if the additional flexibility provides meaningful protection.

### SkyPath Opportunity

Fare comparison should therefore make flexibility visible alongside price.

A cheaper fare is not necessarily the better choice if it provides significantly less flexibility.

---

# 16. Post-Selection Experience

After users select a flight, Skyscanner presents available airline and travel-provider booking options.

The platform explains that booking confirmation and subsequent information are generally provided by the selected airline or travel partner, although some bookings may be completed directly through Skyscanner. 15

### UX Implication

Post-selection responsibility can be distributed across different organisations.

This may affect:

- Confirmation
- Customer support
- Booking management
- Changes
- Refunds
- Notifications

### SkyPath Opportunity

A unified experience can reduce uncertainty by keeping important booking information accessible in one place.

---

# 17. Travel Inspiration

Skyscanner's Everywhere feature demonstrates a broader concept of travel inspiration.

The user does not necessarily begin with:

> "I need to fly to a specific destination."

They may instead begin with:

> "I want to travel somewhere affordable."

### UX Learning

Designing for intent rather than fixed inputs can support more natural travel planning.

However, inspiration features should remain separate from the primary booking workflow when they are not relevant to the user's immediate goal.

---

# 18. Strengths

## 18.1 Strong Price Discovery

Skyscanner is highly focused on finding competitive fares.

## 18.2 Flexible Search

Whole Month, Cheapest Month and Everywhere support flexible planning.

## 18.3 Broad Comparison

Users can compare options across airlines and travel providers.

## 18.4 Price Alerts

Users can continue monitoring a route after the initial search.

## 18.5 Nearby Airports

Alternative airports can expand the available search space.

## 18.6 Saved Options

Users can preserve flights they are considering instead of immediately booking.

## 18.7 Travel Inspiration

Everywhere supports open-ended travel discovery.

---

# 19. Potential UX Friction Areas

These are design hypotheses derived from the documented feature set and should be validated through usability research.

### Information Density

Flexible search, filtering, price information and provider options can create a large amount of information.

### Price Interpretation

Indicative flexible-date prices may differ from the later live price.

### Provider Handoff

Moving from Skyscanner to an airline or travel agency may create a discontinuity.

### Choice Overload

Large numbers of destinations and flight options can increase decision effort.

### Persistent Search Context

Saved searches and alerts may not always preserve every original filtering condition.

### Alternative-Airport Complexity

A cheaper airport may introduce additional travel time or logistical effort.

---

# 20. Competitive Lessons for SkyPath

## Lesson 01 — Flexibility Can Be a Core UX Capability

Users do not always know their exact destination or travel date.

Supporting controlled flexibility can help users discover better options.

---

## Lesson 02 — Price Discovery Is More Than Showing a Number

Users need context around why an option is cheaper and what trade-offs accompany that price.

---

## Lesson 03 — Saved Decisions Matter

Users often need time to compare before committing.

The product should support consideration rather than assuming immediate purchase.

---

## Lesson 04 — Price Alerts Can Extend the Decision Journey

Monitoring can reduce repeated manual searching.

---

## Lesson 05 — Alternative Options Need Context

Nearby airports and flexible dates are useful only when their practical consequences are understandable.

---

## Lesson 06 — Provider Handoffs Create Continuity Challenges

A search platform can be excellent at discovery while still leaving the user to navigate another system for the actual transaction.

---

# 21. SkyPath Differentiation Opportunity

Skyscanner is particularly strong in **price discovery and travel comparison**.

SkyPath should not attempt to compete simply by adding more destinations or providers.

Instead, the opportunity is to combine strong comparison with a more continuous booking experience.

The proposed SkyPath differentiation is:

> **Help users move from discovering an attractive option to confidently understanding, configuring and completing the booking.**

---

# 22. Competitive Positioning

### Skyscanner

**Explore → Compare → Save/Track → Provider Handoff**

### SkyPath

**Search → Compare → Understand → Configure → Review → Pay → Confirm → Manage**

The distinction is therefore primarily about **journey continuity and decision confidence**.

---

# 23. Key Competitive Takeaway

Skyscanner demonstrates how flexibility can become a central part of flight discovery.

Features such as Whole Month, Everywhere, Price Alerts, Saved flights and nearby-airport exploration allow users to search beyond a single fixed itinerary. 16

The opportunity for SkyPath is to retain the benefits of flexible comparison while reducing the cognitive complexity associated with evaluating multiple alternatives.

The central design question is:

> **How might SkyPath provide flexible choices without making the booking decision feel overwhelming?**

---

# 24. Evidence Note

This analysis is based primarily on publicly available Skyscanner product and help documentation.

Documented capabilities have been separated from UX interpretations and proposed SkyPath opportunities.

Potential friction areas are design hypotheses and should be validated through usability testing rather than presented as measured usability findings.
