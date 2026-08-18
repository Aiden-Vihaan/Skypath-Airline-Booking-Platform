# SkyPath Airline Booking Platform
## User Flow Documentation

**Project:** SkyPath Airline Booking Platform  
**Document:** User Flow Documentation  
**Version:** 1.0  
**UX Phase:** Wireframes & Interaction Design

---

## 1. Overview

This document defines the primary user flows for the SkyPath Airline Booking Platform.

The flows translate the research findings, personas, information architecture, and user requirements into clear interaction paths. The goal is to reduce booking friction, improve transparency, and help travellers complete important tasks with confidence.

---

# 2. Flight Booking Flow

### Objective
Enable travellers to search, compare, select, and book flights with minimal confusion.

### Flow

Start  
→ Enter origin and destination  
→ Select travel dates  
→ Select passengers  
→ Search flights  
→ View search results  
→ Apply filters  
→ Compare flights  
→ Select flight  
→ Select fare  
→ Enter passenger details  
→ Select seats  
→ Add baggage and add-ons  
→ Review booking  
→ Payment  
→ Booking confirmation

### Key UX Considerations

- Clearly display total price.
- Make fare differences easy to understand.
- Allow users to compare important flight attributes.
- Avoid unnecessary form fields.
- Provide progress indicators.
- Show selected options throughout the process.
- Prevent unexpected charges.

---

# 3. Flight Search Flow

### Objective
Help users quickly find relevant flights.

### Flow

Start  
→ Enter departure airport  
→ Enter destination airport  
→ Select departure date  
→ Select return date  
→ Select passenger count  
→ Select cabin class  
→ Search

### Error States

- Invalid airport
- Same origin and destination
- Past travel date
- Missing required information
- No available flights

### UX Requirements

- Autocomplete airport names.
- Display airport code and city.
- Support flexible date selection.
- Clearly distinguish departure and return dates.
- Provide useful empty-state messaging.

---

# 4. Flight Comparison Flow

### Objective
Help users evaluate flights based on price, duration, stops, airline, and included benefits.

### Flow

Search Results  
→ Select multiple flights  
→ Compare flights  
→ Review price  
→ Review duration  
→ Review stops  
→ Review baggage allowance  
→ Review fare benefits  
→ Select preferred flight

### Key UX Considerations

- Use consistent comparison attributes.
- Highlight meaningful differences.
- Keep price and included services visible.
- Avoid overwhelming users with unnecessary information.

---

# 5. Fare Selection Flow

### Objective
Help travellers select the fare that best matches their needs.

### Flow

Selected Flight  
→ View available fares  
→ Compare fare benefits  
→ Review baggage allowance  
→ Review cancellation/change conditions  
→ Review seat benefits  
→ Select fare  
→ Continue

### UX Requirements

Each fare should clearly communicate:

- Total price
- Baggage allowance
- Seat selection
- Change policy
- Cancellation/refund policy
- Included services

---

# 6. Passenger Details Flow

### Objective
Allow travellers to provide accurate passenger information efficiently.

### Flow

Selected Fare  
→ Passenger information  
→ Enter name  
→ Enter date of birth  
→ Enter gender/title where required  
→ Enter passport/ID information  
→ Enter contact information  
→ Validate information  
→ Continue

### UX Considerations

- Clearly identify mandatory fields.
- Use appropriate input formats.
- Provide inline validation.
- Allow information review before proceeding.
- Avoid unnecessary data collection.

---

# 7. Seat Selection Flow

### Objective
Allow travellers to select preferred seats with clear availability and pricing.

### Flow

Passenger Details  
→ Seat Selection  
→ View seat map  
→ Select passenger  
→ Select available seat  
→ View seat type and price  
→ Confirm seat  
→ Continue

### Decision Points

**Is the seat available?**

- Yes → Select seat
- No → Display unavailable → Select another seat

**Is the seat an additional-cost seat?**

- Yes → Display additional price
- No → Continue

### UX Requirements

- Clearly distinguish available and unavailable seats.
- Display seat price before confirmation.
- Provide seat characteristics where relevant.
- Allow users to change their selection.

---

