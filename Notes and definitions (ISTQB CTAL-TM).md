# Notes and definitions / ISTQB Certified Tester Advanced Level Test Management (CTAL-TM) v3.0
## **analytical-based test process improvement**  
identifying problems in testing by using the data from the project or team itself &rarr; deriving the improvements from analysis, many times quantitative approaches are used to identify problems as using only qualitative approaches can result in wrong recommendations which is not supported by the data

## **breadth-first**
one test for each risk is assigned the highest priority, whereas the other tests are prioritized by their risk level coverage, used for gaining overall view as early as possible

## **Déjà vu**  
same set of risks are raised for each project, neglecting them in the long run

## **depth-first**
starting the test execution from highest risk level

## **experience-based testing**  
testing which relies on tester's past experiences, skills and intuition &rarr; useful for detecting test cases which can easily slip through rigid test methodologies

## **functional testing**
evaluates the functions that a component or system should perform, checking the functional completeness, correctness and appropriateness

## **goal question metric (GQM)**  
- analytical approach for test process improvement, a framework to define and analyze metrics which are tailored to stakeholder information needs
- measurement goals contain a quality aspect of an object that is measured for a particular purpose, perspective and context
- these goals are then formed into questions defining the quality aspect from stakeholder point of view, after which the metrics are selected to provide necessary information to answer the questions
- example:
  - goal, an object or entity: measurements include products, processes and resources
  - question used to assess the goals: is the current performance satisfactory, is it improving, is the improvement enough?
  - metric, every question is assessed with the metrics: for example, lines of code, module/program size, level of user satisfaction

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

## **incremental development model**  
SDLC model where the software is built gradually &rarr; for example a few features are fully developed, afterwards few more features are added and so on until the product is completely ready, requires a clear completion goal

## **iterative development model**  
SDLC model where the development happen in smaller cycles with constant feedback loop &rarr; for example, one feature might not be fully completed in one iteration but the work is continued in the next cycle with the feedback from previous cycle's results

## **keen beginnings**  
risk-based test approach is neglected when high short-term pressure to succeeding arises

## **measures, metrics and indicators**  
- analytical approach for test process improvement, a quantitative method to assess how well the test process is performed
- key attributes to be measured include effectiveness, efficiency and predictability &rarr; one or several metrics can be selected to assess each attribute, collected and analyzed data can be used to identify improvements

## **model-based test process improvement**  
- test improvement model is used to improve test processes, usually on organizational level but can be applied on project level
- the improvements are introduced by comparing the testing against external best practices

## **non-functional testing**  
evaluating other than functional characteristics, "how well the system behaves", includes for example performance, compatibility, usability and security reliability

## **product (quality) risk**  
potential threats or failures that can affect the quality of your project deliverables, processes or outcomes

## **retrospective**  
- meeting where the team reviews methods, collects lessons learned and decides the changes and actions to improve
- in sequential models, retrospectives are part of test completion, whereas in Agile development, retrospectives are held at the end of each iteration
- retrospective steps:
  - *introduction*: goal and agenda are reviewed
  - *collecting data*: data about what happened during the iteration or project, can me qualitative such as timeline of key events or quantitative such as test progress, defects and effectiveness
  - *deriving improvements*: collected data is analyzed to understand the current situation and generating improvement suggestions
  - *deciding on improvement actions*: improvement actions are derived and prioritized by creating an improvement plan, also goals and relevant metrics can be defined to measure the impact of actions on the identified problems
  - *close retrospective*: retrospective itself is reviewed

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

## **root cause analysis**  
- analytical approach for test process improvement, identifies the solutions to remove the problem causes instead of just addressing the obvious symptoms
- for example, a set of defects can be collected which are analyzed and compiled into clusters &rarr; using cause-effect diagrams to identify and address by improvements the root causes of these defects

## **sequential development model**  
SDLC model where the development is strictly divided into non-overlapping segments which follow each other

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
 
## **Test Maturity Model integration (TMMi)**  
- model for improving test processes, consists of five maturity levels
- all levels (except first) have test process areas and improvement goals, also contains (sub-)practices and examples

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
 
## **test policy**  
high-level document of the organization &rarr; defines testing vision, goals and principles in organizational level

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

## **test tool**  
- either business (commercial, open source or custom type) or technical tools, administrated by test manager
- examples of evaluating the tool: improvement opportunities, compatibility with current tools in the organization, how does the tool integrate to SDLC, proof-of-concept evaluation
- should have guidelines, training, incremental rollout and owner

## **test tool cost-benefit analysis**  
made to ensure the positive ROI, must consider the (non-)recurring activities and costs such as initial or recurring licensing costs, integrating, training and maintenance - also opportunity costs (time spent on the tool-related activities instead of spending it on the actual testing) must be considered

## **test tool decision aspects**  
- *regulations and security*: for example, commercial tools could be best for safety-critical software as they usually met the required standards and certifications
- *financial aspects*: the tool can have one-time or running license costs, also training and maintenance costs must be considered
- *stakeholder requirements*: custom tools most likely meet all the requirements by relevant stakeholders if commercial and open-source tools are not sufficient enough
- *existing software landscape and tool strategy*: locked vendors, integrated systems and regulations might dictate what tools are appropriate for the organization

## **test tool lifecycle**  
- four stages:
  - *acquisition*: decision to acquire the tool has been made, afterwards the tool owner must be determined &rarr; they make the usage decisions
  - *support and maintenance*: tool owner is accountable for this stage &rarr; maintenance can be assigned for example to one person who works as an admin
  - *evolution*: tool suitability must be maintained in time &rarr; changes in environment, business needs or vendor decisions can render the tool useless or other changes are needed
  - *retirement*: essential to preserve the data produced by the tool
 
## **test tool metrics**  
for example, test management tools can measure test execution statuses, requirements management tool have traceability on requirements coverage of tests, defect management tools can measure status, severity and priority

## **test tool selection viewpoints**  
the tool should be considered from various viewpoints of different stakeholders: for example, the senior management is interested in positive return of interest (ROI), whereas the tool users appreciate usability

## **test type**  
four different approaches for testing, test management activities for each type:
- *functional testing management*: crafting a test strategy that aligns with functional requirements and project objectives, coordinating resources for functional aspects of the system
- *non-functional testing management*: establishing performance benchmarks and managing them during testing, overseeing tests that ensure non-functional standards such as security or reliability
- *black-box testing management*: ensuring that tests cover all user scenarios and business requirements, collecting the feedback from stakeholders to improve black-box testing approaches
- *white-box testing management*: overseeing the use of code coverage tools, ensuring that technical insights are taken care in test planning process

## **TPI NEXT**  
- model for improving test processes, consists of 16 key areas
- each area contains a specific test process aspect, such as strategy, metrics, tools and environment
- each area has four maturity levels, also areas contain checkpoints for maturity assessment

## **anomaly**  
## **defect**  
## **defect report**  
## **defect workflow**  
## **failure**  
## **metric**  
## **test estimation**  
## **test objective**  
## **test progress**  
## **planning poker**  
## **three-point estimation**  
## **Wideband Delphi**  
