# Lessons Learned

## 1. Purpose

This document captures the key lessons learned while completing the
Business Analysis case study for a Small Business Order Management System.

The purpose of this reflection is to identify what was learned from the
analysis process, areas that were challenging, and how the experience can
be applied to future Business Analysis work.


## 2. Understanding the Problem Before the Solution

One of the main lessons learned was the importance of understanding the
business problem before proposing a solution.

Initially, it was easy to think about the system that could solve the
problem. However, the analysis showed that a Business Analyst should first
understand what is happening, who is affected, where problems occur, and
why they occur.

The As-Is process helped establish the current situation before defining
the To-Be process.


## 3. Business Requirements Are Different from Functional Requirements

A key learning was understanding the difference between business
requirements and functional requirements.

A business requirement describes the business outcome that needs to be
achieved, while a functional requirement describes a capability or
behaviour needed to support that outcome.

For example:

Business Requirement:

> Improve Customer Order Visibility.

Functional Requirement:

> The system shall allow customers to view the current status of their
> submitted orders.

This distinction helped avoid writing solution-level requirements when
trying to describe business needs.


## 4. Stakeholder Identification Requires Relevance

Another lesson was that stakeholders should be identified based on their
relationship with the problem, process, or proposed change.

Not every person or organization connected to a business is necessarily a
key stakeholder for a particular requirement.

The analysis showed the importance of considering who:

- Uses the process.
- Provides information.
- Performs activities.
- Makes decisions.
- Is affected by the change.
- Supports or implements the solution.


## 5. Elicitation Questions Need Structure

The elicitation exercise showed that asking questions is not enough.

Questions need to be structured around areas such as:

- Current situation
- Current process
- Pain points
- Root causes
- Stakeholders
- Information needs
- Exceptions
- Desired outcomes

Open-ended questions were useful for understanding the situation, while
clarification questions helped identify missing or ambiguous information.


## 6. Ambiguity Must Be Identified and Resolved

One of the strongest lessons from the case study was recognizing ambiguous
requirements.

For example:

> "Customers should be able to track their orders easily."

The word "easily" is ambiguous.

Further questions are needed to determine:

- How customers access tracking.
- What information they can see.
- What order statuses are available.
- Whether login or an order reference is required.
- When status information is updated.

This showed that a Business Analyst should not simply record a requirement.
The requirement needs to be clear enough to understand and eventually
validate.


## 7. As-Is and To-Be Processes Have Different Purposes

The As-Is process describes how the business currently operates.

The To-Be process describes the proposed future state.

Keeping these separate helped identify the differences between the current
process and the desired process.

The comparison also made it easier to identify process gaps and determine
which requirements could address those gaps.


## 8. User Stories Should Focus on the User

User stories helped convert requirements into a user-focused format.

The basic structure used was:

> As a [user], I want [capability], so that [value].

A useful lesson was to avoid combining multiple independent capabilities
into one user story.

For example, instead of:

> As an order staff member, I want to view, edit, process, and update
> orders.

Separate stories can be created for different capabilities.

This makes requirements easier to understand, prioritize, and validate.


## 9. Acceptance Criteria Make Requirements Testable

Acceptance criteria provided a way to determine whether a user story has
actually been completed.

The Given-When-Then structure helped convert vague expectations into
conditions that can be verified.

For example:

> Given a valid order reference, when the customer accesses the tracking
> interface, then the current order status is displayed.

This showed the importance of asking:

> "How will we know that this requirement has been successfully delivered?"


## 10. Prioritization Requires Business Context

MoSCoW prioritization demonstrated that not every requirement has the same
level of importance.

Requirements were categorized as:

- Must Have
- Should Have
- Could Have
- Won't Have

The analysis also showed that prioritization should not simply be based on
personal opinion.

Business value, operational impact, customer impact, dependencies,
constraints, and stakeholder expectations should be considered.


## 11. Traceability Connects the Analysis

The Requirements Traceability Matrix helped connect the different BA
artifacts.

The overall relationship was:

Business Problem
→ Business Requirement
→ Functional Requirement
→ User Story
→ Acceptance Criteria
→ Priority

This demonstrated how traceability can help identify missing
relationships, unnecessary requirements, and requirements that do not have
a clear business reason.


## 12. What I Would Improve

If I repeated this case study, I would improve the analysis by:

- Performing more detailed stakeholder elicitation.
- Validating the current-state process with actual stakeholders.
- Gathering more information about exceptions and business rules.
- Defining the complete order-status lifecycle.
- Validating MoSCoW priorities with stakeholders.
- Adding more detailed traceability between requirements and process steps.
- Exploring additional edge cases such as cancellation, duplicate orders,
  failed delivery, and payment failure.


## 13. Key Takeaways

The main lessons from this case study are:

1. Understand the problem before designing the solution.
2. Separate business requirements from functional requirements.
3. Identify stakeholders based on their relationship to the change.
4. Use structured elicitation questions.
5. Challenge ambiguous requirements.
6. Model both the current and future state.
7. Keep user stories focused on one clear user need.
8. Make requirements testable through acceptance criteria.
9. Prioritize requirements based on business context.
10. Maintain traceability throughout the analysis.


## 14. Final Reflection

This case study helped me understand that Business Analysis is not simply
about writing requirements.

It is about understanding a problem, asking the right questions,
identifying stakeholder needs, analysing the current process, defining a
desired future state, and connecting business needs to measurable
requirements.

The biggest lesson from this project is that a good solution starts with
a clear understanding of the problem.

The analysis process also showed the importance of questioning assumptions,
identifying ambiguity, and validating information instead of immediately
jumping to a technical solution.

These lessons will be applied to future Business Analysis and
technology-related projects.