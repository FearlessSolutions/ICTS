# ICTS

The Problem
INTAKE ISSUE:  Department of Commerce (DOC) Bureau of Industry and Security (BIS) expects to publish a final rule in April 2023 that prohibits a specific party from continuing to provide ICTS services to both critical infrastructure entities (banks, energy sectors, police departments, commercial farming, etc.) and individual citizens.  Upon publishing this rule in the federal register, it is expected that entities using these services may seek waivers or exceptions to this prohibition. Currently, BIS has created one intake email to intake these requests.  There are more than 2 million active users and over 5000 companies using this specific service and it’s possible many of them will seek exceptions. 


LICENSING ISSUE: Second, in August 2023, BIS plans to publish a rule that allows the government to impose restrictions of US companies and citizens on the use of specific information and communications technology or services (ICTS) imported from foreign countries that pose a threat to US National Security. ICTS is defined as software services from China (including Hong Kong), Russia, Cuba, Iran, North Korea, and Venezuela’s Maduro Regime. As part of the Rule, affected US parties will receive written notification outlining the restrictions and impacted software or hardware/services that may require licensing/exceptions similar to that of the current controls on exports of critical technology. The draft Rule may also provide a time-limited opportunity for US parties to voluntarily disclose their use of these products and for the government to consider those responses before finalizing the Rule.  It is more than likely that this rule will go “final” into Q2 FY 24, which marks the point at which companies would seek licenses (aka exceptions) to specific prohibitions. The rules are still being drafted, and this requirement should be considered when establishing the immediate requirements for an intake system above. 


The government currently does not have a system that supports the submission, adjudication, and determination of these disclosures in either circumstance. Without a clear process and system, the government will be in violation of the response deadlines set forth in the Rule. Additionally, poor management of these requests for disclosure creates additional risks for national security; creating significant roadblocks for effective management and analysis of growing risks to the supply chain.  


Main Users


Role
Responsibilities
Estimated Number of Users
US Parties notified as part of the Rule
Verification of their identity as an employee of a US company impacted by the Rule
Submission of an exemption request for the Rule
Notification of the final determination 
500,000
DOC Employees
Review and adjudication of the exemption request
Passing a determination in regard to the exemption request
15-80





High-level Approach
Create low-fidelity submission and adjudication system for the processing of the intake exemption requests that will coincide with the delivery of the written notifications of the restrictions to US industry. Upon notification, US companies may be eligible to submit exemption requests through the system.
Main Goal
Improved operational efficiency, response speed, and visibility into the adjudication process for ICTS company disclosures and requests for extensions or exemptions. 
Success Metrics
Metric
How will we measure it?
Benchmark
 Adjudication time 
Time from submission receival to final determination


 
Determination Response 
Number of exemptions where a final determination is passed and explained
 100%
Visibility
Amount of information available to submitters
5 Pieces of Information (Request, Request Date, Determination, Determination Reasoning, Determination)


Solution Alignment
Key Features
Required Features 
Ability for Industry to Submit Exemptions & Extension
Ability for ICTS to Log-in to view submissions
Link from BIS Website to application
Submission Success Notification

Security Requirements
FISMA high
Fedramp high
Post-launch Features (updates, expansion)
SSO
Case Management System for Extensions and Exemptions Adjudication
Intake of rule comments and feedback
Intake of tips or disclosures for ICTS violations
Adjudication Final Determination Notification
Reporting
Key Flows
Show some mocks/embeds of the experience. Link to any other documentation as necessary. In general, it’s helpful to organize these around certain user journeys/use cases. Show enough of a clickthrough where people can walk away with a reasonable understanding of how the product works.
Design Research, Prototypes, Content
Add helpful links here.
Open Issues + Key Decisions
Question / Issue
Decision / Mitigation Tactic
Notes
How will we interview people (potential users) who aren’t supposed to know about this yet?
UAT Testing post development with ICTS staff, BIS Staff, and proxy industry users from  Internal staff at Fearless
That’s tricky. How do we use usability testing, working in confidentiality?
One option the team could do is to neutralize the sensitivity component.
Are there any existing exemption request systems in across agencies?
CFIUS Case Management System | U.S. Department of the Treasury
CFIUS and ICTS will not overlap
What do you believe will be users’ biggest concerns around this action? 
Companies want to submit an exemption so that they can use the product/service
User that needs to log in and submit data, review the data, submit corporate data and respond with the result, and ideally provide the status of that submission


Is there an existing exemption process that is already in place?
Not for ICTS, the team is only 4 people. Other exemption requests processes


Are there parts of the exemption process that require paperwork? Where and when does that handoff happen?




What is our end users' motivation? Are there any ramifications for using prohibited ICTS but not filing an exemption?
Loss of operational efficiency after a product is ICTS restricted and sunset.


What are the specific ICTS impacted? How many imports do we anticipate needing exemptions for?




Are export companies the same as import companies? Will we be able to use any of the export discoveries for ICTS?
No 


When is the notification date?
April 1st


How long will DOC be excepting exemption requests?
The Final rule will be publish in August


Are there any upstream or downstream data dependencies?




What occurs during the adjudication of an exemption request? What is the workflow?




What information is required to make an exemption request determination?
Company Name, Address, phone number 
POC name, email, phone 
product(s) names (can we list all of their products where they can be selected as a drop down? I can provide a list.) and the ability to add more than one product as some companies have multiple products?
Maybe a couple of narrative boxes the customer can use to explain the reason they are requesting an extension/exemption.  Maybe give them a choice via drop down to indicate whether they are asking for an extension or exclusion?


