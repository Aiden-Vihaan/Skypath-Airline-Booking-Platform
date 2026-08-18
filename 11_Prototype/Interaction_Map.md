# SkyPath — Interaction Map

## 1. Overview

The Interaction Map defines how users interact with the SkyPath airline booking experience and how the interface responds to those interactions.

It documents the relationship between:

- User actions
- Interface responses
- System feedback
- Navigation
- Component states
- Validation
- Errors
- Confirmation
- Recovery

The interaction model is designed to make the booking experience predictable, transparent, and easy to recover from.

---

## 2. Interaction Design Principles

SkyPath follows these core interaction principles:

### 2.1 Visibility of System Status

The interface communicates what is happening after important user actions.

Examples:

- Loading indicators during flight search.
- Updated prices after selecting add-ons.
- Confirmation messages after successful actions.
- Clear payment processing states.

### 2.2 Immediate Feedback

User actions should produce visible feedback.

Examples:

- Selected flight receives a selected state.
- Selected seat is visually distinguished.
- Buttons respond to interaction.
- Form fields display validation feedback.
- Added baggage appears in the booking summary.

### 2.3 User Control

Users should be able to review and modify decisions before final confirmation.

Examples:

- Change flight.
- Change fare.
- Change seat.
- Remove baggage.
- Modify passenger information.
- Return to previous booking stages.

### 2.4 Error Prevention

The interface should prevent avoidable errors before they occur.

Examples:

- Disable unavailable seats.
- Validate passenger information.
- Prevent incomplete forms from continuing.
- Display baggage limits before selection.
- Display final pricing before payment.

### 2.5 Recognition Over Recall

Users should not need to remember information from previous screens.

Important information remains visible through:

- Booking summaries.
- Selected flight details.
- Price breakdowns.
- Passenger information summaries.
- Baggage allowances.
- Seat selections.

---

## 3. Global Interaction Model

The primary booking interaction follows this structure:

```text
User Action
    ↓
Interface Response
    ↓
System Feedback
    ↓
Updated State
    ↓
Next Available Action
