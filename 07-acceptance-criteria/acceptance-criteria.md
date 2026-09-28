# Acceptance Criteria

## 1. Purpose

The purpose of this document is to define the conditions that must be
satisfied for the selected user stories to be considered complete and
acceptable.

The acceptance criteria provide clear and testable expectations for the
behaviour and outcomes associated with each user story.

The criteria are derived from the identified user stories, functional
requirements, business requirements, and proposed To-Be process.


## 2. Acceptance Criteria Format

The acceptance criteria use the following structure:

> Given [initial condition],
> When [action or event occurs],
> Then [expected result].

This structure helps describe the situation, action, and expected outcome
in a clear and testable manner.


## 3. Customer Acceptance Criteria

### US-01 — Place an Order

**Acceptance Criteria**

- **AC-01:** Given the customer has entered the required order
  information, when the customer submits the order, then the order is
  successfully created.
- **AC-02:** Given the order information is incomplete, when the customer
  attempts to submit the order, then the missing required information is
  identified.
- **AC-03:** Given an order is successfully created, then the order is
  assigned an identifiable order reference.


### US-02 — Receive Order Confirmation

**Acceptance Criteria**

- **AC-01:** Given a valid order has been successfully submitted, when the
  order is created, then the customer receives an order confirmation.
- **AC-02:** The order confirmation includes the relevant order reference.
- **AC-03:** The confirmation is provided only after the order has been
  successfully recorded.


### US-03 — View Order Status

**Acceptance Criteria**

- **AC-01:** Given the customer has a valid order reference, when the
  customer accesses the order-tracking interface, then the current order
  status is displayed.
- **AC-02:** The displayed status corresponds to the latest status
  recorded for the order.
- **AC-03:** If the order reference is invalid or does not exist, then the
  customer is informed that the order cannot be found.


### US-04 — Provide Missing Order Information

**Acceptance Criteria**

- **AC-01:** Given required order information is missing or incorrect,
  when the customer is contacted, then the customer can provide the
  required information.
- **AC-02:** Given the customer provides corrected information, when the
  information is submitted, then the relevant order record can be updated.
- **AC-03:** The updated information is available to the staff member
  responsible for processing the order.


## 4. Order Staff Acceptance Criteria

### US-05 — View Centralized Orders

**Acceptance Criteria**

- **AC-01:** Given an authorized order staff member accesses the order
  management interface, then available orders are displayed in one
  centralized view.
- **AC-02:** Each displayed order contains the information required by
  staff to identify and review the order.
- **AC-03:** Newly submitted orders become available for authorized staff
  to review.


### US-06 — Review Order Information

**Acceptance Criteria**

- **AC-01:** Given an authorized order staff member selects an order, when
  the order is opened, then the relevant order information is displayed.
- **AC-02:** Staff can identify whether required order information is
  complete.
- **AC-03:** Orders with missing or incorrect information can be
  identified before processing.


### US-07 — Process an Order

**Acceptance Criteria**

- **AC-01:** Given an order contains the required information, when an
  authorized staff member processes the order, then the order can proceed
  to the fulfilment stage.
- **AC-02:** An order cannot proceed when required information has not been
  provided.
- **AC-03:** The order remains associated with its order reference
  throughout the processing stage.


### US-08 — Update Order Status

**Acceptance Criteria**

- **AC-01:** Given an authorized order staff member is managing an order,
  when the staff member updates the order status, then the new status is
  recorded.
- **AC-02:** The latest recorded status is available to authorized users.
- **AC-03:** The customer can view the updated status when customer status
  visibility is applicable.


## 5. Packing Staff Acceptance Criteria

### US-09 — View Orders for Preparation

**Acceptance Criteria**

- **AC-01:** Given an order has reached the preparation stage, when
  authorized packing staff access the order list, then the order is
  available for preparation.
- **AC-02:** The order information required for preparation is displayed.
- **AC-03:** Packing staff can identify the order using its order
  reference.


### US-10 — Update Preparation Status

**Acceptance Criteria**

- **AC-01:** Given packing staff have started or completed preparation,
  when the appropriate status is selected, then the preparation status is
  recorded.
- **AC-02:** The updated preparation status is available to authorized
  users.
- **AC-03:** The status update is associated with the correct order.


## 6. Delivery Staff Acceptance Criteria

### US-11 — View Orders Ready for Delivery

**Acceptance Criteria**

- **AC-01:** Given an order has been prepared and is ready for delivery,
  when authorized delivery staff access the relevant orders, then the
  order is displayed as ready for delivery.
- **AC-02:** Delivery staff can identify the order using its order
  reference.
- **AC-03:** The information required to complete the delivery is
  available to authorized delivery staff.


### US-12 — Update Delivery Status

**Acceptance Criteria**

- **AC-01:** Given delivery staff are handling an order, when the delivery
  status is updated, then the new status is recorded against the correct
  order.
- **AC-02:** When the order is successfully delivered, then the order can
  be marked as completed.
- **AC-03:** The completed status is available to authorized users and,
  where applicable, visible to the customer.


## 7. Acceptance Criteria Summary

| User Story | Main Acceptance Outcome |
|------------|-------------------------|
| US-01 | Customer can successfully submit a valid order |
| US-02 | Customer receives confirmation for a successfully created order |
| US-03 | Customer can view the current order status |
| US-04 | Missing or incorrect information can be provided and updated |
| US-05 | Authorized staff can view centralized orders |
| US-06 | Staff can review order information |
| US-07 | Valid orders can proceed to fulfilment |
| US-08 | Order status can be updated and recorded |
| US-09 | Packing staff can view orders requiring preparation |
| US-10 | Preparation status can be recorded |
| US-11 | Delivery staff can view orders ready for delivery |
| US-12 | Delivery status can be recorded and completed |


## 8. Exceptions and Validation Considerations

The following scenarios require further stakeholder validation before the
acceptance criteria can be considered final:

- Order cancellation after submission.
- Customer changes after an order has been processed.
- Failed delivery.
- Duplicate orders.
- Payment failure or incomplete payment.
- Invalid order references.
- Notification delivery failure.
- Orders containing incomplete information.
- Orders that cannot be fulfilled.
- Rules governing who can update each order status.


## 9. Relationship to User Stories

Acceptance criteria provide the conditions used to determine whether the
requirements represented by the user stories have been satisfied.

The relationship can be summarized as:

User Story
→ Acceptance Criteria
→ Testing / Validation
→ User Acceptance


## 10. Definition of Acceptance

A user story can be considered ready for acceptance when all applicable
acceptance criteria have been satisfied and the expected user or business
outcome has been demonstrated.

Final acceptance should be validated with the relevant stakeholders.