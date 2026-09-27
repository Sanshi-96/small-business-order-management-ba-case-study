# Non-Functional Requirements

## Purpose

Non-functional requirements describe the quality characteristics and constraints under which the system should operate.

They do not primarily describe system features. Instead, they describe qualities such as performance, usability, security, reliability, and responsiveness.

## Non-Functional Requirements

### NFR-01 — Payment Gateway Performance

The system shall redirect the customer to the selected payment gateway within 3 seconds under normal operating conditions.

**Quality Attribute:** Performance

**Reason:**

A delay during payment redirection may negatively affect the customer experience and could result in incomplete transactions.

---

### NFR-02 — Responsive User Interface

The system shall provide a responsive interface that can be accessed using supported desktop, tablet, and mobile screen sizes.

**Quality Attribute:** Usability / Compatibility

**Reason:**

Customers and staff may access the system using different devices.

---

### NFR-03 — Role-Based Access

The system shall restrict access to order-management functions according to the user's assigned role.

**Quality Attribute:** Security

**Reason:**

Customers, staff, delivery personnel, and administrators may require different levels of access to order information and system functions.

## Requirement Clarification

The following areas require further stakeholder discussion:

- Supported browsers and devices
- Expected number of simultaneous users
- System availability requirements
- Maximum acceptable response time for other system operations
- Authentication requirements
- Data privacy requirements
- Data retention requirements
- Backup and recovery expectations