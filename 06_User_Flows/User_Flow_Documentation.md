# SkyPath — User Flow Documentation

## 1. Overview

SkyPath is an airline booking platform designed to make flight discovery, comparison, booking, and post-booking management simpler and more transparent.

This document defines the major user flows represented in Chapter 6 of the SkyPath UX project.

The flows focus on important user tasks that occur before, during, and after flight booking.

---

## 2. User Flow Objectives

The user flows were created to:

- Reduce unnecessary steps during booking.
- Make flight comparison easier.
- Provide clear fare and baggage information.
- Reduce confusion during seat and add-on selection.
- Make check-in straightforward.
- Give users greater control over refunds and booking changes.
- Support repeat travellers through loyalty features.
- Provide clear confirmation and recovery paths when problems occur.

---

## 3. Primary User Flow

### Flight Booking

The primary booking journey follows this sequence:

**Flight Search → Search Results → Filter & Sort → Compare Flights → Flight Details → Select Fare → Passenger Details → Seat Selection → Baggage & Add-ons → Booking Review → Payment → Booking Confirmation**

### Key Decision Points

Users may:

- Modify their search criteria.
- Apply or remove filters.
- Compare multiple flights.
- Return to flight results.
- Change the selected fare.
- Edit passenger information.
- Change their seat.
- Add or remove baggage and additional services.
- Modify booking details before payment.
- Retry payment after a failed transaction.

The flow is designed to allow users to move backward without losing previously entered information wherever possible.

---

## 4. Baggage Flow

The baggage flow helps users understand and manage baggage requirements before completing payment.

### Flow

**Booking → Baggage & Add-ons → Included Baggage → Additional Baggage Options → Select Baggage → Price Update → Review → Continue to Payment**

### Key Considerations

- Clearly display baggage included with the selected fare.
- Show additional baggage options and prices.
- Explain baggage limits in simple language.
- Display the updated total immediately after selection.
- Allow users to remove or change baggage.
- Prevent users from accidentally purchasing duplicate baggage.

### UX Goal

Make baggage costs and allowances transparent before payment so users are less likely to experience unexpected charges.

---

## 5. Check-in Flow

The check-in flow allows passengers to complete online check-in before their flight.

### Flow

**Check-in → Find Booking → Enter Booking Details → Passenger Verification → Select Passenger → Review Details → Check-in → Confirmation**

### Key Considerations

- Provide clear instructions for locating the booking.
- Minimize unnecessary information entry.
- Clearly identify passengers included in the booking.
- Highlight missing or invalid information.
- Provide a clear confirmation after successful check-in.

### UX Goal

Reduce anxiety and unnecessary effort during the pre-flight check-in process.

---

## 6. Seat Upgrade Flow

The seat-upgrade flow allows users to review available seats and upgrade their seating option.

### Flow

**Manage Trip → Seat Selection → Available Seats → Seat Details → Upgrade Option → Price Difference → Confirm Upgrade → Updated Booking**

### Key Considerations

- Clearly distinguish standard and upgraded seats.
- Display additional costs before confirmation.
- Provide useful seat information such as location and available features.
- Allow users to cancel the upgrade before confirmation.
- Update the booking immediately after successful payment.

### UX Goal

Help users make informed seat decisions without creating uncertainty about additional charges.

---

## 7. Refund Flow

The refund flow allows users to request a refund for an eligible booking.

### Flow

**Manage Trip → Refund Request → Select Booking → Refund Eligibility → Select Passenger/Segment → Refund Details → Confirm Request → Refund Confirmation**

### Key Considerations

- Clearly explain refund eligibility.
- Show applicable deductions or fees.
- Display the estimated refund amount.
- Explain the expected processing timeline.
- Provide confirmation after submission.
- Allow users to track the refund status.

### UX Goal

Make the refund process transparent and reduce uncertainty about eligibility, deductions, and processing time.

---

## 8. Loyalty Flow

The loyalty flow supports users who frequently travel with SkyPath.

### Flow

**Loyalty → Sign In / Join → Loyalty Dashboard → Points Balance → Earn Points → Redeem Points → Review Redemption → Confirmation**

### Key Considerations

- Display the current points balance clearly.
- Explain how points are earned.
- Show available redemption options.
- Provide clear information about points required for each option.
- Confirm successful redemption.
- Make loyalty information accessible from the main navigation.

### UX Goal

Encourage repeat usage by making loyalty benefits easy to understand and manage.

---

## 9. Error and Recovery Patterns

Important flows include recovery paths rather than forcing users to restart.

### Common Error Scenarios

**Payment Failure**

Payment → Failure → Error Explanation → Retry Payment / Change Payment Method → Confirmation

**Invalid Passenger Information**

Passenger Details → Validation Error → Correct Information → Continue

**Unavailable Seat**

Seat Selection → Seat Unavailable → Return to Seat Map → Select Alternative Seat

**Unavailable Flight**

Flight Details → Flight No Longer Available → Return to Search Results → Select Alternative

**Refund Not Eligible**

Refund Request → Eligibility Check → Not Eligible → Explanation → Contact Support / Return to Manage Trip

---

## 10. Navigation Principles

The user flows follow these navigation principles:

1. Users should always understand where they are in the booking process.
2. Primary actions should be visually prominent.
3. Users should be able to go back and modify information.
4. Important prices should be visible before confirmation.
5. Errors should provide a clear recovery action.
6. Destructive or irreversible actions should require confirmation.
7. Confirmation states should clearly communicate successful completion.

---

## 11. Flow Design Principles

### Visibility

Important information such as price, baggage allowance, flight details, and booking status should remain visible at relevant stages.

### Consistency

Similar actions should behave consistently across booking, check-in, refund, and post-booking experiences.

### User Control

Users should be able to review, modify, or cancel selections before committing to an action.

### Error Prevention

The interface should prevent common mistakes through validation, clear labels, and confirmation steps.

### Transparency

Additional costs, restrictions, eligibility conditions, and important booking information should be communicated before users make final decisions.

---

## 12. Relationship to Other UX Artifacts

The user flows build upon findings from earlier project stages:

- **User Research** identifies user needs and pain points.
- **Personas** represent major traveller types.
- **Journey Maps** describe the end-to-end traveller experience.
- **Information Architecture** defines how the product content and features are organised.
- **User Flows** translate these findings into task-specific interaction paths.
- **Wireframes and UI Designs** can then use these flows as structural guidance.

---

## 13. Chapter 6 Deliverables

The following user-flow assets are included in this chapter:

| Asset | Purpose |
|---|---|
| `Flight_Booking.fig` | Primary flight booking flow |
| `Baggage.fig` | Baggage selection and management flow |
| `Checkin.fig` | Online check-in flow |
| `Seat_Upgrade.fig` | Seat selection and upgrade flow |
| `Refund.fig` | Refund request flow |
| `Loyalty.fig` | Loyalty and rewards flow |
| `User_Flow_Documentation.md` | Documentation and rationale for all major flows |

---

## 14. Summary

The SkyPath user flows translate research and information-architecture findings into clear task pathways.

The primary focus is reducing friction during flight booking while maintaining transparency, user control, and clear recovery paths.

Together, the flows provide a structural foundation for the subsequent wireframing and interface-design stages of the project.
