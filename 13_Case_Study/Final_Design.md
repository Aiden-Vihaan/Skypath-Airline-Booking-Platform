# SkyPath — Final Design

## Final Design Overview

The final SkyPath concept brings together the research, information architecture, interaction design, visual design, and usability considerations developed throughout the project.

The resulting system is designed around one continuous user journey:

**Discover → Search → Compare → Select → Prepare → Review → Pay → Manage**

---

## Flight Discovery

The discovery experience provides users with a starting point for exploring destinations and available travel options.

The design avoids forcing users into a highly technical search interface immediately.

Instead, it establishes the destination and travel context before moving into detailed flight search.

---

## Flight Search

The search experience prioritises the information required to define a trip:

- origin;
- destination;
- travel dates;
- passenger count;
- traveller type.

The interface is structured to minimise unnecessary input while maintaining sufficient control for more complex journeys.

---

## Flight Comparison

Flight comparison is one of the most important decision-making stages.

The final design surfaces:

- price;
- departure;
- arrival;
- duration;
- stops;
- baggage;
- fare conditions.

The intention is to allow users to evaluate value rather than simply selecting the cheapest numerical price.

---

## Fare Selection

Fare selection communicates the relationship between fare price and included benefits.

Users can understand what changes when selecting a different fare instead of discovering the difference later in the booking.

---

## Passenger Information

Passenger information is structured around the actual travellers included in the booking.

The design aims to reduce repetitive input and clearly associate information with the correct passenger.

This becomes particularly important for:

- families;
- groups;
- travellers requiring assistance.

---

## Seat Selection

Seat selection provides users with meaningful information before making a decision.

The system distinguishes between:

- available seats;
- selected seats;
- restricted seats;
- additional-cost seats.

The price impact is communicated as part of the booking total.

---

## Baggage

The baggage experience was designed as an explicit decision rather than an optional afterthought.

Users can understand:

- included baggage;
- checked baggage;
- cabin baggage;
- additional baggage;
- weight limits;
- passenger association;
- additional cost.

The baggage flow also supports changing selections before final confirmation.

---

## Add-ons

Optional services are grouped in a controlled manner to avoid overwhelming the booking experience.

Examples include:

- meals;
- baggage;
- seat selection;
- upgrades.

The interface maintains transparency between optional selections and the final price.

---

## Review and Payment

Before payment, the user receives a consolidated booking summary.

The review stage includes:

- flight information;
- passenger information;
- seat selections;
- baggage;
- add-ons;
- total price.

This creates a deliberate checkpoint between configuration and payment.

---

## Confirmation

After payment, the confirmation experience provides the user with a clear representation of the completed booking.

The confirmation should answer:

- What was booked?
- Who is travelling?
- When is the flight?
- What baggage is included?
- What was paid?
- What can be managed next?

---

## Post-Booking Management

The design treats post-booking management as part of the primary experience.

Users can access tasks such as:

- view itinerary;
- check in;
- change seats;
- add baggage;
- upgrade;
- request refund;
- manage loyalty information.

This reduces the need for users to rediscover the appropriate feature after booking.

---

## Responsive Design

The design system considers multiple screen contexts:

- desktop;
- tablet;
- mobile.

The responsive strategy prioritises content and task hierarchy rather than simply scaling desktop layouts down.

On smaller screens, secondary information can be progressively disclosed while critical actions remain accessible.

---

## Accessibility

Accessibility considerations are integrated into the overall design.

Key considerations include:

- readable typography;
- sufficient interaction targets;
- clear hierarchy;
- understandable labels;
- meaningful status indicators;
- accessible navigation;
- assistance-related information;
- reduced reliance on colour alone.

Accessibility is treated as a system-level requirement rather than a separate visual mode.

---

## Design System

The final interface uses a reusable component approach.

Major component categories include:

- navigation;
- buttons;
- inputs;
- cards;
- flight-result components;
- fare components;
- passenger forms;
- baggage components;
- seat-selection elements;
- price summaries;
- alerts;
- confirmation states.

The objective is to maintain consistency while allowing components to adapt to different booking contexts.

---

## Final Design Principle

The final design is guided by a simple principle:

> **Every important decision should be understandable before the user commits to it.**

This principle is reflected in:

- flight comparison;
- fare selection;
- baggage;
- add-ons;
- payment review;
- confirmation;
- post-booking management.

---

## Final Outcome

SkyPath demonstrates how a complex service can be approached as an interconnected UX system.

The final design is therefore not defined by individual screens alone.

Its value comes from the relationship between:

**Information Architecture + Interaction Design + Content Hierarchy + Accessibility + Visual Design + Prototype Behaviour + Usability Evaluation**
