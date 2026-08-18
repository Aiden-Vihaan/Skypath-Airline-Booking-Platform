# SkyPath — Prototype Link & Scope

## 1. Overview

The SkyPath prototype represents the high-fidelity interaction model for the airline booking experience.

It connects the key user flows identified during research and information architecture into a coherent end-to-end booking journey.

The prototype focuses on reducing booking friction, improving information clarity, increasing confidence during payment, and giving travellers better control over optional services and post-booking actions.

---

## 2. Prototype Purpose

The prototype is designed to:

- Validate the core airline booking journey before development.
- Test whether users can find and compare flights efficiently.
- Reduce cognitive load during flight selection.
- Make fare and baggage information easier to understand.
- Support clear passenger and traveller information entry.
- Provide transparent seat, baggage, and add-on selection.
- Increase confidence before payment.
- Make confirmation and post-booking management easy to understand.
- Validate responsive behaviour across desktop and mobile experiences.

---

## 3. Prototype Platform

**Primary design tool:** Figma

**Prototype type:** High-fidelity interactive prototype

**Primary experience:** Responsive airline booking platform

**Primary interaction model:** Click/tap-based navigation with realistic states, validation, feedback, overlays, and confirmation flows.

---

## 4. Prototype Entry Point

**Figma Prototype:**  
> Add the final Figma prototype URL here.

`[INSERT FINAL FIGMA PROTOTYPE LINK]`

### Prototype access

The prototype should open at the primary booking entry point and allow reviewers to navigate through the main booking journey without requiring additional explanation.

---

## 5. Primary Prototype Flow

The main end-to-end flow is:

