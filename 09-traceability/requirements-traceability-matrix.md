# Requirements Traceability Matrix

## 1. Purpose

The purpose of this Requirements Traceability Matrix (RTM) is to establish
relationships between the identified business requirements, functional
requirements, user stories, acceptance criteria, and prioritization.

The matrix helps ensure that identified business needs are represented in
the proposed solution and can be traced through the requirements and
validation process.

It also helps identify gaps, unnecessary requirements, and requirements
that do not have a clear connection to an identified business need.


## 2. Traceability Structure

The requirements in this case study are traced through the following
relationship:

Business Problem
→ Business Requirement
→ Functional Requirement
→ User Story
→ Acceptance Criteria
→ MoSCoW Priority

This relationship provides a connection between the original business
need and the expected system behaviour.


## 3. Requirements Traceability Matrix

| Business Requirement | Functional Requirement | User Story | Acceptance Criteria | Priority |
|-----------------------|------------------------|------------|----------------------|----------|
| BR-01 Improve Order Information Accuracy | FR-04 Automatically create and store order record | US-01 Place an Order | US-01 AC-01, AC-03 | Must Have |
| BR-01 Improve Order Information Accuracy | FR-03 Staff view supported orders centrally | US-06 Review Order Information | US-06 AC-01, AC-02, AC-03 | Must Have |
| BR-01 Improve Order Information Accuracy | — | US-04 Provide Missing Order Information | US-04 AC-01, AC-02, AC-03 | Must Have* |
| BR-02 Reduce Missed Orders | FR-03 Centralized order-management interface | US-05 View Centralized Orders | US-05 AC-01, AC-02, AC-03 | Must Have |
| BR-02 Reduce Missed Orders | FR-04 Automatically create and store order record | US-01 Place an Order | US-01 AC-01, AC-03 | Must Have |
| BR-02 Reduce Missed Orders | — | US-07 Process an Order | US-07 AC-01, AC-02, AC-03 | Must Have |
| BR-03 Improve Customer Order Visibility | FR-01 Order confirmation | US-02 Receive Order Confirmation | US-02 AC-01, AC-02, AC-03 | Should Have |
| BR-03 Improve Customer Order Visibility | FR-05 Customer can view current order status | US-03 View Order Status | US-03 AC-01, AC-02, AC-03 | Should Have* |
| BR-03 Improve Customer Order Visibility | FR-05 Order status visibility | US-08 Update Order Status | US-08 AC-01, AC-02, AC-03 | Must Have |
| BR-03 Improve Customer Order Visibility | — | US-10 Update Preparation Status | US-10 AC-01, AC-02, AC-03 | Should Have |
| BR-03 Improve Customer Order Visibility | — | US-12 Update Delivery Status | US-12 AC-01, AC-02, AC-03 | Should Have |
| BR-02 Reduce Missed Orders | — | US-09 View Orders for Preparation | US-09 AC-01, AC-02, AC-03 | Must Have |
| BR-02 Reduce Missed Orders | — | US-11 View Orders Ready for Delivery | US-11 AC-01, AC-02, AC-03 | Must Have |


## 4. Functional Requirement Traceability

| Functional Requirement | Related Business Requirement | Related User Story |
|-------------------------|-----------------------------|---------------------|
| FR-01 Order confirmation | BR-03 | US-02 |
| FR-02 Customer selects available payment method | BR-01 | US-01 |
| FR-03 Authorized staff view supported orders centrally | BR-02 | US-05, US-06 |
| FR-04 Automatically create and store order record | BR-01, BR-02 | US-01 |
| FR-05 Customer views current order status | BR-03 | US-03, US-08 |


## 5. User Story Traceability

| User Story | Related Business Requirement | Acceptance Criteria | Priority |
|------------|-----------------------------|----------------------|----------|
| US-01 Place an Order | BR-01, BR-02 | US-01 AC-01 to AC-03 | Must Have |
| US-02 Receive Order Confirmation | BR-03 | US-02 AC-01 to AC-03 | Should Have |
| US-03 View Order Status | BR-03 | US-03 AC-01 to AC-03 | Should Have* |
| US-04 Provide Missing Order Information | BR-01 | US-04 AC-01 to AC-03 | Must Have* |
| US-05 View Centralized Orders | BR-02 | US-05 AC-01 to AC-03 | Must Have |
| US-06 Review Order Information | BR-01 | US-06 AC-01 to AC-03 | Must Have |
| US-07 Process an Order | BR-01, BR-02 | US-07 AC-01 to AC-03 | Must Have |
| US-08 Update Order Status | BR-03 | US-08 AC-01 to AC-03 | Must Have |
| US-09 View Orders for Preparation | BR-01, BR-02 | US-09 AC-01 to AC-03 | Must Have |
| US-10 Update Preparation Status | BR-03 | US-10 AC-01 to AC-03 | Should Have |
| US-11 View Orders Ready for Delivery | BR-02 | US-11 AC-01 to AC-03 | Must Have |
| US-12 Update Delivery Status | BR-03 | US-12 AC-01 to AC-03 | Should Have |


## 6. Traceability Observations

The matrix indicates that the identified user stories are connected to
the business requirements established during the earlier analysis.

The traceability relationships also show that customer visibility,
centralized order management, order accuracy, and order processing are
represented across the requirements and user stories.

Some user stories do not currently have a direct functional requirement
mapping. These relationships should be reviewed and validated during
further requirements analysis.


## 7. Traceability Gaps and Validation Points

The following areas require further analysis or stakeholder validation:

- The relationship between missing-information handling and formal
  functional requirements should be clarified.
- Preparation and delivery status updates may require additional formal
  functional requirements.
- The exact relationship between payment functionality and the current
  business requirements requires further elicitation.
- MoSCoW priorities should be validated with relevant stakeholders.
- The exact order-status lifecycle should be confirmed.
- Any new requirements identified during further elicitation should be
  added to the traceability matrix.


## 8. Benefits of Traceability

Maintaining traceability helps to:

- Confirm that business needs are represented in requirements.
- Identify requirements that are not connected to a business need.
- Identify business needs that have not been addressed.
- Support impact analysis when requirements change.
- Support test planning and validation.
- Improve communication between business and technical stakeholders.
- Maintain consistency between BA artifacts.


## 9. Traceability Direction

Traceability can be performed in two directions.

### Forward Traceability

Forward traceability follows a requirement from its original business
need toward implementation and validation.

Example:

Business Requirement
→ Functional Requirement
→ User Story
→ Acceptance Criteria


### Backward Traceability

Backward traceability starts from a requirement or feature and traces it
back to the original business need.

Example:

User Story
→ Functional Requirement
→ Business Requirement
→ Business Problem


## 10. Conclusion

The Requirements Traceability Matrix provides a structured connection
between the business problem, requirements, user stories, acceptance
criteria, and prioritization decisions.

The matrix should be maintained and updated when requirements change
throughout the project lifecycle.