# 8. Baggage & Add-ons Flow

### Objective
Make baggage allowances and additional baggage costs transparent.

### Flow

Seat Selection  
→ Baggage & Add-ons  
→ View included baggage  
→ Review baggage allowance  
→ Add extra baggage if required  
→ Select baggage quantity/weight  
→ View updated price  
→ Review selection  
→ Continue

### Decision Points

**Is baggage already included?**

- Yes → Display included allowance
- No → Display available baggage options

**Does the user want additional baggage?**

- Yes → Select additional baggage
- No → Continue

### UX Requirements

- Show included baggage prominently.
- Display weight limits.
- Show additional baggage prices clearly.
- Update the total price immediately.

---

# 9. Review & Payment Flow

### Objective
Allow users to verify their complete booking before making payment.

### Flow

Add-ons  
→ Booking Review  
→ Review flight details  
→ Review passenger details  
→ Review seats  
→ Review baggage  
→ Review add-ons  
→ Review total price  
→ Select payment method  
→ Enter payment information  
→ Confirm payment

### UX Requirements

The review screen should provide:

- Flight details
- Passenger names
- Seat selections
- Baggage
- Add-ons
- Taxes and fees
- Final total

Users should be able to edit individual sections before payment.

---

# 10. Booking Confirmation Flow

### Objective
Provide immediate confirmation and useful next steps after successful payment.

### Flow

Payment Successful  
→ Booking Confirmation  
→ Display booking reference  
→ Display itinerary  
→ Display passenger information  
→ Display payment summary  
→ Download/email confirmation  
→ Manage booking

### Key Actions

- View booking
- Download ticket
- Email confirmation
- Add trip to calendar
- Manage booking
- Check in later

---

# 11. Manage Booking Flow

### Objective
Allow users to manage an existing reservation.

### Flow

Manage Booking  
→ Enter booking reference  
→ Enter passenger information  
→ Retrieve booking  
→ View trip details  
→ Select required action

### Available Actions

- Change flight
- Change passenger information where permitted
- Change seat
- Add baggage
- Add services
- Request refund
- View payment information
- Check-in

---

# 12. Check-in Flow

### Objective
Provide a simple digital check-in experience.

### Flow

Manage Booking  
→ Check-in  
→ Confirm passenger  
→ Review travel information  
→ Confirm seat  
→ Complete check-in  
→ Generate boarding pass

### Key UX Considerations

- Clearly show check-in status.
- Display boarding pass immediately after completion.
- Provide instructions for airport arrival.
- Support multiple passengers in one booking.

---

# 13. Seat Upgrade Flow

### Objective
Allow users to upgrade their seat after booking.

### Flow

Manage Booking  
→ Seat Upgrade  
→ View current seat  
→ View available upgrade seats  
→ Compare seat types  
→ Select upgrade seat  
→ View additional cost  
→ Review upgrade  
→ Confirm upgrade  
→ Payment  
→ Upgrade confirmation

### Decision Points

**Is the selected seat available?**

- Yes → Continue
- No → Select another seat

**Is an additional payment required?**

- Yes → Payment
- No → Confirm upgrade

**Is payment successful?**

- Yes → Upgrade confirmed
- No → Retry payment / Choose another payment method

---

# 14. Refund Flow

### Objective
Make refund eligibility and the refund process transparent.

### Flow

Manage Booking  
→ Request Refund  
→ Review booking  
→ Check refund eligibility  
→ Display refund conditions  
→ Display estimated refund amount  
→ Confirm refund request  
→ Submit request  
→ Refund confirmation

### Decision Points

**Is the booking eligible for a refund?**

- Yes → Continue
- No → Explain applicable policy and alternatives

### UX Requirements

- Explain cancellation conditions clearly.
- Display estimated refund amount.
- Clearly communicate non-refundable charges.
- Provide refund status after submission.

---

# 15. Loyalty Flow

### Objective
Help users understand and manage loyalty benefits.

### Flow

Loyalty  
→ Sign in / Create account  
→ View membership status  
→ View points balance  
→ View points history  
→ View available rewards  
→ Select reward  
→ Redeem points  
→ Confirmation

