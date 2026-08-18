# SkyPath — Problem Definition

## Problem Context

Airline booking is a high-information interaction.

Users are required to make several connected decisions involving:

- destination;
- date;
- flight schedule;
- fare type;
- baggage;
- seats;
- passenger information;
- meals and other add-ons;
- payment;
- cancellation or refund conditions.

These decisions are often presented as separate steps even though users perceive them as one continuous booking task.

A decision made early in the journey can affect cost, flexibility, baggage allowance, seating, and later choices.

This creates opportunities for confusion and unnecessary cognitive effort.

---

## Problem Statement

Users need a way to compare, understand, and complete airline bookings without having to repeatedly search for hidden conditions, additional costs, restrictions, or important travel information.

The design challenge is therefore:

> **How might an airline booking platform make complex travel decisions transparent, predictable, and manageable while supporting different traveller needs?**

---

## Key UX Problems

### 1. Information Overload

Flight search results can contain many variables simultaneously:

- departure time;
- arrival time;
- duration;
- number of stops;
- airline;
- fare;
- baggage allowance;
- seat availability;
- fare restrictions.

Presenting all information with equal visual emphasis can make comparison difficult.

### Design implication

Information should be prioritised according to the user's decision rather than simply displayed according to the airline's internal structure.

---

### 2. Difficult Flight Comparison

Users frequently compare flights based on more than ticket price.

A cheaper flight may have:

- longer travel time;
- additional stops;
- reduced baggage;
- restrictive cancellation conditions;
- additional seat or baggage charges.

### Design implication

Comparison should expose meaningful differences instead of requiring users to inspect each flight independently.

---

### 3. Unclear Additional Costs

Baggage, seat selection, meals, upgrades, and other services can alter the final price.

If these costs are introduced late in the process, users may feel that the original price was misleading.

### Design implication

SkyPath uses progressive cost disclosure and maintains a visible relationship between selections and the updated booking total.

---

### 4. Complex Baggage Decisions

Baggage requirements vary considerably between travellers.

For example:

- students may carry significantly more luggage;
- families may require additional checked baggage;
- business travellers may need predictable cabin baggage;
- senior travellers may require simpler explanations of baggage restrictions.

### Design implication

The baggage experience should clearly distinguish:

- included baggage;
- additional baggage;
- weight limits;
- number of pieces;
- price;
- passenger association.

---

### 5. Family Travel Complexity

Family travellers may need to coordinate:

- adults;
- children;
- seats;
- baggage;
- meals;
- travel documents;
- accommodation;
- special requirements.

### Design implication

Family-related requirements should be considered throughout the journey instead of being treated as a single passenger-information form.

---

### 6. Accessibility Barriers

Users with accessibility requirements may need information about:

- airport assistance;
- accessible seating;
- mobility support;
- boarding assistance;
- service requirements;
- accessible facilities.

When this information is difficult to discover, users may experience uncertainty before travelling.

### Design implication

Accessibility should be integrated into the booking architecture rather than treated as an isolated feature.

---

### 7. Payment Anxiety

Payment represents a high-risk moment.

Users need confidence that:

- the selected flight is correct;
- passenger information is accurate;
- the final price is understood;
- additional services are included;
- the transaction is secure.

### Design implication

A strong review stage should precede payment and provide a concise but comprehensive summary.

---

### 8. Post-Booking Uncertainty

The booking journey does not end after payment.

Users may later need to:

- check their itinerary;
- change a booking;
- add baggage;
- change seats;
- request a refund;
- upgrade a seat;
- check in.

### Design implication

Post-booking tasks should remain accessible through a clear booking-management structure.

---

## Design Goals

The problem analysis led to six primary design goals.

### Goal 01 — Clarity

Make important information understandable without requiring users to search across multiple screens.

### Goal 02 — Transparency

Communicate total costs, baggage allowances, restrictions, and optional services clearly.

### Goal 03 — Efficiency

Reduce unnecessary steps for users who already know what they want.

### Goal 04 — Flexibility

Support different traveller contexts and booking requirements.

### Goal 05 — Accessibility

Ensure critical functionality and information remain usable for people with different abilities and needs.

### Goal 06 — Confidence

Give users sufficient information to make decisions confidently before committing to payment.

---

## Design Success Criteria

The solution should allow users to:

1. find an appropriate flight;
2. compare alternatives efficiently;
3. understand the total cost;
4. select baggage and seats confidently;
5. enter passenger information without unnecessary friction;
6. review the complete booking before payment;
7. complete payment with confidence;
8. retrieve and manage the booking afterwards.

The design should also reduce avoidable uncertainty and prevent important information from appearing unexpectedly late in the journey.
