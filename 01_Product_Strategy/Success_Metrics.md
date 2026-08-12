# SkyPath — Success Metrics

## 1. Purpose

Success metrics define how the SkyPath experience could be evaluated if the product were tested with representative users.

The metrics connect the project's product goals with observable user behaviour and experience outcomes.

Because SkyPath is a UX/HCI design project rather than a live production system, the metrics described here are proposed evaluation measures and target hypotheses rather than measured business results.

---

# 2. Measurement Philosophy

SkyPath should not define success solely through transaction completion.

A user may technically complete a booking while still experiencing:

- Confusion
- Uncertainty
- Excessive cognitive effort
- Difficulty comparing options
- Lack of pricing transparency
- Anxiety about whether the transaction succeeded

Therefore, success should be evaluated across four dimensions:

**Understanding → Decision Quality → Task Performance → Confidence**

---

# 3. Primary Success Indicators

The primary indicators for evaluating the SkyPath experience are:

1. Booking task completion
2. Task success rate
3. Time required to complete key tasks
4. Error rate
5. Comparison accuracy
6. Price comprehension
7. User confidence
8. Perceived cognitive effort
9. Navigation efficiency
10. Post-booking information retrieval

These measures should be evaluated together rather than interpreted individually.

---

# 4. Metric 01 — Task Completion Rate

### Definition

The percentage of participants who successfully complete a defined booking task.

### Example Tasks

- Search for a flight.
- Select a suitable flight.
- Choose a fare.
- Enter passenger information.
- Select a seat.
- Review the booking.
- Complete the simulated booking journey.

### Why It Matters

A booking interface must support successful completion of its core tasks.

### Proposed Measurement

**Task Completion Rate = Successful Task Completions / Total Task Attempts × 100**

### Target Hypothesis

The primary booking journey should achieve a high completion rate during usability testing, with failures investigated rather than treated only as numerical outcomes.

---

# 5. Metric 02 — Task Success Rate

Task completion alone does not show whether users completed a task correctly.

Task success should consider whether the participant achieved the intended outcome without significant assistance or incorrect decisions.

### Example

A participant may reach the payment screen but select a fare that does not satisfy the stated travel requirements.

The task may therefore be considered incomplete or partially successful depending on the evaluation protocol.

### Why It Matters

SkyPath aims to support informed decision-making, not merely navigation through screens.

---

# 6. Metric 03 — Task Completion Time

### Definition

The amount of time required to complete a defined task.

### Relevant Tasks

- Finding a suitable flight
- Comparing flight options
- Selecting a fare
- Completing passenger information
- Reviewing the booking

### Why It Matters

Long completion times may indicate unnecessary interaction, unclear information hierarchy or difficulty understanding available choices.

### Interpretation

A shorter time is not automatically better.

If users complete tasks faster because important information is hidden, the experience may become less transparent.

Time should therefore be interpreted alongside accuracy and confidence.

---

# 7. Metric 04 — Error Rate

### Definition

The frequency of user errors during important interactions.

Potential errors include:

- Incorrect passenger information
- Selecting an unintended flight
- Misunderstanding fare conditions
- Incorrect seat selection
- Missing required information
- Misinterpreting optional services
- Attempting to proceed with incomplete information

### Why It Matters

Error patterns can reveal weaknesses in information architecture, interaction design or system feedback.

### Evaluation Direction

The objective should be to prevent high-impact errors before they occur rather than relying only on error messages.

---

# 8. Metric 05 — Flight Comparison Accuracy

### Definition

The percentage of participants who correctly identify the flight that best matches a specified set of requirements.

### Example Scenario

A participant may be asked to identify:

> The flight with the lowest total price that includes baggage and has no more than one stop.

### Why It Matters

This directly evaluates whether the interface supports meaningful comparison.

### Success Indicator

Participants should be able to identify the appropriate option using the information presented in the interface without relying on external assistance.

---

# 9. Metric 06 — Price Comprehension

### Definition

The user's ability to correctly understand the relationship between the displayed fare, additional selections and final payable amount.

### Evaluation Questions

Participants could be asked:

- What is the current total?
- What is included in the fare?
- Which services were added?
- Which charges are optional?
- Why did the total change?

### Why It Matters

Price transparency is one of the central product objectives of SkyPath.

### Success Indicator

Users should be able to explain the final price accurately before completing payment.

---

# 10. Metric 07 — User Confidence

### Definition

The degree to which users feel confident about their decisions during the booking process.

### Possible Measurement

A post-task rating scale could be used, for example:

**1 — Not confident at all**

to

**5 — Extremely confident**

### Evaluation Questions

Participants could rate confidence after:

- Flight selection
- Fare selection
- Booking review
- Payment
- Confirmation

### Why It Matters

Confidence is a core intended outcome of the SkyPath experience.

---

# 11. Metric 08 — Perceived Cognitive Effort

### Definition

The amount of mental effort participants perceive while completing a task.

### Evaluation Direction

Participants could rate questions such as:

> How mentally demanding was this task?

using a standardised rating scale.

### Why It Matters

SkyPath aims to reduce unnecessary cognitive load while preserving necessary information.

### Interpretation

A low cognitive-effort score is not automatically desirable if participants achieve it by overlooking important information.

The metric should therefore be evaluated alongside comprehension and task accuracy.

---

# 12. Metric 09 — Navigation Efficiency

### Definition

The efficiency with which users move through the booking journey.

### Potential Measures