```text
Discover
   ↓
Search Flights
   ↓
Compare Flight Options
   ↓
Select Flight & Fare
   ↓
Passenger Details
   ↓
Seat & Add-ons
   ↓
Review & Payment
   ↓
Booking Confirmation
   ↓
Post-Booking Management


### 6. Key Prototype Scenarios

Scenario 01 — Flight Booking

Goal: Complete a flight booking from search to confirmation.

Flow:
1.Enter origin and destination.
2.Select travel dates.
3.Select passenger count.
4.Search available flights.
5.Compare flight options.
6.Select a flight.
7.Choose fare type.
8.Enter passenger information.
9.Select seats.
10.Add or review baggage.
11.Review optional services.
12.Review complete booking summary.
13.Proceed to payment.
14.Complete payment.
15.View booking confirmation.

Success condition:
The user can complete the booking journey while understanding the selected flight, fare, passenger information, additional services, and final price.

Scenario 02 — Baggage Selection
Goal: Review included baggage and add additional baggage when required.
Flow:
Booking
   ↓
Baggage & Add-ons
   ↓
Check Included Baggage
   ↓
View Baggage Options
   ↓
Add Additional Baggage
   ↓
Review Baggage Details
   ↓
Price Update
   ↓
Confirm Selection

Success condition:
The user understands what baggage is included, what additional baggage costs, and how the selection affects the final booking price.

Scenario 03 — Seat Selection / Upgrade
Goal: Select a preferred seat or upgrade the seat when available.
Flow:
Seat & Add-ons
   ↓
View Seat Map
   ↓
Review Seat Availability
   ↓
Select Seat
   ↓
Review Additional Cost
   ↓
Confirm Selection
Success condition:
The user can identify available seats, understand seat-related costs, and confirm their selection without confusion.

Scenario 04 — Loyalty
Goal: Allow returning users to access loyalty-related benefits.
Flow:
Account / Loyalty
   ↓
View Loyalty Status
   ↓
Review Points / Benefits
   ↓
Apply Eligible Benefit
   ↓
Continue Booking
Success condition:
The user understands their loyalty status and any benefits available during the booking process.

Scenario 05 — Refund / Cancellation
Goal: Help a traveller understand and initiate a refund or cancellation.
Flow:
Manage Booking
   ↓
Select Booking
   ↓
Cancellation / Refund
   ↓
Review Eligibility
   ↓
Review Refund Amount
   ↓
Confirm Request
   ↓
Request Confirmation
Success condition:
The user understands their eligibility, financial implications, and the status of the refund request before confirming.

7. Prototype States
The prototype includes representative states for important interaction conditions.

Default State
The standard interface before user interaction.

Selected State
Used when a user selects a flight, seat, fare, baggage option, or other choice.

Disabled State
Used when an action is unavailable.

Loading State
Used when the system is processing a request or retrieving information.

Error State
Used when an action cannot be completed or information is invalid.

Validation State
Used to identify missing or incorrectly entered information.

Success State
Used after a successful action or completed transaction.

Confirmation State
Used when the user needs to verify an important decision before proceeding.

8. Primary Interaction Areas
The prototype prioritizes interaction quality around:
Flight search
Flight comparison
Fare selection
Passenger information
Seat selection
Baggage selection
Add-on services
Booking review
Payment
Confirmation
Manage booking
Refund and cancellation
Loyalty benefits

9. Information Hierarchy
The prototype follows a progressive-disclosure approach.
Users are first presented with the information required to make the current decision.
Additional details are available when needed without overwhelming the primary task.
Priority hierarchy

Primary information
Flight
Date
Time
Route
Fare
Total price
Availability

Secondary information
Baggage allowance
Seat conditions
Fare benefits
Add-on prices
Cancellation conditions

Supporting information
Detailed policies
Terms and conditions
Additional service information
Help and contextual guidance

10. Interaction Principles
The prototype follows these interaction principles:

10.1 Clear next action
Each screen should communicate the primary action clearly.

10.2 Progressive disclosure
Complex information is revealed progressively rather than presented simultaneously.

10.3 Transparent pricing
Additional costs should be visible before confirmation.

10.4 Reversible decisions
Where possible, users should be able to modify selections before payment.

10.5 Immediate feedback
The interface should acknowledge important user actions immediately.

10.6 Error prevention
The experience should prevent avoidable errors through validation, clear constraints, and meaningful defaults.

10.7 Consistency
Interaction patterns, labels, buttons, navigation, and feedback should remain consistent throughout the experience.

11. Responsive Prototype
The SkyPath experience is designed for responsive use across:

Mobile
The core information architecture remains consistent while layout, navigation, spacing, and interaction patterns adapt to the available screen size.
Desktop
Prioritizes comparison, visibility, and multi-column information.
Tablet
Balances information density with touch-friendly interaction.
Mobile
Prioritizes focused tasks, vertical progression, simplified navigation, and accessible touch targets.

12. Accessibility Considerations
The prototype considers accessibility throughout the interaction model.
Key considerations include:
Clear visual hierarchy.
Sufficient contrast.
Meaningful labels.
Large enough interactive targets.
Keyboard-accessible interaction patterns where applicable.
Clear error messages.
Avoiding colour as the only indicator of status.
Consistent navigation.
Readable typography.
Simple and predictable interaction patterns.

13. Prototype Validation Goals
The prototype is intended to validate the following questions:
Can users find and search for flights without assistance?
Can users compare flight options effectively?
Do users understand fare differences?
Can users identify included baggage?
Can users add additional baggage confidently?
Can users select seats without confusion?
Can users understand additional costs?
Can users review the complete booking before payment?
Do users feel confident during the payment process?
Can users understand the confirmation and post-booking experience?
Can users recover easily from errors?
Can users complete the main tasks comfortably on mobile?

14. Prototype Success Criteria
The prototype will be considered successful when users can:
Complete the primary booking task without assistance.
Understand important decisions before confirming them.
Identify the final price before payment.
Modify optional selections without losing progress.
Recover from common errors.
Understand confirmation and post-booking information.
Navigate the experience consistently across responsive layouts.

15. Related Documentation
The prototype is supported by the following project documentation:
06_User_Flows/User_Flow_Documentation.md
07_Wireframes/User_Flow_Documentation.md
08_Design_System/Accessibility.md
08_Design_System/Colors.md
08_Design_System/Design_Tokens.json
08_Design_System/Elevation.md
08_Design_System/Icons.md
08_Design_System/Motion.md
08_Design_System/Spacing.md
08_Design_System/Typography.md
11_Prototype/Interaction_Map.md
11_Prototype/Transition_Specifications.md
11_Prototype/Prototype_Testing.md

16. Prototype Version
Version: 1.0
Status: High-Fidelity Prototype
Design System: SkyPath Design System
Primary Flow: Flight Booking
Secondary Flows: Baggage, Seat Selection, Loyalty, Refund / Cancellation, Post-Booking Management