How can we verify that a US company was impacted by the Rule?
We have the subpoena list with the following information: Customer name, customer address, product group, product name


Will Help Desk be supporting this effort?




Who are our primary contacts at ICTS?
Evan Broderick, Mark Johnson


Who will be our PO?
Mark Johnson


Will we be working on ICTS for just MVP and then switching back to export? Or is staying on ICTS?




Would companies using  ICTS system have BIS CIN or other unique identification number? If no, how will the company be uniquely identifiable?




Will users be submitting the request in the form of a document (e.g. PDF) or they are expected to fill out an online form?




Will BIS Azure cloud be used for this project? Who will be managing the cloud etc.? (Simon computing? Or internal resources or Fearless).




What is the target date for publishing the ICTS information on the BIS website?
Waiting for Under Secretary announcement of office, should be ready to post 2/20 (BUT NOT POSTED UNTIL WE HAVE PA/OGC CONCURRENCE, AT LEAST A WEEK EARLIER)


What information is required to be published on the BIS website?




Will we be processing extension requests?




What’s the difference between exemption requests and extension requests?




Are these the only comments (20) that are being addresed re: the revised rule? Regulations.gov




Will affected products be limited by product type or more specifically by version number/types?







Launch Readiness
Date
Milestone
Audience
Description
 TBD
ICTS Exemption Request Discovery
ICTS Team, Other DOC Team, Impacted Companies
Getting a detailed understanding of the requirements, workflow, and timelines for ICTS Exemption Requests.
Lean UX activities
Low fidelity prototypes and workflows completed
Established Vision and OKRs
 TBD
Technical Solution Approval
BIS Team, ICTS Team
Approval of low fidelity MVP Technical Approach
3/16
System Build
BIS Team, ICTS Team
Creation of the low fidelity system
3/17-
3/24
System Testing
BIS Team, ICTS Team
Regression, accessibility, and penetration testing
3/25-
3/31
Training
ICTS Team, Other DOC Team, Impacted Companies
Training of DOC employees (BIS, ICTS, Help Desk) on the new system, training documentation & FAQs for external users 
2/20
Communications
ICTS Team, Impacted Companies
Integration of the following documentation into the restriction notification/ ICTS website:
Introduction/link to the system
Instructions on how to set up a user
Instructions on how to use the system

Operational Readiness
Area
Question
Answer (Y/N)
Instructions / Notes
Accessibility
Is this launch compliant with our accessibility standards?


Must meet 508 and plain language standards
Support
Are we clear with error and confirmation messaging across functionality?
 
 
Onboarding
Will new learning material be needed (or updates to existing documentation)?
 
 
Onboarding
Have we planned for how new users will learn about this product/feature? How?
 
 
Onboarding
Is this functionality available to all users at once, or phased rollout?
 
 All users at once
Help desk
Have we provided documentation to help desk?
 
 
Help desk
Have we demoed new functionality to help desk?
 
 
Help desk
Have we determined the flow for problem escalation with help desk?
 
 
Architecture / Security
Are we adding any new roles and permissions?
 
 Yes, internal adjudicators, Help Desk, role approvers, and submitters
Architecture
Is data being transferred across products?
 
 
Architecture
Is there a dependency on the architecture team’s workload? Is the architecture team aware?
 
 
Architecture
Are we sunsetting any legacy systems?
 N
 
Security
Are we changing or affecting anything related to DOC security protocol?
 
 
Policy
Do we have any requirements for Paperwork Reduction Act? Do we need to get started on PRA submission?
 
 
Policy
Are there any other policy or legal aspects we need to consider before launch?
 
 



Technical Details
Add links to relevant technical details.
Data Elements
Requested Technical Solutions
Associated Business Problem
Implementation Approach
MVP or Post-MVP
Business Process Flow - ability to follow cases and assign persons.
Operational Efficiency in Exemption Request Management


MVP
FISMA mid/high secure
Fedramp high
Secure Exemption Request Management
Involve Vaultes
MVP
Searchable Exemptions
Management of Multiple Request




Mapping capability - Geolocation, and visual map






Cross domain solution 0 ability to upload or "send" a document to a JWICS email address, directly, and a high side "database" that mirrors the same database on unclass.






API to customs data (both ACE and export data), that has entity resolution (automatic resolution of an "entity name", address, or phone, fax, to information submitted by a party under consideration)




Post-MVP
Ability to link to publicly available import information, such as Import Yeti






API to a "derogatory information" flag






Auto resolve and flag to a company listed in IMS-R as a company of concern or under investigation






A way to track case flow (business process of "who" the case is with, internally, with visual analytics and who is "next" in the process flow)
Visibility into the adjudication process




Ability to rapidly upload case documents
Management of multiple documents associated with one case




Link the DOC website to our BIS ICTS Portal. - Explain the entire ICTS program (leadership, policy, intent, and next steps in the development of the ICTS program - get messaging from OCPA.)
Launch, onboarding, training


MVP
Ability to upload information and have the system output a standardized set of information as a Report of Investigation (ROI)
Reporting




Ability for any company to register, and submit their standard administrative information, name, address, phone fax, and the ability for another company to search and find that company, "by name and address only", in that database.
User Management
is there a corporate database we can validate against so we’re not recreating the wheel as far as companies? Or products through HS codes? https://www.trade.gov/harmonized-system-hs-codes

How do foreign Saas companies handle import controls in the first place? @evan


Ability to map international addresses.









