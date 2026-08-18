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

## 4. Global Navigation Interactions

| Interaction | User Action | System Response | Result |
|---|---|---|---|
| Primary navigation | Select navigation item | Active destination opens | User moves to selected section |
| Back | Select Back | Previous state is restored | User returns without unnecessary data loss |
| Continue | Select Continue | Current information is validated | User progresses to next stage |
| Cancel | Select Cancel | Confirmation may appear when destructive | User exits or returns safely |
| Close | Select close icon | Overlay/modal closes | Previous context remains |
| Edit | Select Edit | Relevant section becomes editable | User can modify information |
| Save | Select Save | Data is validated and stored | Updated information is displayed |
| Help | Select Help | Contextual guidance opens | User receives assistance |

---

## 5. Flight Search Interactions

### 5.1 Origin and Destination

**User action:**  
User selects the origin or destination field.

**System response:**  
The field becomes active and presents search suggestions.

**Interaction behaviour:**

- Search suggestions appear while typing.
- Airport and city information should be distinguishable.
- Recently selected locations may be surfaced where appropriate.
- Invalid or unsupported locations should produce clear feedback.

**Result:**  
The selected location is displayed in the search form.

### 5.2 Date Selection

**User action:**  
User opens the date selector.

**System response:**  
A calendar interface appears.

**Interaction behaviour:**

- Selected departure date is highlighted.
- Return date becomes available after departure selection.
- Invalid date combinations are prevented.
- Current selection remains visible.
- Date changes update the search criteria.

**Result:**  
The selected travel dates are displayed in the search form.

### 5.3 Passenger Selection

**User action:**  
User opens passenger controls.

**System response:**  
Passenger quantity controls appear.

**Interaction behaviour:**

Users can increase or decrease:

- Adults
- Children
- Infants

The interface should respect minimum and maximum limits.

**Result:**  
Passenger count is reflected in the search criteria.

### 5.4 Search Flights

**User action:**  
User selects **Search Flights**.

**System response:**  
The system validates the search parameters and displays a loading state.

**Feedback:**

```text
Searching available flights...
