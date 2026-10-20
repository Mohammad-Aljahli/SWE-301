# 4.1 Team Information

**Project title:** Subscription & Storage Manager  
**Group letter:** GROUP E  
**Team members:** Saleh Alhajri, Mohammad Aljahli, Mohamed Alaaeldin Daoud 
**GitHub repository URL:** [Insert the actual GitHub repository URL]

**One-sentence summary:** A web-based application that helps users manually track digital subscriptions, renewal dates, recurring costs, and cloud-storage usage in one place.

# 4.2 Problem and Users

People often subscribe to several digital services, such as entertainment platforms, productivity applications, and cloud-storage providers. Information about renewal dates, recurring charges, and available storage may be spread across separate provider accounts, emails, or personal notes. This makes it harder to review all subscriptions together, estimate monthly expenses, and identify approaching renewals. The proposed project focuses on the inconvenience of tracking this information across different locations; it does not require access to real financial accounts or provider credentials.

The problem matters to individuals who manage multiple subscriptions and want a clearer view of their recurring commitments. A missed renewal date can result in an unexpected charge, while unclear storage information can make it difficult to plan usage. The system will provide a single dashboard where users enter and maintain their own records. For the semester prototype, all entries will use simulated data, and storage usage will be recorded manually rather than fetched from external services.

The two main actors are **User**, who manages subscription and storage records, and **Administrator**, who maintains demonstration accounts and sample data for the prototype. The administrator will not access real subscription credentials or payment information.

# # 4.3 Existing Solutions

The current process often involves checking separate service websites, emails, or spreadsheets to track subscription costs, renewal dates, and storage usage. This can make it difficult for users to maintain a clear overview of their subscriptions and storage information.

| Existing process or solution | Useful features | Limitation for the proposed users | Source |
|---|---|---|---|
| Current process: separate service websites, emails, or spreadsheets | Users can manually track subscription details without sharing financial credentials. | Information is scattered across multiple sources, making it difficult to review renewal dates and total costs together. | [Insert actual interview, observation, or document evidence and date] |
| Rocket Money | Provides subscription and spending-management features. | Its broader financial-management approach may be unnecessary for users who only want to manually track subscription and storage information. | https://www.rocketmoney.com/ |
| Google One | Provides Google-account storage management and storage-plan information. | It primarily focuses on Google's storage ecosystem rather than a combined manual overview of subscriptions and storage across different providers. | https://one.google.com/ |

**Comparison findings:** Existing solutions provide useful subscription-management or storage-management features. However, the proposed system focuses on combining manually entered subscription details, renewal dates, recurring costs, and cloud-storage usage in a single, simple dashboard. This approach avoids financial-account connections and third-party service integration, making the prototype more manageable for a three-student team.
# 4.4 Proposed Solution and Justification

The Subscription & Storage Manager will be a small web application in which a user can create and maintain subscription records, including service name, price, billing interval, and next renewal date. It will display upcoming renewals and calculate an estimated monthly total from saved subscription records. Users can also record a cloud-storage service's total capacity and used capacity, then view the resulting usage percentage. All information will be entered manually using simulated data.

The proposed dashboard addresses the inconvenience of reviewing multiple sources by presenting these records together. Its deliberately narrow scope avoids bank connections, automated billing, provider-account access, and live storage synchronization. A three-student team can build a small prototype using standard web-development tools, a lightweight database, and reusable interface components. The team may reuse an established web framework and a date-handling library after reviewing their licenses and suitability.

# 4.5 Scope and Workflows

| In scope | Out of scope |
|---|---|
| Create, view, edit, and delete manually entered subscription records | Bank or payment-card connections |
| Display upcoming renewal dates | Automated subscription cancellation or payment processing |
| Calculate an estimated monthly subscription total | Direct login to third-party subscription accounts |
| Record storage capacity and used storage for cloud services | Live cloud-storage synchronization or file access |
| Display storage usage percentages | Mobile-native application or AI-based recommendations |
| Use simulated accounts and demonstration data | Real confidential, financial, or personal datasets |

| Workflow | Main actor and goal | Expected outcome |
|---|---|---|
| 1. Manage a subscription | User enters a service name, price, billing interval, and renewal date, then saves or updates the record. | The subscription record is stored and shown in the user's list. |
| 2. Review renewals and costs | User opens the dashboard to see upcoming renewal dates and an estimated monthly subscription total. | The dashboard shows the recorded renewal schedule and calculated cost. |
| 3. Track cloud-storage usage | User enters or updates used and total capacity for a cloud-storage service and opens the storage overview. | The storage record is saved and its usage percentage is displayed. |

# 4.6 Initial Requirements

## Functional Requirements