### Key Information

- Current points
- Membership tier
- Points earned
- Points used
- Expiring points
- Available rewards
- Tier benefits

---

# 16. Family Traveller Flow

### Objective
Support families travelling with children by simplifying passenger management, food preferences, baggage, and travel requirements.

### Flow

Flight Search  
→ Select passengers  
→ Add adults and children  
→ Search flights  
→ Select flight  
→ Enter passenger details  
→ Add child information  
→ Select seats together  
→ Review child/family requirements  
→ Select baggage  
→ Select meal preferences  
→ Review accommodation or assistance needs where applicable  
→ Review booking  
→ Payment  
→ Confirmation

### Key UX Considerations

- Clearly identify child passengers.
- Help families select seats together.
- Display child-specific requirements.
- Provide suitable meal options.
- Make baggage allowances clear.
- Support family-friendly travel information.
- Minimise repetitive passenger information entry.

---

# 17. Senior Traveller Flow

### Objective
Provide a simpler and more accessible booking experience for older travellers.

### Flow

Search Flight  
→ Select flight  
→ Select fare  
→ Passenger details  
→ Request assistance  
→ Select seat  
→ Add baggage  
→ Review booking  
→ Payment  
→ Confirmation

### UX Considerations

- Large readable text.
- Clear labels.
- Simple navigation.
- Minimal cognitive load.
- Easy access to assistance options.
- Clear payment and cancellation information.

---

# 18. Accessibility Flow

### Objective
Ensure travellers with accessibility needs can identify and request appropriate assistance.

### Flow

Search Flight  
→ Select flight  
→ Passenger details  
→ Accessibility & Assistance  
→ Select required assistance  
→ Review accessibility requirements  
→ Select suitable seat  
→ Add baggage/services  
→ Review booking  
→ Payment  
→ Confirmation

### Possible Assistance Options

- Wheelchair assistance
- Airport assistance
- Boarding assistance
- Mobility support
- Special seating requirements
- Hearing/communication assistance
- Visual assistance

### UX Requirements

- Use accessible language.
- Do not hide assistance options.
- Provide clear confirmation of requested assistance.
- Allow users to modify assistance requirements before booking.

---

# 19. Error & Recovery Patterns

SkyPath should provide clear recovery paths instead of leaving users at dead ends.

### Common Errors

**No flights available**

Search again  
→ Modify date  
→ Modify airport  
→ Remove filters

**Payment failed**

Retry payment  
→ Choose another payment method  
→ Return to payment

**Seat unavailable**

Display unavailable state  
→ Select another seat

**Session expired**

Notify user  
→ Sign in again  
→ Restore booking information where possible

**Invalid passenger information**

Highlight incorrect field  
→ Explain required format  
→ Correct information  
→ Continue

---

# 20. Global UX Principles

All SkyPath user flows should follow these principles:

1. **Transparency** — Prices, restrictions, baggage and fare conditions should be visible before commitment.

2. **Progressive disclosure** — Show important information first and detailed information when needed.

3. **Consistency** — Use consistent terminology, navigation and interaction patterns.

4. **Error prevention** — Prevent mistakes through validation and clear instructions.

5. **User control** — Users should be able to review and modify selections before payment.

6. **Accessibility** — Design flows that can be understood and completed by users with different abilities.

7. **Feedback** — Every important action should provide clear system feedback.

8. **Recovery** — Errors should provide a clear path forward.

9. **Price clarity** — Additional costs should never appear unexpectedly.

10. **Reduced cognitive load** — Avoid unnecessary choices, repetitive forms and confusing terminology.

---

# 21. Primary Success Metrics

The user flows should ultimately improve:

- Flight search completion rate
- Flight selection confidence
- Booking completion rate
- Form completion rate
- Seat-selection success rate
- Baggage/add-on understanding
- Payment success rate
- Booking abandonment rate
- Refund request completion
- Check-in completion
- User satisfaction

---

# 22. Design Goal

The overall goal of the SkyPath user-flow system is to create a predictable, transparent and low-friction airline booking experience.

Users should always understand:

**Where they are → What they are doing → What it will cost → What happens next.**
