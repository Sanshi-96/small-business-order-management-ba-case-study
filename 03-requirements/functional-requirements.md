# Functional Requirements

## Purpose

Functional requirements describe what the proposed system should do to support the identified business needs.

The requirements below were derived from the initial problem analysis and business requirements.

## Functional Requirements

### FR-01 — Order Confirmation

The system shall send an order confirmation notification to the customer after a valid order has been successfully submitted.

**Related Business Requirement:** BR-03

---

### FR-02 — Payment Method Selection

The system shall allow customers to select an available payment method during the order process.

**Related Business Requirement:** BR-01

**Note:** The specific payment methods must be confirmed with the business during requirements elicitation.

---

### FR-03 — Centralized Order Management

The system shall allow authorized staff to view orders received through supported sales channels from a centralized order-management interface.

**Related Business Requirement:** BR-02

---

### FR-04 — Automatic Order Record Creation

The system shall automatically create and store an order record when a customer successfully submits an order.

**Related Business Requirement:** BR-01

---

### FR-05 — Customer Order Tracking

The system shall allow customers to view the current status of their submitted orders.

**Related Business Requirement:** BR-03

## Initial Functional Requirement Summary

| ID | Requirement | Related Business Requirement |
|---|---|---|
| FR-01 | Send order confirmation | BR-03 |
| FR-02 | Select available payment method | BR-01 |
| FR-03 | Centralized order management | BR-02 |
| FR-04 | Automatically store order record | BR-01 |
| FR-05 | View order status | BR-03 |

## Requirements Requiring Further Clarification

The following details require stakeholder clarification:

- Which sales platforms should be supported?
- Which payment methods should be available?
- What information should be included in the order confirmation?
- What order statuses should customers be able to see?
- How should staff update order status?
- How should cancelled or failed orders be handled?
- What information should customers provide to access order tracking?

## Ambiguity Analysis

### Original Requirement

> Customers should be able to track their orders easily.

### Identified Ambiguities

The word **"easily"** is ambiguous because it does not define measurable system behaviour.

Questions requiring clarification include:

- Where will customers track their orders?
- Will customers need to log in?
- Can customers use an order reference number?
- Which order statuses should be displayed?
- How frequently should the status be updated?
- Should customers receive notifications when the status changes?
- Which communication channels should be supported?

### Refined Requirement

> The system shall allow customers to view the current status of their submitted orders through an order-tracking interface using an appropriate order identifier.

### Further Clarification Required

The exact tracking mechanism and order-status values must be confirmed with stakeholders before the requirement is finalized.