| ID | Functional requirement | Priority |
|---|---|---|
| FR-01 | The system shall allow a user to create a subscription record containing a service name, price, billing interval, and next renewal date. | Must |
| FR-02 | The system shall allow a user to view their saved subscription records. | Must |
| FR-03 | The system shall allow a user to edit an existing subscription record. | Must |
| FR-04 | The system shall allow a user to delete an existing subscription record. | Must |
| FR-05 | The system shall display saved subscriptions in ascending order of next renewal date. | Must |
| FR-06 | The system shall calculate and display an estimated monthly total by converting saved subscription prices to monthly equivalents. | Must |
| FR-07 | The system shall allow a user to create or update a storage record containing service name, used capacity, and total capacity. | Must |
| FR-08 | The system shall calculate and display the storage usage percentage for each saved storage record. | Must |

## Non-Functional Requirements

| ID | Category | Measurable requirement |
|---|---|---|
| NFR-01 | Performance | With a demonstration dataset of 50 subscriptions and 20 storage records, the dashboard shall load within 2 seconds in at least 9 of 10 local test runs on the agreed test device. |
| NFR-02 | Usability | At least 4 of 5 test participants shall successfully add a subscription and find its renewal date without assistance within 3 minutes. |
| NFR-03 | Data integrity | The system shall reject all 10 predefined invalid storage inputs in the agreed test set, including negative capacities, zero total capacity, and used capacity greater than total capacity. |

# 4.7 Development Approach

The team will use **incremental development**. The initial requirements define a manageable core, but user feedback may reveal changes needed in the dashboard layout and record-entry forms. Developing the system in small increments will allow the team to test essential functions early and refine later features without waiting until the entire prototype is complete.

The first increment will support subscription records, the second will add renewal ordering and monthly-cost calculations, and the third will add storage records and usage percentages. Each increment will be reviewed and tested before the next is added. The team may reuse a web framework and interface components to reduce implementation time. The main risks are limited semester time, unclear user expectations, and incorrect date or capacity calculations; early reviews and focused tests will address these risks.

# 4.8 Team Plan and Risks

## Coordinator Roles

| Role | Team member | Responsibility |
|---|---|---|
| Process and Project Coordinator | Saleh Alhajri | Coordinate schedule, task tracking, and repository progress. |
| Requirements and Design Coordinator | Mohammad Aljahli | Coordinate requirement reviews, workflows, and interface planning. |
| Implementation and Quality Coordinator | Mohamed Alaaeldin Daoud | Coordinate implementation, integration, and testing. |

All three members will contribute to every major project activity; coordinator roles organize work rather than isolate responsibilities.

## Milestones

| Milestone | Main planned output | Coordinator |
|---|---|---|
| 1. Proposal | Project proposal and initial requirements |Saleh Alhajri|
| 2. Requirements and models | Refined requirements and system models | Mohammad Aljahli |
| 3. Design and initial prototype | Initial design and working subscription-record prototype | Mohamed Alaaeldin Daoud |
| 4. Final prototype, testing, and presentation | Integrated prototype, test evidence, and presentation | Mohamed Alaaeldin Daoud |

## Risks

| Risk | Impact | Planned response |
|---|---|---|
| Requirements change after development begins | High | Review the three workflows with potential users before implementation and prioritize Must requirements. |
| Incorrect renewal or monthly-cost calculations | High | Define billing-interval rules and test monthly and annual subscriptions with known expected results. |
| Inaccurate or sensitive data entered into the prototype | Medium | Use only simulated data, validate numerical inputs, and avoid collecting provider credentials or payment details. |

# 4.9 Sources, AI Use, and Contributions
Sources
- SWE301 Assignment 1: Project Proposal and Initial Requirements, instructor-provided assignment document.
- Rocket Money official website: https://www.rocketmoney.com/ (official product website; verify claims before submission).
- Google One official website: https://one.google.com/ (official product website; verify claims before submission).
AI Use Disclosure
ChatGPT (OpenAI) was used to help organize and revise the proposal text, clarify requirements, and compare the draft against the assignment instructions. The team must independently review the final wording, confirm factual claims using the listed sources, and revise any inaccurate or unsupported suggestions before submission. The team remains responsible for the final work.

## ### Team Contributions

| Member | Contribution | GitHub Evidence |
|---|---|---|
| Saleh Alhajri | Defined the project problem, identified the target users, described the proposed solution, and reviewed the final proposal. | [Insert actual commit or pull request link] |
| Mohammad Aljahli | Researched existing solutions, defined the project scope, and prepared the three workflows. | [Insert actual commit or pull request link] |
| Mohamed Alaaeldin Daoud | Prepared the functional and non-functional requirements, development approach, and project risks. | [Insert actual commit or pull request link] |

All three team members participated in reviewing the proposal and will contribute to the major development activities throughout the semester.
