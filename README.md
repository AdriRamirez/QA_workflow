# QA WORKFLOW
## Quality Assurance (QA)
Quality Assurance or QA is a systematic process on how to perform tasks that “ensure” the quality of the project from the beginning to the end. Quality Assurance is proactive, it aims at preventing issues before they are detected in the product. So, QA’s priority is to increase the team’s productivity, prevent issues, and optimize the processes. This is done via documentation, planning, and training. This cannot be mixed up with Quality Control or QC, which objective is to determine which are the quality requirements for the QA to fulfill.

![](https://github.com/AdriRamirez/QA_workflow.github.io/blob/main/Images/QAvsQC.jpg?raw=true)

## QA Workflow in Video Games
During the development of the game the workflow changes with the different phases of production, therefore the tasks and priorities change as we go forward and we are asked for different feedback based on the priorities of that development phase.

To reduce errors and minimize bugs, different tools are used to help us carry out our work. The organization is very important since we have to be constantly in contact with our team and provide quality feedback so that we can polish every feature as much as possible.

### QA Team
The team keeps track of documentation, communicates with the development team, introduces automation, and code quality tools. Also, is responsible for refining product requirements and building strategies to fill them out. 

Most of the work of the QA team in video games is detecting errors that break the game experience. But it is not the only job:

* **Playing** and testing games in methodical and experimental approaches in order to find errors or broken elements.

* Recording, archiving and analyzing those errors to further **categorize** them later.

* **Experiment** with in-game settings and altered states in order to find more errors.

* Perform previously executed play testing methods on a new version of the game to **catalog** the errors that remain.

* **Analyze** any written materials, in-game writing, and menu copy to check for quality, consistency and clarity.

With this roles in mind, we can categorize the QA team in different charges and responsibilities:

* **QA Tester:** This role's primary responsibility is to test and play through specific parts of the game to identify all errors. It can be either gameplay, tech, progression, or graphics. After that, they need to create proper documentation of the issues they encountered (bug report) and then test again fixed issues

* **Senior QA tester:** These are just experienced game testers. For that, they are often responsible for testing bigger parts of the game or the most important ones. They might mentor Junior QA Testers.

* **QA Lead:** Their job is to manage other testers, create and maintain proper work schedules, design high-level test plans, and usually mentor more junior team members.

* **QA Automation Tester & QA Test Engineer:** Their job is to create and improve needed tools and processes to test the game. With that, they can automate the testing process by creating the script for specific repeatable actions.

* **QA Director:** This position is often see on big studios and is the responsible of all the QA Teams. This role is more focused on planning and maintaining the proper work pipeline, processes, career development, and budgeting.


## Agile Methodoloy
The Agile methodology is a way to manage a project by breaking it up into several phases. It involves constant collaboration with stakeholders and continuous improvement at every stage. Once the work begins, teams cycle through a process of planning, executing, and evaluating. Continuous collaboration is vital, both with team members and project stakeholders.

It’s a process for managing a project that involves constant collaboration and working in iterations. Agile project management works off the basis that a project can be continuously improved upon throughout its life cycle, with changes being made quickly and responsively.

Agile is one of the most popular approaches to project management due to its flexibility, adaptability to change, and high level of customer input. This methodology is not a singular framework, the term is used including different frameworks. The most popular ones been Scrum and Kanban.

* **Scrum:** This type is based on performing periodic intervals of work, called _sprints_. Each sprint has a fixed duration and at the end a partial delivery is made with the progress. This methodology has 4 stages:

  * **Planning:** the objectives of the sprint and the steps to achieve them are based.

  * **Execution:** Involves the development of objectives and includes a brief daily meeting to review the work.

  * **Review:** the finished result or prototype is presented.

  * **Retrospective:** the way in which the project has been executed is analyzed, detecting possible failures and points of improvement for the next sprint.
  
![](https://github.com/AdriRamirez/QA_workflow.github.io/blob/main/Images/scrum.png?raw=true)

* **Kanban:** Is an Agile framework used to visualize and improve workflows, reduce waste and inefficiency, and increase team focus by limiting work in progress. Unlike Scrum, kanban is not based around sprints. Instead, Kanban is flexible and adapts to existing roles and team structures by categorizing tasks on a Kanban board according to what production phase they are in (To-Do, In Progress, and Complete).

![](https://github.com/AdriRamirez/QA_workflow.github.io/blob/main/Images/kanban.png?raw=true)

## Waterfall Methodoloy
Waterfall model is a linear, sequential development process that is often used in project management. It divides the process into distinct phases, each of which must be completed before moving on to the next. The phases are typically:

* **Requirements** gathering and analysis: In this phase, the requirements for the project are gathered and analyzed to determine what needs to be developed.

* **Design:** In this phase, the design for the project is created, including architecture, interface, and database design.

* **Development:** In this phase, the project is developed based on the design and requirements.

* **Testing:** In this phase, the project is tested for bugs, errors, and usability.

* **Deployment:** Once the product have no errors, it is released to the market.

* **Maintenance:** The project is maintained and updated as necessary.

The waterfall methodology is called so because it follows a linear, cascading sequence of phases, where each phase must be completed before the next one can begin. It is a structured and disciplined approach to project managing that can be useful in certain situations, but it also has limitations, such as a lack of flexibility and difficulty in accommodating changes in requirements during the development process.

![](https://github.com/AdriRamirez/QA_workflow.github.io/blob/main/Images/waterfall.png?raw=true)

## Bugs Report
Reporting a bug in QA testing in a video game studio typically involves the following steps:

* **Reproduce** the bug: First, you need to ensure that you can reproduce the bug consistently. Try to identify the exact steps that lead to the bug, and take note of any error messages or other relevant information.

* **Document** the bug: Create a detailed report of the bug, including information such as the platform, the version of the game, the steps to reproduce the bug, and any error messages or other relevant information. Screenshots or videos can also be helpful in demonstrating the bug.

* **Prioritize** the bug: Assign a priority level to the bug based on its severity and impact on the game. Bugs that affect gameplay or prevent progress are typically assigned a higher priority.

* **Submit** the bug report to the appropriate person or team, such as the QA lead or the development team. Be sure to provide all relevant information and details in the report.

* **Follow up** on the bug report to ensure that it is being addressed by the appropriate team. If necessary, provide additional information or clarification to help resolve the bug.

By following these steps, you can help ensure that bugs are reported and addressed in a timely and efficient manner, ultimately leading to a better quality game for players.

### Bug Report Template
**Title:** [Brief description of the bug]

**Description:**

[Provide a detailed description of the bug, including what is happening, where it is happening, when it is happening, and any relevant error messages or other information.]

**Steps to Reproduce:**

[Provide a step-by-step guide to reproduce the bug, including any necessary setup or prerequisites.]

**Expected Behavior:**

[Describe what you expected to happen when performing the steps to reproduce the bug.]

**Actual Behavior:**

[Describe what actually happened when performing the steps to reproduce the bug.]

**Priority:**

[Assign a priority level to the bug based on its severity and impact on the game. For example, High, Medium, or Low.]

**Attachments:**

[Include any relevant attachments, such as screenshots, videos, or log files.]

**Environment:**

[Provide information about the environment in which the bug was observed, including the platform, the version of the game, and any relevant hardware or software details.]

By using a bug report template like this, you can ensure that your bug reports are comprehensive, well-organized, and easy for others to understand, which can help expedite the bug-fixing process.

![](https://github.com/AdriRamirez/QA_workflow.github.io/blob/main/Images/bug_template.png?raw=true)

Example of a template using Github Issues

### Bug Fixing
If the bug found is small and it can be fixed easily, it should be prioritaze and start working on the remaining features of the game once fixed. Otherwise, if the bug is big, programmers should have few more days to work on that. It should not take more than that to fix the bug. However, if that situation occurs, only the specialist in that land should focus on the bug. The other members will continue working on the project.

![](https://github.com/AdriRamirez/QA_workflow.github.io/blob/main/Images/bug_diagram.png?raw=true)

## References
[Quality Assurance & Quality Control 1](https://gamecloud-ltd.com/video-game-quality-assurance-testing-process-part-1/)

[Quality Assurance & Quality Control 2](https://jelvix.com/blog/quality-assurance-vs-quality-control/)

[QA Team](https://8bitplay.com/blog/ultimate-super-turbo-hd-guide-to-the-game-development-roles-qa-game-tester-jobs#what-is-QA-tester)

[QA Tester role](https://pinglestudio.com/blog/game-testing/qa-lead-responsibilities-and-video-game-testers-role)

[Agile](https://www.wrike.com/project-management-guide/faq/what-is-agile-methodology-in-project-management/)

[Waterfall](https://business.adobe.com/blog/basics/waterfall#:~:text=The%20Waterfall%20methodology%20%E2%80%94%20also%20known,before%20the%20next%20phase%20begins.)

