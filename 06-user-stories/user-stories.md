# User Stories

## 1. Purpose

The purpose of this document is to describe the key user needs identified
for the proposed order-management process from the perspective of the
main stakeholders.

The user stories are derived from the identified business requirements,
functional requirements, elicitation findings, and proposed To-Be process.

Each user story describes a specific actor, the required capability, and
the expected business or user value.


## 2. User Story Format

The user stories follow the common structure:

> As a [user/actor], I want [action/capability], so that [benefit/value].

The stories are kept focused on a single actor, action, and outcome to
support clear understanding, development, and testing.


## 3. Customer User Stories

### US-01 — Place an Order

**User Story**

> As a customer, I want to place an order through the supported ordering
> process so that I can purchase the required products or services.

**Related Requirements:** FR-04, BR-02


### US-02 — Receive Order Confirmation

**User Story**

> As a customer, I want to receive an order confirmation after successfully
> submitting an order so that I know my order has been received.

**Related Requirements:** FR-01, BR-01


### US-03 — View Order Status

**User Story**

> As a customer, I want to view the current status of my order so that I
> can understand its progress without repeatedly contacting staff.

**Related Requirements:** FR-05, BR-03


### US-04 — Provide Missing Order Information

**User Story**

> As a customer, I want to provide missing or corrected order information
> when requested so that my order can be processed accurately.

**Related Requirements:** BR-01


## 4. Order Staff User Stories

### US-05 — View Centralized Orders

**User Story**

> As an order staff member, I want to view orders through a centralized
> interface so that I can monitor incoming orders in one place.

**Related Requirements:** FR-03, BR-02


### US-06 — Review Order Information

**User Story**

> As an order staff member, I want to review order information before
> processing an order so that incomplete or incorrect information can be
> identified.

**Related Requirements:** FR-03, BR-01


### US-07 — Process an Order

**User Story**

> As an order staff member, I want to process a valid order so that it can
> move to the fulfilment stage.

**Related Requirements:** BR-01, BR-02


### US-08 — Update Order Status

**User Story**

> As an order staff member, I want to update the order status so that the
> current progress of an order is accurately recorded.

**Related Requirements:** FR-05, BR-03


## 5. Packing Staff User Stories

### US-09 — View Orders for Preparation

**User Story**

> As a packing staff member, I want to view orders that require
> preparation so that I can prepare the correct orders for delivery.

**Related Requirements:** BR-01, BR-02


### US-10 — Update Preparation Status

**User Story**

> As a packing staff member, I want to update the preparation status of an
> order so that other users can see its current progress.

**Related Requirements:** BR-03


## 6. Delivery Staff User Stories

### US-11 — View Orders Ready for Delivery

**User Story**

> As a delivery staff member, I want to view orders that are ready for
> delivery so that I know which orders need to be delivered.

**Related Requirements:** BR-02


### US-12 — Update Delivery Status

**User Story**

> As a delivery staff member, I want to update the delivery status of an
> order so that the order progress can be accurately recorded.

**Related Requirements:** BR-03


## 7. User Story Summary

| ID | Actor | User Need | Expected Value |
|----|-------|-----------|----------------|
| US-01 | Customer | Place an order | Submit an order |
| US-02 | Customer | Receive confirmation | Know the order was received |
| US-03 | Customer | View order status | Understand order progress |
| US-04 | Customer | Provide missing information | Enable accurate processing |
| US-05 | Order Staff | View centralized orders | Monitor orders in one place |
| US-06 | Order Staff | Review order information | Identify incomplete/incorrect information |
| US-07 | Order Staff | Process valid order | Move order to fulfilment |
| US-08 | Order Staff | Update order status | Maintain accurate progress |
| US-09 | Packing Staff | View orders for preparation | Prepare correct orders |
| US-10 | Packing Staff | Update preparation status | Communicate progress |
| US-11 | Delivery Staff | View orders ready for delivery | Identify delivery work |
| US-12 | Delivery Staff | Update delivery status | Maintain delivery progress |


## 8. User Story Assumptions

The user stories are based on the current understanding of the business
problem and proposed future-state process.

The following points require stakeholder validation:

- Exact ordering channels supported by the future process.
- Exact order statuses required.
- Which users are authorized to update each status.
- How customers will access their order status.
- What information is required before an order can be processed.
- How order cancellation and modification should be handled.
- How failed or incomplete deliveries should be handled.
- What notifications should be provided to customers.


## 9. Relationship to Requirements

The user stories provide a user-focused representation of selected
functional and business requirements.

The relationship can be summarized as:

Business Requirement
→ Functional Requirement
→ User Story
→ Acceptance Criteria

For example:

BR-03: Improve Customer Order Visibility
→ FR-05: Customer can view current order status
→ US-03: Customer wants to view order status
→ Acceptance Criteria


## 10. Next Step

The next stage is to define acceptance criteria for each user story.

Acceptance criteria will describe the conditions that must be satisfied
for each user story to be considered complete and successfully delivered.