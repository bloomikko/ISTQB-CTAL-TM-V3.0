# Notes and definitions / ISTQB Certified Tester Advanced Level Test Management (CTAL-TM) v3.0
## **breadth-first**
one test for each risk is assigned the highest priority, whereas the other tests are prioritized by their risk level coverage, used for gaining overall view as early as possible

## **Déjà vu**  
same set of risks are raised for each project, neglecting them in the long run

## **depth-first**
starting the test execution from highest risk level

## **functional testing**
evaluates the functions that a component or system should perform, checking the functional completeness, correctness and appropriateness

## **hybrid software development model**  
integrates elements from traditional sequential approaches and Agile practices
- *hybrid as a transition to Agile*: full transition to Agile may be difficult, so a hybrid approach is implemented
- *hybrid as fit for purpose*: if an organization or project cannot move to Agile, this approach can be implemented
- hybrid software development model test management activity examples:
  - understanding the capability to transition between traditional (sequential) and Agile methodologies
  - evaluating pros and cons of hybrid approach
  - ensuring adeptness of combining different methodologies

## **IDEAL**
improvement process for testing, can be used in either organizational or project level
- *I = initiating*: at the start of the improvement process, objectives and scope of the process improvements are agreed upon by all stakeholders
- *D = diagnosing*: current situation is assessed, usually against standardized framework (model-based test process improvement) or analyzing against specific metrics (analytical-based test process improvement)
- *E = establishing*: plan with all actions in prioritized order to improve the process
- *A = acting*: implementation of the plan, for example deploying, training and piloting the new processes
- *L = learning*: after deployment, learning what benefits were achieved, what did (not) work and acting on this information

## **keen beginnings**  
risk-based test approach is neglected when high short-term pressure to succeeding arises

## **non-functional testing**  
evaluating other than functional characteristics, "how well the system behaves", includes for example performance, compatibility, usability and security reliability

## **product (quality) risk**  
potential threats or failures that can affect the quality of your project deliverables, processes or outcomes

## **retrospective**  
event where the test team measures how well risk-based testing realized the benefits

## **risk analysis**  
identifying and assessing the potential impact and likelihood of product risks

## **risk assessment**  
categorization of risks (by product/project risk, quality characteristics), determining the risk level, likelihood and impact for each risk item

## **risk-based testing**  
- identification, assessment, monitoring and mitigation of risks to drive testing
- techniques:
  - heavyweight (formal with defined procedures and detailed documentation)
    - *hazard analysis*: identifying underlying hazards in every risk
    - *cost of exposure*: likelihood of failure and its cost, also cost of testing for these failures
    - *failure mode and effect analysis (FMEA)*: identifying quality risks and their causes and effects, assigning severity, priority and detection rates
    - *fault tree analysis*: mapping the potential failures as relation to each other, eventually revealing the root causes
  - lightweight (less thorough)
    - *Systematic Software Testing (SST)*
    - *Pragmatic Risk Analysis and Management (PRAM)*
    - *Product Risk Management (PRISMA)*

## **risk identification**  
- stakeholders' process of identifying quality risks through several techniques: expert interviews, independent assessments, retrospectives, risk workshops, brainstorming, checklists and referring to past experience
- ensuring involving the broadest possible sample of stakeholders is vital: it must be ensured that all relevant stakeholders have a chance to participate
- often also produces by-products which are not product risks, such as general issues in the project or flaws in documentation

## **risk impact**  
the magnitude how the risk affects if it happens, can be influenced by factors such as criticality of the affected feature, damage to reputation or lack of reasonable workarounds

## **risk level**  
- the result of combining risk likelihood and impact
- sometimes can be very difficult to determine: using historical data and consulting key project stakeholders can ease the process

## **risk likelihood**  
the possibility how likely the risk is bound to happen, can be influenced by factors such as complexity of technology, tools and system architecture, maturity of the organization and time, resource, budget and management pressure

## **risk management**  
two activities: risk analysis (risk identification and assessment) and control (risk monitoring and mitigation)

## **risk mitigation**  
- activities that reduce the likelihood of failures, such as testing, contingency plan (workarounds), transferring the risk to a third party or risk acceptance
- higher risk levels should be treated more extensively whereas lower level areas can be taken care with less effort
- several contextual factors to be considered when choosing the means of risk mitigation, such as test items, levels, types and team, quality characteristics, SDLC's intricacies and regulatory requirements
- can be applied anytime in test monitoring and controlling to address the residual (remaining) risk level

## **risk monitoring**  
several activities:
- quality risk analysis results are used in test planning to focus the testing towards correct areas with correct techniques
- risk analysis guide the selection of test conditions in test analysis
- risk-based prioritization guides the sequences of test execution activity

