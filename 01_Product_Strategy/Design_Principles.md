# SkyPath — Design Principles

## 1. Purpose

The SkyPath design principles establish a set of consistent decision-making criteria for the product experience.

They are intended to guide interaction, information architecture, visual hierarchy and interface behaviour throughout the booking journey.

The principles are not visual styling rules. They describe how the product should behave and what the experience should prioritise when design trade-offs arise.

---

# 2. Principle 01 — Clarity Over Clutter

SkyPath should communicate complex travel information without overwhelming the user.

The interface should prioritise information according to its relevance to the current decision.

### Design Application

- Establish clear information hierarchy.
- Group related information.
- Prioritise essential information.
- Avoid unnecessary visual competition.
- Use progressive disclosure where appropriate.
- Keep primary actions visually identifiable.

### Guiding Question

> Can the user understand the most important information without having to search through the interface?

---

# 3. Principle 02 — Transparency Before Commitment

Users should understand important consequences before committing to a decision.

This is particularly important for pricing, fare conditions, baggage, seats and optional services.

### Design Application

- Display relevant costs at decision points.
- Distinguish included services from paid additions.
- Communicate fare conditions clearly.
- Maintain visibility of important selections.
- Provide a consolidated review before payment.

### Guiding Question

> Does the interface provide enough information for the user to make an informed decision?

---

# 4. Principle 03 — Support Comparison, Not Just Selection

The purpose of search results is not simply to display available flights.

The experience should help users understand how available options differ.

### Design Application

Important comparison dimensions may include:

- Price
- Departure time
- Arrival time
- Duration
- Stops
- Baggage
- Fare conditions

The visual hierarchy should make meaningful differences easy to identify.

### Guiding Question

> Can the user explain why one option is better suited to their needs than another?

---

# 5. Principle 04 — Recognition Over Recall

Users should not be required to remember important information from previous stages of the booking journey.

Relevant information should remain available when decisions are being made.

### Design Application

- Repeat important contextual information where necessary.
- Show selected options clearly.
- Maintain relevant flight details during later stages.
- Provide review opportunities.
- Use familiar visual patterns.

### Guiding Question

> Does the interface help the user recognise important information rather than forcing them to remember it?

---

# 6. Principle 05 — Progressive Disclosure

Complex information should be revealed according to the user's needs.

The interface should provide sufficient information for the current decision without presenting every possible detail simultaneously.

### Design Application

- Present essential information first.
- Allow deeper information to remain accessible.
- Separate primary decisions from secondary details.
- Avoid unnecessary interruptions.
- Introduce complexity progressively.

### Guiding Question

> Is the amount of information presented appropriate for the decision the user is currently making?

---

# 7. Principle 06 — User Control at Every Decision

Users should feel that they are making decisions rather than being pushed through a predetermined transaction.

### Design Application

- Allow selections to be reviewed.
- Allow appropriate selections to be changed.
- Make optional services clearly optional.
- Avoid ambiguous actions.
- Provide clear navigation between important stages.

### Guiding Question

> Does the user remain in control of the booking throughout the journey?

---

# 8. Principle 07 — Make System Status Visible

The system should communicate what is happening, what has happened and what will happen next.

This is especially important during multi-stage booking and payment.

### Design Application

- Show booking progress.
- Clearly indicate selected states.
- Provide feedback after important actions.
- Communicate validation states.
- Provide clear payment status.
- Make confirmation unmistakable.

### Guiding Question

> Does the user know where they are and what the system is doing?

---

# 9. Principle 08 — Prevent Errors Before They Happen

A strong experience should reduce the likelihood of errors rather than relying entirely on error messages after something goes wrong.

### Design Application

- Use appropriate field validation.
- Communicate requirements clearly.
- Distinguish invalid information from incomplete information.
- Provide review before irreversible actions.
- Avoid ambiguous controls.
- Preserve user-entered information where appropriate.

### Guiding Question

> Could the interface have helped the user avoid this error in the first place?

---

# 10. Principle 09 — Feedback Should Be Meaningful

Feedback should provide information that helps the user understand the result of an action.

A change in colour or animation alone is not sufficient when an action has important consequences.

### Design Application

Feedback should communicate:

- What happened.
- Whether the action succeeded.
- Whether further action is required.
- What the user can do next.

### Guiding Question

> Does the feedback help the user understand what happened and what to do next?

---

# 11. Principle 10 — Essential and Optional Decisions Must Be Distinguishable

Airline booking contains both mandatory and optional decisions.

The interface should not make these categories visually or conceptually indistinguishable.

### Design Application

Essential decisions may include:

- Flight selection
- Fare selection
- Passenger information
- Required payment information

Optional decisions may include:

- Seat upgrades
- Additional baggage
- Meals
- Other travel services

### Guiding Question

> Can the user immediately understand what is required and what is optional?

---

# 12. Principle 11 — Consistency Creates Confidence

Consistent interaction patterns reduce the amount of learning required throughout the journey.

### Design Application

Maintain consistency in:

- Terminology
- Buttons
- Forms
- Cards
- Selection states
- Navigation
- Feedback
- Spacing
- Typography
- Component behaviour

Consistency should apply to both visual appearance and interaction behaviour.

### Guiding Question

> Will a user who understands one part of the interface know how another part is likely to behave?

---

# 13. Principle 12 — Accessibility Is Part of the Design

Accessibility should be considered during design rather than treated as a final compliance step.

### Design Application

- Maintain appropriate contrast.
- Avoid relying on colour alone.
- Use readable typography.
- Provide clear labels.
- Make interactive states distinguishable.
- Consider keyboard and alternative interaction needs.
- Provide understandable error feedback.
- Maintain logical information hierarchy.

### Guiding Question

> Can people with different abilities understand and interact with the experience?

---

# 14. Principle 13 — Design for the Complete Journey

The booking experience should not be optimised around a single screen.

Each interaction contributes to the user's overall journey.

### Design Application

Consider continuity across:

**Search → Compare → Select → Configure → Review → Pay → Confirm → Manage**

Important information and interaction patterns should remain coherent as users move between these stages.

### Guiding Question

> Does this design decision improve the overall journey, or only the individual screen?

---

# 15. Principle 14 — Reduce Friction Without Removing Control

Simplicity should not be achieved by hiding important choices or removing user control.

The goal is to reduce unnecessary effort while preserving meaningful decisions.

### Design Application

- Remove redundant interactions.
- Simplify repetitive tasks.
- Maintain access to important information.
- Avoid unnecessary steps.
- Preserve meaningful user choices.

### Guiding Question

> Are we removing unnecessary effort or simply removing information and control?

---

# 16. Principle 15 — Design for Confidence, Not Just Completion

A booking can technically be completed while still leaving the user uncertain.

SkyPath therefore treats confidence as an important experience outcome.

### Design Application

Users should be able to understand:

- What they selected.
- What they paid.
- What is included.
- What happens next.
- Where their booking information is located.

### Guiding Question

> After completing the booking, would the user feel confident explaining what they purchased?

---

# 17. Principle 16 — Evidence Before Assumption

Design decisions should be connected to research, observed patterns, usability findings or clearly stated hypotheses wherever possible.

When evidence is unavailable, the design assumption should be acknowledged rather than presented as a validated fact.

### Design Application

- Connect design decisions to identified user needs.
- Document important assumptions.
- Distinguish research findings from hypotheses.
- Validate important assumptions when possible.
- Avoid unsupported claims.

### Guiding Question

> What evidence or reasoning supports this design decision?

---

# 18. Design Trade-Off Framework

Not every principle can always be maximised simultaneously.

For example, adding more information can improve transparency while increasing cognitive load.

When principles conflict, SkyPath prioritises decisions according to the following order:

1. **User safety and error prevention**
2. **Clarity and comprehension**
3. **Transparency**
4. **User control**
5. **Task efficiency**
6. **Visual simplicity**
7. **Commercial opportunity**

This hierarchy helps prevent visual or commercial considerations from overriding fundamental usability requirements.

---

# 19. Principle-to-Experience Mapping

| Principle | Primary Experience Area |
|---|---|
| Clarity Over Clutter | Information architecture |
| Transparency Before Commitment | Pricing and review |
| Support Comparison | Search results |
| Recognition Over Recall | Booking journey |
| Progressive Disclosure | Complex information |
| User Control | Selection and review |
| Visible System Status | Navigation and payment |
| Error Prevention | Forms and checkout |
| Meaningful Feedback | Interaction states |
| Essential vs Optional | Add-ons |
| Consistency | Design system |
| Accessibility | Entire interface |
| Complete Journey | End-to-end experience |
| Reduce Friction | Interaction design |
| Design for Confidence | Booking completion |
| Evidence Before Assumption | Design process |

---

# 20. Design Principle Summary

The SkyPath design philosophy can be summarised through six core ideas:

**Understand**  
Make complex information easier to interpret.

**Compare**  
Help users evaluate meaningful differences.

**Control**  
Keep users informed and in control of their choices.

**Prevent**  
Reduce errors and uncertainty before they occur.

**Complete**  
Create a predictable path towards successful booking.

**Continue**  
Maintain a coherent experience after the transaction.

Together, these principles provide the foundation for SkyPath's interaction and interface decisions.

They ensure that visual design is not treated as an isolated layer, but as part of a broader human-computer interaction strategy.
