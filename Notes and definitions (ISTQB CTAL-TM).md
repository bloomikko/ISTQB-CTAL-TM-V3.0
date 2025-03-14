# Notes and definitions / ISTQB Certified Tester Advanced Level Test Management (CTAL-TM) v3.0
## **hybrid software development model**  
integrates elements from traditional sequential approaches and Agile practices
- *hybrid as a transition to Agile*: full transition to Agile may be difficult, so a hybrid approach is implemented
- *hybrid as fit for purpose*: if an organization or project cannot move to Agile, this approach can be implemented
- hybrid software development model test management activity examples:
  - understanding the capability to transition between traditional (sequential) and Agile methodologies
  - evaluating pros and cons of hybrid approach
  - ensuring adeptness of combining different methodologies

## **risk-based testing**  
identification, assessment, monitoring and mitigation of risks to drive testing

## **stakeholder/power-interest matrix**  
tool for assessing the stakeholders' expertise, interest, influence and the interconnections between these attributes, contains four quadrants:
- *promoters (high influence, high interest)*: key collaborators for shaping the test strategy and plan
- *latents (high influence, low interest)*: although lower interest, their decisions remain critical for resource allocation and high-level project direction
- *defenders (low influence, high interest)*: useful for qualitative feedback, usually kept engaged through regular updates and discussions
- *apathetics (low influence, low interest)*: can provide unique insights if for example updated on significant milestones

## **test completion**  
- handling the test artifacts, evaluating the test process (for example, seeking improvements) and product, communicating the test closure to stakeholders
- usually occurs at project milestones, such as release or the end of an iteration
- unresolved defects are handled by change requests or product backlog items
- test completion activities:
  - *create and approve the test completion report*:
    - ensuring all testing has been done and test objectives are met
    - collecting the relevant information from various documents created in the test process &rarr; test completion report which is approved by all relevant stakeholders
  - *archive testware*: emphasis on reusable testware for future projects, temporary archival for all testware in configuration management system
  - *handover testware*: delivering work products to those who need them
  - *perform all necessary tasks to clean the test environment and to restore it to a pre-defined
state*
  - *perform/collect/document lessons learned*: done in retrospectives

## **test context**  
unique conditions and constraints that influence the test process, essential for test managers to accordingly align testing with specific needs and objectives

## **test control**  
- ongoing activity: taking measures to test monitoring results and reporting the test status to stakeholders
- compares actual progress against the test plan and applies corrective actions as needed
- basically reacts to test management activities
- test control activities:
  - *implementing the test plan and control directives*
  - *managing deviations from planned testing*
  - *treating newly identified and changed risks*
  - *establishing readiness to begin testing*
  - *granting and obtaining approval for test completion based on the exit criteria*

## **test item**  
work product being tested

## **test management activities at various test levels**  
- *component (unit) testing*: defining the scope, objectives and completion criteria, involving testers to code reviews, coordinating with the development team
- *component integration testing*: determining integration sequences and test combinations, overseeing the integration progress aligns with other testing strategies
- *system integration testing*: ensuring the scope and objectives of system integration testing are clear, having oversight of the progress, outcomes and issue management
- *system testing*: allocating the resources, selecting the tools and scheduling the testing (in Agile projects, the system testing is integrated with iterative story testing, ensuring a continuous testing)
- *acceptance testing*: confirming the fulfillment of acceptance criteria with stakeholders, plan testing activities, coordinate acceptance testing logistics, facilitating tests at the customer's site and ensuring the quality standards outside development context

## **test management activities for different test types**  
- *functional testing management*: crafting a test strategy that aligns with functional requirements and project objectives, coordinating resources for functional aspects of the system
- *non-functional testing management*: establishing performance benchmarks and managing them during testing, overseeing tests that ensure non-functional standards such as security or reliability
- *black-box testing management*: ensuring that tests cover all user scenarios and business requirements, collecting the feedback from stakeholders to improve black-box testing approaches
- *white-box testing management*: overseeing the use of code coverage tools, ensuring that technical insights are taken care in test planning process

## **test management activities for various software development lifecycle models**  
- sequential models rely more on early planning, estimations and predominant choices &rarr; not very flexible and reactive
- iterative models focus for continuous delivery, monitoring and iterative development &rarr; reactive to changes

## **test management activities to plan, monitor and control**  
ensuring that the test process is well-defined, adaptable to changes and results in a product that satisfies the project requirements and stakeholder expectations
- *test planning*:
  - crafting a test plan which appropriate scope &rarr; identifying all (non-)functional requirements for ensuring complete test coverage, ensuring that the test cases validate the system from all angles (for example, black- and white-box testing methodologies)
  - risk assessment and mitigation plan: pinpointing potential vulnerabilities that could impact the workflow or the product, developing the mitigation measures for these risks
  - allocating resources and synchronizing them in complex environments, for example if there are several teams or stakeholders to be collaborated with
- *test monitoring*:
  - monitoring and reviewing that the test execution goes against the established plan, ensuring that the testing is focused on the most critical areas
  - selecting the right tools and establishing continuous monitoring with CI/CD systems
  - constant collaboration with developers
- *test control*:
  - reacting to monitoring results accordingly in response to new insights, challenges and evolving project dynamics &rarr; being able to change
  - defining the quality gates that are followed in the testing process

## **test monitoring**  
ongoing activity: tracking test progress, results and deviations from planned testing, produces source material for test controlling

## **test planning**  
- defining test objectives, approach, scope, resources, schedule, deliverables and participants/stakeholders
- should be initiated ASAP in the development process before requirements are identified
- test planning activities:
  - *understanding the context and organizing test planning*: understanding the test policy, strategy, scope and the test item
  - *identify and analyze product risks*: identifying and assessing the potential impact and likelihood of product risks
  - *identify risk treatment approaches*: using risk analysis, addressing appropriate risk treatment approaches (preventive/corrective/mitigated)
  - *defining test approach, estimating and allocating test resources*:
    - approach: basis on organizational test strategy, regulatory standards or any constraints given by the project
    - resources: making sure that required test resources such as staff, tools, environments and data are provided for test activities
  - **establish the test plan**: plan accepted by all stakeholders 

## **test process**  
includes seven activities, can be applied in various levels such as project, program or portfolio, each level has its own test plan (**bolded** are emphasised by the syllabus):  
- **test planning**
- **test monitoring and control**  
- test analysis
- test design
- test implementation
- test execution
- **test completion**

## **test stakeholders** (not definitive list, test managers conduct a stakeholder analysis)  
- *developers and development leads/managers*: for example unit testing
- *testers, test leads/managers*: individuals who prepare testware, for example developing test plans and contributing to the testing process
- *project managers, product owners and business users*: stakeholders who specify requirements and requested level of quality, review work products and make decisions based on test results
- *operations team*: ensures the system's readiness for production
- *customers and users*: customers purchase the product, users directly utilize it

**experience-based testing**
**functional testing**
**hybrid software development model**
**incremental development model**
**iterative development model**
**non-functional testing**
**product risk**
**quality risk**
**retrospective**
**risk analysis**
**risk assessment**
**risk identification**
**risk impact**
**risk level**
**risk likelihood**
**risk management**
**risk mitigation**
**risk monitoring**
**sequential development model**
**S.M.A.R.T. goal methodology**
**software development lifecycle**
**test level**
**Test Maturity Model integration**
**test objective**
**test plan**
**test policy**
**test process improvement**
**test strategy**
**test type**
**TPI NEXT**
**goal question metric (GQM)**
**IDEAL**
**indicator**
**measure**
**metric**