## **S.M.A.R.T. goal methodology**
methodology for defining project test objectives and exit criteria
- *S = specific*: clear and ambiguous
- *M = measurable*: quantifiable and have specific criteria to measure progress in order to determine if it has been reached
- *A = achievable*: feasible when considering resources, timeframe and capabilities
- *R = relevant*: aligned with other project objectives
- *T = timely*: well-defined specific timeframe and deadline for completion

## **software development lifecycle (SDLC)**  
high-level representation of software development process, various ones exist

## **stakeholder churn**  
stakeholders change over time and constant risk analysis is lacked &rarr; risk analysis should not be done only in the beginning of testing process

## **stakeholder/power-interest matrix**  
tool for assessing the stakeholders' expertise, interest, influence and the interconnections between these attributes, contains four quadrants:
- *promoters (high influence, high interest)*: key collaborators for shaping the test strategy and plan
- *latents (high influence, low interest)*: although lower interest, their decisions remain critical for resource allocation and high-level project direction
- *defenders (low influence, high interest)*: useful for qualitative feedback, usually kept engaged through regular updates and discussions
- *apathetics (low influence, low interest)*: can provide unique insights if for example updated on significant milestones

## **test approach**  
- not an one-size-fits-all solution: requires careful consideration towards test levels, types and techniques
- factors to be considered when choosing the appropriate approach:
  - *domain*: for which the product will be created/modified, for example medicine and insurance fields vary a lot so therefore their own nuances must be considered
  - *organizational goals and overarching quality characteristics*: these can affect the approach a lot, for example as one organization can focus on value of testing, whereas another can emphasize efficiency of defect detection - balancing between these is crucial, but the organization can still emphasize some areas more than others
  - *project goals and type of project*: for example, customer specific versus market oriented product requires different testing approaches
  - *test resources*: for example, experience-based testing requires good domain knowledge, whereas mobile testing requires testing on different devices and operating systems
  - *SDLC used for the project*: for example, software lifecycle with CI/CD approach requires more automation, whereas traditional models have their own nuances
  - *interfaces with other system*: if the test item is integrated to one system versus multiple ones, the test approach must be aligned
  - *availability of test data*: does the project need anonymised test data, or does it handle sensitive information such as social security numbers etc.?

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

## **test level**
- group of test activities that are organized and managed together
- test management activities:
  - *component (unit) testing*: defining the scope, objectives and completion criteria, involving testers to code reviews, coordinating with the development team
  - *component integration testing*: determining integration sequences and test combinations, overseeing the integration progress aligns with other testing strategies
  - *system integration testing*: ensuring the scope and objectives of system integration testing are clear, having oversight of the progress, outcomes and issue management
  - *system testing*: allocating the resources, selecting the tools and scheduling the testing (in Agile projects, the system testing is integrated with iterative story testing, ensuring a continuous testing)
  - *acceptance testing*: confirming the fulfillment of acceptance criteria with stakeholders, plan testing activities, coordinate acceptance testing logistics, facilitating tests at the customer's site and ensuring the quality standards outside development context
 
## **test process improvement**
- at least 30-40% of project costs account for testing &rarr; optimizing the effectiveness and efficiency is necessary
- can emerge from for example dissatisfaction of current test results, unexpected defects, changing circumstances or benchmark results

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

## **test objective**
- should address aspects of quality and quantity and be measurable or evaluable
- examples:
  - reaching exit criteria in defined timeframe
  - complying rules, regulations and standards of specific industry
  - enhancing test automation, for example by measuring the number of tests or percentage how much the tests cover the system

## **test plan**
describes the objectives, resources and processes of a test project, should always contain a scope, objectives and exit criteria

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

## **test strategy**  
describes the approach to testing in specific context to meet the organization's (quality and testing) objectives

## **test type**  
four different approaches for testing, test management activities for each type:
- *functional testing management*: crafting a test strategy that aligns with functional requirements and project objectives, coordinating resources for functional aspects of the system
- *non-functional testing management*: establishing performance benchmarks and managing them during testing, overseeing tests that ensure non-functional standards such as security or reliability
- *black-box testing management*: ensuring that tests cover all user scenarios and business requirements, collecting the feedback from stakeholders to improve black-box testing approaches
- *white-box testing management*: overseeing the use of code coverage tools, ensuring that technical insights are taken care in test planning process

## **experience-based testing**
## **incremental development model**
## **iterative development model**
## **sequential development model**
## **Test Maturity Model integration**
## **test policy**
## **TPI NEXT**
## **goal question metric (GQM)**
## **indicator**
## **measure**
## **metric**
