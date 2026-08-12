# SkyPath — Problem Statement

## 1. Overview

Airline booking is a high-information, high-consequence digital experience. Users are required to compare flights, interpret prices and fare conditions, provide passenger information, select seats, evaluate optional services and complete payment within a single journey.

Although airline booking platforms provide access to a large amount of information, the challenge is not simply providing more information. The challenge is presenting the right information at the right moment in a way that supports confident decision-making.

SkyPath explores this problem from a human-computer interaction perspective.

---

## 2. Core Problem

Users can experience unnecessary cognitive and interactional complexity while booking flights because important information is distributed across multiple stages of the journey.

Flight price, duration, stops, baggage allowance, fare conditions, optional services and post-booking information may require users to repeatedly interpret and compare information before making a decision.

This creates an opportunity to design a booking experience that makes complex travel decisions easier to understand without removing the depth of information users need.

---

## 3. User Problem

The central user problem can be expressed as:

> **How might we help travellers understand, compare and complete an airline booking with greater clarity and confidence while reducing unnecessary cognitive and interactional effort?**

The problem extends beyond the flight-search screen.

Users need support throughout the complete journey:

**Search → Compare → Select → Configure → Review → Pay → Confirm → Manage**

A successful experience therefore needs to maintain clarity across the entire journey rather than optimising only one individual screen.

---

## 4. Key Problem Areas

### 4.1 Information Overload

Flight-booking interfaces can contain large amounts of information simultaneously.

Users may need to process:

- Departure and arrival times
- Flight duration
- Number of stops
- Airport information
- Fare class
- Baggage allowance
- Seat conditions
- Refund and cancellation conditions
- Additional services
- Total price

The design challenge is to establish a clear hierarchy so that important information remains immediately understandable.

---

### 4.2 Difficult Flight Comparison

Travellers often need to evaluate multiple flight options against several criteria.

Price alone may not determine the best option.

A flight with a lower initial price may have:

- Longer travel time
- More stops
- Less baggage
- Additional fees
- Less flexibility

The interface therefore needs to support meaningful comparison rather than presenting options as isolated search results.

---

### 4.3 Pricing and Fare Transparency

The relationship between the advertised fare and the final payable amount can be difficult to understand when additional services and charges are introduced during the booking process.

Users need a clear understanding of:

- Base fare
- Taxes and fees
- Baggage costs
- Seat costs
- Optional services
- Final payable amount

The design opportunity is to make price changes understandable rather than forcing users to reconstruct the calculation themselves.

---

### 4.4 Repetitive Data Entry

Booking journeys can require users to provide information that may already be available through their profile or previous interactions.

Repeated entry increases interaction effort and introduces opportunities for errors.

SkyPath therefore explores how passenger information can be structured so that required information remains accessible while unnecessary repetition is reduced.

---

### 4.5 Decision Complexity

The booking journey contains multiple decisions that occur sequentially.

Users may need to choose:

1. A flight
2. A fare
3. A passenger configuration
4. A seat
5. Additional services
6. Payment information

Presenting every possible decision simultaneously can increase cognitive load.

The experience should therefore distinguish between essential decisions and optional decisions.

---

### 4.6 Uncertainty During Booking

Users may hesitate when they are unsure whether their selections have been saved, whether a payment was successful or what happens after confirmation.

Clear system feedback can reduce uncertainty by communicating:

- Current progress
- Completed steps
- Selected options
- Payment status
- Booking confirmation
- Post-booking actions

---

### 4.7 Post-Booking Continuity

The interaction does not end when payment succeeds.

Travellers may subsequently need to:

- View their itinerary
- Access boarding information
- Review booking details
- Manage their reservation
- Check flight status
- Modify eligible booking details

The experience therefore needs to provide continuity between booking and post-booking management.

---

## 5. HCI Framing

The problem can be understood through several human-computer interaction considerations.

### Cognitive Load

The interface should reduce unnecessary mental effort by organising complex information into understandable groups.

### Visibility of System Status

Users should be able to understand where they are in the booking process and what has already been completed.

### Recognition Over Recall

Important information should remain visible when users need to make decisions rather than requiring them to remember details from previous screens.

### Error Prevention

The interface should help users identify potentially problematic information before committing to irreversible actions.

### Consistency

Similar concepts and actions should behave consistently throughout the booking journey.

### User Control

Users should be able to review and understand their selections before completing payment.

---

## 6. Design Opportunity

The problem presents an opportunity to rethink the airline-booking experience as a continuous decision-support system rather than a sequence of disconnected forms.

The design opportunity is to create an experience in which:

- Flight options are easier to compare.
- Pricing remains transparent.
- Essential and optional decisions are clearly separated.
- Repetitive input is reduced.
- Progress remains visible.
- Important selections can be reviewed before payment.
- Confirmation provides clear next steps.
- Post-booking access remains connected to the original journey.

---

## 7. Problem Statement

> **SkyPath addresses the complexity of airline booking by exploring how information architecture, interaction design and visual hierarchy can work together to help travellers compare options, understand costs, make informed decisions and complete bookings with greater confidence and less unnecessary effort.**

---

## 8. Design Challenge

The broader design challenge is not to create another airline booking interface.

It is to investigate:

> **How can a complex transactional experience be designed so that users feel informed and in control without being overwhelmed by the amount of information and decisions involved?**

This question forms the foundation for the subsequent research, information architecture, user flows, wireframes and interface design explored throughout the project.