- Number of unnecessary backtracks
- Number of repeated actions
- Number of navigation errors
- Time spent locating important information
- Number of screens visited before completing a task

### Why It Matters

Navigation should support orientation without creating unnecessary interaction.

---

# 13. Metric 10 — Information Findability

### Definition

How easily users can locate important information when required.

### Information Examples

- Baggage allowance
- Flight duration
- Stops
- Fare conditions
- Seat cost
- Optional services
- Final price
- Booking reference

### Evaluation Method

Participants can be given specific information-retrieval tasks and measured on:

- Success
- Time
- Accuracy
- Assistance required

---

# 14. Metric 11 — Review Accuracy

### Definition

The user's ability to verify that the final booking accurately represents their previous selections.

### Review Items

Participants should be able to verify:

- Flight
- Date
- Route
- Fare
- Passenger information
- Seat
- Optional services
- Total cost

### Why It Matters

The review stage acts as a final confidence and error-prevention checkpoint.

---

# 15. Metric 12 — Post-Booking Findability

### Definition

The ability of users to locate important booking information after confirmation.

### Example Tasks

Participants may be asked to locate:

- Booking reference
- Itinerary
- Flight details
- Passenger information
- Seat assignment
- Post-booking management options

### Why It Matters

The product experience extends beyond payment.

---

# 16. UX Metric Framework

| Dimension | Metric | Example Measure |
|---|---|---|
| Understanding | Price comprehension | Correct interpretation |
| Understanding | Information findability | Task success/time |
| Decision-making | Comparison accuracy | Correct option identified |
| Performance | Task completion | Completion rate |
| Performance | Task time | Seconds/minutes |
| Performance | Error rate | Errors per task |
| Navigation | Navigation efficiency | Backtracks/actions |
| Confidence | User confidence | Rating scale |
| Cognitive experience | Perceived effort | Rating scale |
| Continuity | Post-booking findability | Retrieval success |

---

# 17. Qualitative Measures

Quantitative metrics should be complemented by qualitative research.

During usability testing, researchers could examine:

- User comments
- Points of hesitation
- Confusion
- Misinterpretations
- Questions asked
- Unexpected behaviours
- Emotional reactions
- Workarounds
- Reasons behind choices

Qualitative observations can explain why a quantitative metric changed.

---

# 18. Proposed Usability Evaluation

A future usability study could ask representative participants to complete a realistic booking scenario.

### Example Scenario

> You are planning a trip and need to find a flight that meets a specified budget, travel-time requirement and baggage need. Select the most appropriate flight, configure the booking and complete the simulated checkout.

The study could evaluate:

1. Search behaviour
2. Flight comparison
3. Fare understanding
4. Passenger information entry
5. Seat selection
6. Optional services
7. Booking review
8. Payment understanding
9. Confirmation
10. Post-booking retrieval

---

# 19. Success Criteria Framework

The following framework can be used during future evaluation:

### Excellent

Users complete the task accurately, understand the relevant information and report high confidence with minimal unnecessary effort.

### Acceptable

Users complete the task with minor hesitation or recoverable errors.

### Needs Improvement

Users require significant assistance, misunderstand important information or experience repeated friction.

### Critical Issue

Users cannot complete the task or make a high-impact decision incorrectly because the interface does not provide sufficient support.

---

# 20. Metric Interpretation

Metrics should never be interpreted in isolation.

For example:

A reduction in task completion time may appear positive, but if users simultaneously demonstrate lower comprehension, the design may have become faster at the cost of understanding.

Similarly, a high booking completion rate does not necessarily indicate a successful experience if users misunderstand pricing or fare conditions.

SkyPath therefore prioritises a balanced interpretation:

**Speed + Accuracy + Understanding + Confidence**

---

# 21. Business-Level Metrics

If SkyPath were eventually developed as a production product, additional business metrics could be considered.

Potential measures include:

- Booking conversion rate
- Booking abandonment rate
- Checkout completion rate
- Ancillary attachment rate
- Customer-support contact rate
- Post-booking engagement
- Repeat usage
- Customer satisfaction
- Customer retention

These metrics are not currently measured by the project.

They represent potential future evaluation areas.

---

# 22. Research Validation Loop

The proposed evaluation model follows an iterative cycle:

**Design → Test → Measure → Analyse → Identify Issues → Refine → Test Again**

This prevents metrics from becoming a final-stage reporting exercise.

Instead, measurement becomes part of the design process.

---

# 23. Success Definition

SkyPath should ultimately be considered successful when users can:

- Find an appropriate flight.
- Compare meaningful alternatives.
- Understand fare differences.
- Understand the final price.
- Complete required information accurately.
- Make informed selections.
- Review their booking confidently.
- Complete the transaction without unnecessary friction.
- Access their booking afterwards.

The desired experience can therefore be summarised as:

> **Users should be able to make a complex booking decision with clarity, accuracy and confidence.**

---

# 24. Measurement Limitation

The current project does not claim validated performance results.

No production conversion data, behavioural analytics or statistically representative usability study is being presented as evidence of product success.

The metrics in this document define a framework for future validation.

This distinction is important because a UX concept should not present proposed outcomes as measured results.

---

# 25. Summary

The SkyPath success framework evaluates more than whether a user reaches the final confirmation screen.

It considers whether the user:

**Understood the options → Made an appropriate decision → Completed the task accurately → Understood the final transaction → Felt confident about the outcome**

This measurement approach reflects the central product philosophy of SkyPath:

> **A successful booking is not simply a completed transaction. It is an informed and confident decision supported by a well-designed interaction.**
