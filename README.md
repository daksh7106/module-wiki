# Final Exam Handout

Students are invited to contribute to [the wiki](https://github.com/MQ-COMP1050/module-wiki/wiki) in this repo. It contains a markdown file for both the practice exam and the final exam.

* We will print the first 2 pages as the official A4 double-sided exam handout.
* The handout will be distributed at the respective exam.
* We will use the version a day before the respective exam.
* You *cannot* print them out yourself to take to the exam. You can only bring a pen or pencil, and of course, your photo ID.
* If these pages are empty we will hand out empty pages.

Of course, the normal rules for editing public documents at a university apply. We reserve the right to edit the document if it contains offensive or unsuitable content.


Go to [the wiki](https://github.com/MQ-COMP1050/module-wiki/wiki)!

# COMP1050 Week 2: Software Development Life Cycle (SDLC) and Software Processes for Project Management

## What is SDLC (Software Development Life Cycle)?

The Software Development Life Cycle (SDLC) is a structured and methodical process that software teams use to plan, build, test, and maintain software systems. It defines a clear set of stages and activities that must be followed to ensure a software product is delivered efficiently, within budget, and to a high standard of quality. SDLC also helps manage collaboration across team members and stakeholders, reduces uncertainty, and allows for better control over risks, timelines, and resource allocation.

## Goals of SDLC

- **Deliver high-quality software**  
  The software should meet user expectations and business goals. It must be reliable, free of major bugs, user-friendly, secure, and maintainable. Achieving this goal requires clear requirements, proper planning, thorough testing, and consistent quality checks throughout the development process.

- **Minimize development costs**  
  Cost savings are achieved by preventing mistakes early, avoiding unnecessary features, using efficient tools, and clearly defining scope. Proper documentation and risk management also reduce the need for rework and long-term maintenance costs.

- **Reduce time-to-market**  
  SDLC enables a faster delivery of working software by streamlining the process into clearly defined stages. Rapid releases help businesses respond to customer demands and stay ahead of competitors, especially in fast-paced industries.

- **Provide a clear development structure**  
  SDLC defines roles, responsibilities, timelines, and deliverables for each phase. This reduces confusion, improves accountability, and ensures that everyone involved is aligned with the project goals. It also helps manage dependencies and identify risks early.

## Phases of the SDLC (Seven Key Stages)

### 1. Planning
In this phase, the project’s purpose is defined. Teams determine what the software must achieve, who the users are, what resources are needed, and what risks are involved. This includes scheduling, budgeting, setting milestones, and identifying success metrics. Stakeholder input is essential to ensure the solution aligns with business needs.

### 2. Feasibility and Requirements Analysis
This stage focuses on understanding the needs of the client and end users. Requirements are gathered through interviews, surveys, and workshops. The requirements are classified into:
- Functional requirements (what the system should do)
- Non-functional requirements (how the system should behave)

A feasibility study assesses whether the project can be done within technical, financial, and operational constraints.

### 3. Design and Prototyping
Once requirements are clear, the system design is created. This includes user interface layouts, system architecture diagrams, data structures, and workflows. Designers may use wireframes, flowcharts, or UML diagrams. Prototypes are built to test ideas early and gather feedback before full development begins.

### 4. Development (Implementation)
During this phase, programmers write the actual code based on the design documents. The team uses version control systems (such as Git), follows coding standards, and often works in teams to build modules or features. The output of this phase is a working software application.

### 5. Testing
Testing ensures the software functions as expected. This phase includes several types of testing:
- Unit testing: Testing individual components
- Integration testing: Ensuring components work together
- System testing: Validating the entire system
- User Acceptance Testing (UAT): Checking if it meets client expectations

Testing helps detect bugs, security flaws, and performance issues before deployment.

### 6. Implementation and Integration
In this stage, the software is deployed to a live environment. This might involve installation on company servers or releasing it on the internet or app stores. Documentation and training may also be provided. It may also include integrating the system with existing hardware or software.

### 7. Operations and Maintenance
After deployment, the software must be monitored and maintained. This includes fixing bugs, applying updates, improving performance, and ensuring compatibility with new systems. Maintenance is an ongoing process and can last for years after the initial release.

## SDLC Models Explained

### Waterfall Model
This model progresses through each SDLC phase in a fixed order. Each phase must be completed before the next one begins. It is easy to manage and works well when requirements are clear and stable. However, it does not handle changes well once development begins.

### Prototyping Models
Used when requirements are uncertain. A basic version of the product (prototype) is created and shown to stakeholders for feedback.

- Throwaway prototyping: The prototype is discarded after gathering feedback.
- Evolutionary prototyping: The prototype is continuously improved and becomes part of the final system.

### Iterative Model
The software is developed in small parts (iterations). Each iteration builds a small section of the system and incorporates feedback. This allows early detection of issues and gradual improvement over time.

### Spiral Model
Combines aspects of the Waterfall and Iterative models, with a strong focus on risk analysis. The project passes through repeated spirals, where each loop involves planning, risk evaluation, development, and testing. It is suitable for large and complex projects with high risk.

### V-Model (Verification and Validation Model)
This model links each development stage with a corresponding testing stage. For example, design is paired with integration testing. This ensures that quality is built into every phase and emphasizes rigorous verification and validation.

### Rapid Application Development (RAD)
Focuses on fast delivery through the use of component-based development, iterative prototyping, and minimal planning. It relies heavily on user feedback and suits projects with tight deadlines or changing requirements.

## Agile Methodology

Agile is a flexible, collaborative approach to software development. It emphasizes iterative development, continuous feedback, and adaptability to change.

### Agile Manifesto – Core Values

- **Individuals and interactions over processes and tools**  
  People are more important than tools. Effective communication among team members leads to better outcomes than relying solely on rigid procedures.

- **Working software over comprehensive documentation**  
  The primary goal is to deliver functional software. While documentation is important, it should not delay or obstruct working code.

- **Customer collaboration over contract negotiation**  
  Active and ongoing collaboration with customers is more valuable than simply following contract terms. This ensures the software meets actual needs.

- **Responding to change over following a plan**  
  Plans are important, but Agile teams are encouraged to adapt as situations change, allowing for improvements throughout the development cycle.

### Selected Agile Principles

- Deliver working software frequently, from a few weeks to a few months, with a preference for shorter timescales.
- Welcome changing requirements, even late in development.
- Business stakeholders and developers must work together daily.
- Build projects around motivated individuals and trust them to get the job done.
- Face-to-face conversation is the most effective method of communication.
- Simplicity—the art of maximizing the amount of work not done—is essential.

### Agile Frameworks and Practices

#### Scrum
Scrum divides work into short cycles called sprints (usually 1–4 weeks). The team includes:
- Product Owner: Defines and prioritizes work
- Scrum Master: Facilitates progress and removes obstacles
- Development Team: Builds the product

Daily stand-ups, sprint planning, reviews, and retrospectives are key practices.

#### Kanban
Kanban uses a visual board with columns like "To Do," "In Progress," and "Done." Work-in-progress limits are used to ensure focus and prevent overload. Unlike Scrum, it allows for continuous delivery without fixed sprints.

#### Other Agile Practices

- Pair Programming: Two developers work together at one workstation, improving quality and collaboration.
- Test-Driven Development (TDD): Developers write tests before writing the actual code to ensure correctness.
- Continuous Integration/Deployment (CI/CD): Code is frequently integrated and automatically tested and deployed.
- Refactoring: Code is improved (cleaned up) without changing its behavior, making it easier to maintain.

## GitHub and Version Control

### What is GitHub?

GitHub is a platform for storing, managing, and collaborating on code. It uses Git, a distributed version control system, which allows developers to track changes, work on branches, and merge updates without overwriting each other’s work.

### Repositories

A repository is a container for a project, containing source code, documentation, and version history. Public repositories are open to all, while private repositories require permission to access.

### Version Control Systems

- Centralized version control (e.g., SVN) stores all versions in a central server.
- Distributed version control (e.g., Git) gives each developer a full copy of the project history, allowing offline work and easier branching.

## Project Management Tools

### Project Boards

Project boards are visual tools that track the progress of tasks. Tasks are displayed in columns like “To Do,” “In Progress,” and “Done.” These boards help teams quickly see the status of the project, identify bottlenecks, and ensure steady progress.

### Markdown and README.md Files

#### README.md
This file introduces a project to other developers. It typically includes the project’s purpose, how to install and run it, how to contribute, and any licensing information. Written in Markdown, it is easy to read and format.

#### Markdown Uses
Markdown is a lightweight markup language used for writing clean, formatted documents. It is commonly used in documentation, websites, and developer notes. It allows developers to write text that is readable in plain form and also nicely rendered on platforms like GitHub.

# COMP1050 Week 3: Requirements and Issue Tracking

## 1. Requirements Gathering and Specification

### Definition

Requirements are formal, structured descriptions of what a software system must do or how it must behave. These form the foundation for designing, implementing, and testing software systems. Poor or unclear requirements can lead to miscommunication, delays, cost overruns, and ultimately, project failure.

### Why gathering requirements is essential

- It ensures all stakeholders (clients, users, developers, testers) have a shared understanding of the system's purpose.
- It helps identify what features must be built and how the software should perform.
- It allows the team to estimate time, cost, and resources accurately.

### Common issues in requirements gathering

- Conflicting priorities: Different stakeholders may have opposing expectations.
- Ambiguity: Requirements may be written in vague language that can be interpreted in different ways.
- Misunderstanding: Developers may misinterpret the client’s intent, especially if requirements lack clarity or context.
- Omission: Important features or rules may be forgotten or assumed without explicit confirmation.

## 2. Functional vs Non-Functional Requirements

### Functional Requirements

These describe specific actions or behaviors that the system must support. They define what the system should do.

**Examples:**

- A user must be able to log in.
- The system must allow password changes.
- When a product is added to the cart, it must appear on the checkout page.

### Non-Functional Requirements

These describe how the system performs or operates, rather than what it does. They are related to quality, constraints, and usability.

**Examples:**

- The page must load within 2 seconds.
- The system should support 500 concurrent users.
- Passwords must be at least 8 characters with one uppercase letter and one digit.

**Key distinction:**  
Functional requirements describe actions; non-functional requirements describe conditions and qualities.

**Good non-functional requirements** are quantifiable and specific to enable testing and validation.

## 3. Acceptance Criteria

### Definition

Acceptance criteria are specific, testable conditions that must be satisfied for a user story or requirement to be considered complete.

### Purpose

- They clarify what is expected so developers know when their work is "done."
- They provide measurable conditions for quality assurance teams to verify functionality.
- They prevent misunderstandings by ensuring that stakeholders and developers are aligned.

### Format (Given-When-Then pattern):

- **Given** a certain situation (starting context)
- **When** an action is taken
- **Then** the expected outcome occurs

**Example:**

Given a registered user on the login page,  
When they enter valid credentials and click "Login",  
Then they should be redirected to the dashboard.

### Best practices:

- Use clear, plain language.
- Ensure each condition is testable.
- Cover typical scenarios and edge cases.
- Confirm stakeholder agreement on the criteria.

## 4. Use Cases and Use Case Descriptions

### Use Case Definition

A use case explains how a user interacts with a system to achieve a specific goal. It helps to define the functional requirements in a structured, user-focused format.

### Key Elements of a Use Case:

- Actor: The user or external system interacting with the software.
- Primary Actor: The main user responsible for initiating the use case.
- Preconditions: Conditions that must be true before the use case can start.
- Trigger: The event that starts the interaction.
- Main Success Scenario: A step-by-step guide for how the use case proceeds under normal conditions.
- Alternative Flow (Exception Scenarios): What happens if something goes wrong or a different path is taken.

### Example: Registering as a New User

- Actor: Visitor
- Primary Actor: Visitor
- Preconditions: Visitor is on the sign-up page
- Trigger: Visitor clicks "Sign Up"
- Main Success Scenario: The user enters email and password, submits the form, and receives a confirmation email.
- Alternative Flow: If the user enters a weak password, the system displays a prompt to improve it.

## 5. User Stories in Agile

### Definition

A user story is a short, simple description of a feature or requirement written from the perspective of the end user. It focuses on value rather than technical implementation.

### Standard format:

As a **[role]**,  
I want to **[do something]**,  
So that **[I receive some benefit]**.

### Example:

As a customer,  
I want to view my order history,  
So that I can keep track of my purchases.

### Purpose of user stories:

- Clarify the goals and needs of users.
- Help prioritize development based on value.
- Provide a starting point for discussion and collaboration between developers, testers, and stakeholders.

### Characteristics of a good user story (INVEST model):

- Independent: Can be developed separately.
- Negotiable: Can be discussed and modified.
- Valuable: Delivers value to the user.
- Estimable: Can be reasonably estimated for effort.
- Small: Sized to be completed in a sprint.
- Testable: Has clear acceptance criteria.

## 6. Acceptance Criteria for User Stories

### Purpose

The acceptance criteria for user stories define what needs to be true for a story to be marked as complete. They serve as both requirements and test cases.

### Example for the user story: “As a registered user, I want to change my password.”

- The user must be able to log in using valid credentials.
- Once logged in, the user should have access to a “Change Password” page.
- The old password must be validated before updating.
- The new password must meet security requirements (e.g., length, characters).
- A confirmation message should be shown after successful change.

Good acceptance criteria are unambiguous, realistic, and measurable.

## 7. The Definition of Done (DoD)

### Definition

The Definition of Done is a checklist used to confirm that a feature or task is truly complete. It ensures consistency and quality across the team.

### Typical items in a Definition of Done:

- All acceptance criteria are fulfilled.
- Code is written, reviewed, and approved.
- Automated tests (unit/integration) pass.
- Manual tests are completed.
- The product owner accepts the feature.
- Documentation is updated.
- Code is merged into the main branch and deployed (if applicable).

The DoD helps avoid misunderstandings about task completion and maintains delivery standards.

## 8. Epics and Themes in Agile

### Epic

An epic is a large user story that is too big to complete in a single iteration or sprint. It is broken down into smaller stories to be delivered over time.

**Example:**  
"Implement user authentication" could be an epic that includes user registration, login, password reset, and email verification stories.

### Theme

A theme is a broader category that groups multiple epics or related user stories together under a common goal or feature area.

**Example:**  
A "User Management" theme might include the authentication epic as well as profile management and user role settings.

### Task

A task is a small, actionable unit of work derived from a user story. Tasks are usually completed within a day or two and are assigned to team members.

**Structure:**  
**Theme → Epic → User Story → Tasks**

This hierarchy helps organize large development efforts and align them with business goals.

## 9. GitHub Project Boards and Issue Tracking

### User Stories as GitHub Issues

In GitHub, each user story or requirement can be created as an “Issue.” These issues are then tracked as part of the development workflow.

### Columns (Kanban-style):

- To Do: Work that has not yet started.
- In Progress: Work that is currently being developed.
- Done: Completed and reviewed work.

### Additional Features:

- Labels: Identify the type of issue (e.g., bug, enhancement, feature).
- Assignees: Show who is responsible for the issue.
- Milestones: Group related issues by goals or delivery dates.
- Linked Pull Requests: Connect code changes with specific issues.

### Benefits of using GitHub for project tracking:

- Provides real-time transparency on team progress.
- Ensures accountability through clear assignment of tasks.
- Facilitates efficient communication and collaboration.
- Helps track and close issues systematically.

# COMP1050 – Week 4: Version Control and Debugging (Expanded Notes)

## Part A: Version Control Systems (VCS)

### What is Version Control?

Version control is a system that records changes to files over time, so that specific versions can be recalled later. It's essential in software development to allow:

- Collaboration between team members
- Safe experimentation (with branching)
- The ability to undo mistakes
- Transparency into the history of changes

### Types of Version Control

#### 1. Centralised Version Control (CVCS)

- All versions are stored on a central server.
- Developers “pull” from and “commit” to this server.
- If the server goes down or is inaccessible, no work can be done.
- **Example:** Subversion (SVN)

#### 2. Distributed Version Control (DVCS)

- Every user has a full copy of the repository (with history).
- Changes can be committed locally.
- Synchronisation with others is done using push/pull.
- **Example:** Git (used with GitHub, GitLab, Bitbucket)

### Why Use Git (DVCS)?

- Works offline: commits and branching are local.
- Efficient: only stores changes (not full copies).
- Supports branches and merging for parallel development.
- Enables granular control over commits.
- Encourages experimentation with minimal risk via branches.

### The Git Workflow – Areas and Concepts

| Component         | Description                                 |
|------------------|---------------------------------------------|
| Working Directory| Where you actively edit files               |
| Staging Area     | A temporary area where changes are added before being committed |
| Repository       | Where all committed versions and history are stored |

To move files from one stage to the next:
# git add <file>     # from working directory to staging
# git commit -m ""   # from staging to repository## What is a Commit?

A commit is a record of a change, containing:

- A unique ID hash (e.g., `a3f5e2b`)
- Author info (name, email)
- Parent commit(s)
- The actual changes made (not entire files)
- A commit message (summary of change)

Think of a commit as a checkpoint or snapshot.

## Key Git Commands Explained

| Command               | Function                                   |
|-----------------------|--------------------------------------------|
| `git init`            | Initialize a new repository                |
| `git clone <url>`     | Download a remote repo with history        |
| `git status`          | Show which files are modified/staged       |
| `git add <file>`      | Add file(s) to staging area                |
| `git commit -m "msg"` | Commit changes with a message              |
| `git pull`            | Fetch and merge updates from remote repo   |
| `git push`            | Push your commits to the remote repo       |
| `git log`             | View commit history                        |
| `git diff`            | Show differences between versions          |

## Cloning vs Downloading from GitHub

| Feature              | Clone        | Download         |
|----------------------|--------------|------------------|
| Includes .git folder |  Yes         |  No              |
| Full history         |  Yes         |  No history      |
| Can push/pull        |  Yes         |  No              |
| Connected to GitHub  |  Yes         |  No              |

## Branching in Git

A branch is a parallel version of the repository. It's used to:

- Add new features
- Fix bugs
- Run experiments without affecting the main code

## Merging and Merge Conflicts

- **Merge**: Combines changes from one branch into another.
- **Merge Conflict**: Happens when two branches edit the same line(s) of a file.

### Resolving Conflicts

- Git marks the conflict in the file.
- The developer must manually resolve it and commit again.

## GitHub Issue Tracking

GitHub allows structured issue tracking:

- **Title and description**: Outline what needs fixing.
- **Assignees**: Team members responsible.
- **Labels**: Categorise the issue (bug, enhancement, documentation, etc.).
- **Milestones**: Connect issues to broader goals.
- **Linked branches or pull requests**: Track work connected to issues.

## Advantages of Git

- Full local history of your project
- Multiple independent lines of development (branches)
- Can undo mistakes by reverting to earlier commits
- Easy collaboration through GitHub
- Clean integration with testing and CI/CD tools

## GitHub Desktop and Visual Tools

While Git is used from the command line, tools like:

- GitHub Desktop
- GitKraken
- VS Code Git integration

...offer graphical interfaces for:

- Commits
- Branching
- Merging
- Pull request management

## Part B: Debugging in Processing (Continued)

### Why is Debugging Important?

Debugging helps identify and fix errors in your code. It’s essential for:

- Ensuring the program behaves as expected
- Understanding logic flaws
- Improving reliability

## Understand Errors

- **Syntax Errors**:  
  Occur when there is a mistake in the structure of the code (e.g., missing semicolon or incorrect brackets).  
  **Fix**: Correct the code structure based on error messages.

- **Logic Errors**:  
  The code runs but doesn’t produce the expected results.  
  **Fix**: Adjust the conditions, loops, or calculation logic.

- **Runtime Errors**:  
  These occur while the program is running, often due to:
  - Division by zero
  - Accessing a null object
  - Array index out-of-bounds  
  **Fix**: Add checks and error handling (e.g., `if (array.length > index)`).

# COMP1050 – Week 5: Code Reviews and Software Testing

## Intended Learning Outcomes

By the end of this week, you should be able to:

- Describe the characteristics of good code.
- Understand the importance and types of code reviews.
- Recognise the role of style, semantics, and structure in code readability and correctness.
- Understand different levels and types of software testing.
- Differentiate between white-box and black-box testing.
- Explain how acceptance tests connect user stories to validation.
- Apply testing techniques in Processing using well-structured test formats.

## Part 1: Code Reviews

### What is a Code Review?

A code review is the practice of evaluating someone’s code before it is merged or released. It serves as both a quality assurance process and a knowledge-sharing activity within a team.

### Why Review Code?

- To ensure correctness: Validate that the code works as intended and meets requirements.
- Knowledge sharing: Helps all team members understand each part of the system.
- Improve code quality: Reviewers often spot bugs or suggest improvements.
- Enforce coding standards: Consistency in naming, structure, and formatting.
- Promote collaboration: Encourages open communication and constructive feedback.
- Catch bugs early: Reduces the cost and time of fixing problems later.

### Types of Code Reviews

#### 1. Peer Review

- One developer reviews another's code.
- Steps:
  - The author marks the code as ready for review.
  - A teammate is assigned to review it.
  - The reviewer provides written feedback or asks questions.
  - The author makes changes and resubmits the code.
  - The reviewer approves the final version.
- Supported by: GitHub Pull Requests

#### 2. Code Walkthrough

- The author presents the code to the team.
- Steps:
  - Author gives a brief overview of the changes.
  - Code is reviewed line by line in a meeting.
  - Team asks questions, suggests changes.
  - The author revises the code based on feedback.
- Highly collaborative, good for shared understanding.

#### 3. Pair Programming

- Two people write code together at the same time.
  - Driver: Writes code.
  - Navigator: Reviews code in real-time, suggests improvements.
- Roles are often switched every 20–30 minutes.
- Popular in Agile and Extreme Programming (XP).
- Encourages immediate feedback and fewer bugs.

### Resources to Support Reviews

- Checklists: Ensure consistency across multiple areas like documentation, naming, and logic.
- Test Results: Include output from automated or manual test runs to verify correctness.
- Automated Code Analysis: Tools like PMD or SonarLint check for style violations and common bugs.
- Metrics: Measure things like cyclomatic complexity or code duplication to identify weak areas.

## Part 2: Code Quality – Style and Semantics

### Code Style: Why It Matters

Poorly styled code is hard to read and maintain—even by the original author.

Good style improves:

- Readability: Other people can understand your logic.
- Maintainability: Easier to fix and extend.
- Debuggability: Bugs stand out more clearly.
- Collaboration: Easier for teams to work together.

### Code Style Guidelines

#### 1. Naming Conventions

- Use descriptive names (not a, b2, x1).
- Follow Java/Processing conventions:
  - Variables/methods: lowerCamelCase
  - Classes: UpperCamelCase
  - Constants: ALL_CAPS_WITH_UNDERSCORES
  - Booleans: Use prefixes like is, has, can (e.g., isAlive, hasBorder)

#### 2. Constants

- Declare important fixed values as static final, not magic numbers.

#### 3. Indentation and Braces

- Always use proper indentation and braces—even for single-line statements.

#### 4. Comments

- Write comments for humans.
- Use single-line comments for short notes.
- Use multi-line comments for longer explanations or file headers.
- Update comments when code changes.
- Do not use comments to justify poor code naming or structure.

### Semantics: What Does the Code Really Mean?

Semantics refers to the meaning and intention behind each line of code.

Good semantic practices:

- Every line of code has a purpose.
- Use constructs appropriately (e.g., avoid unnecessary loops or unused variables).
- Eliminate “dead code” or logic that never executes.
- Avoid redundant checks.

## Part 3: Software Testing

### What is Software Testing?

Software testing is the process of checking if a program behaves as expected under various conditions. It helps identify bugs, usability problems, and requirement mismatches.

### IEEE Definition

“The process of analyzing a software item to detect the differences between existing and required conditions and to evaluate the features of the software item.”

### Goals of Testing

- Validate that software works correctly
- Confirm that software fails safely (when needed)
- Reduce the risk of failures
- Lower long-term development costs
- Prevent regressions (bugs that reappear)

## The V-Model of Testing

The V-Model shows the relationship between development stages and testing levels. Every development activity has a corresponding testing activity.

| Development Phase | Corresponding Test       |
|-------------------|--------------------------|
| Requirements      | Acceptance Testing       |
| System Design     | System Testing           |
| Module Design     | Integration Testing      |
| Code Implementation | Unit Testing           |

## Levels of Testing

### 1. Unit Testing

- Tests individual functions or methods in isolation.
- Often automated.
- Fastest and lowest-level form of testing.

### 2. Integration Testing

- Tests combinations of modules to check if they work together properly.

### 3. System Testing

- Validates the entire software system (functional + non-functional requirements).

### 4. Acceptance Testing

- Confirms the system meets the user’s expectations and business goals.
- Derived directly from user stories and acceptance criteria.

## Testing Terminology

- **Test Vector**: Input values
- **Test Case**: A structured plan including input, expected output, and steps
- **Test Suite**: Collection of related test cases
- **Test Environment**: Software, hardware, or other setup used during testing
- **Test Result**: Actual output (compared with expected)

## Part 4: Acceptance Testing in Agile

### What are Acceptance Tests?

Acceptance tests confirm that the software meets the user story and its acceptance criteria.

They focus on the system’s observable behavior, not how it was implemented.

### Format:

- Given some context
- When the user performs an action
- Then the system should behave in a specific way

### Example from Processing Projects

**User Story:**  
As a user, I want a radiating pineapple when I press play, so that I can enjoy a fun animation.

**Test Objective:**  
Check if the pineapple appears correctly.

**Test Steps:**  
Invite 5 users and ask them to rate the resemblance.

**Expected Outcome:**  
At least 3 users rate it 6/10 or higher.

## Black Box vs White Box Testing

| Feature              | Black Box Testing                  | White Box Testing              |
|----------------------|-------------------------------------|--------------------------------|
| Code visibility      | No knowledge of code                | Full access to source code     |
| Focus                | Inputs and expected outputs         | Internal logic and flow        |
| Based on             | User requirements                   | Code implementation            |
| Best for             | Acceptance/system-level tests       | Unit/integration-level tests   |

## Grey-box Testing

Grey-box testing combines both. The tester has partial knowledge of the system and uses both requirement-based and code-based testing approaches.

## Testing Strategy Summary

- Test both expected paths (“happy paths”) and edge cases.
- Choose test values thoughtfully:
  - Try small, large, zero, and negative numbers
  - Try invalid inputs (e.g., empty strings, null values)
- Document each test with:
  - Test ID
  - Input
  - Expected output
  - Actual output
  - Pass/Fail status

# COMP1050 – Week 6: Unit Testing and Regression Testing

## 1. What is Unit Testing?

### 1.1 Definition

Unit testing involves isolating and testing a single unit of code, typically a function, method, or class. The main aim is to ensure that each piece of the program performs as intended, under a variety of inputs.

In contrast to system testing, which examines the software as a whole, unit tests zoom in on small, modular components, checking for correctness before integration.

### 1.2 Purpose and Advantages

- **Immediate feedback**: If something is broken, it’s discovered early during development.
- **Faster debugging**: Since each unit is tested independently, it's easier to identify the exact source of a bug.
- **Supports refactoring**: Confidently modify existing code without breaking functionality.
- **Improves modularity**: Encourages developers to write small, testable functions.
- **Enhances reliability**: Tests confirm that a method works across a range of input conditions.

## 2. Assertions in Unit Testing

### 2.1 What is an Assertion?

An assertion is a programming construct used to validate whether a specific condition is true. If the assertion fails, the program typically halts and reports the failure.

It allows developers to express expectations directly in the code, such as “I expect this function to return 42 when given the value 7.”

### 2.2 Purpose

- Express assumptions clearly in code.
- Fail early and visibly when expectations aren't met.
- Automate the testing process.
- Build confidence in logic correctness.

### 2.3 When to Use Assertions

- Testing basic arithmetic results, string outputs, boolean flags, or conditionals.
- Validating object state (e.g., verifying that a value is correctly updated).
- Confirming that exceptions are thrown when expected (in more advanced frameworks).

**Note:** Avoid using assertions for runtime error handling—their purpose is to confirm correctness, not handle user input errors.

## 3. Documenting Unit Tests

### 3.1 Why Document Test Cases?

Writing structured documentation for test cases ensures:

- **Consistency**: Everyone on the team understands how testing is done.
- **Reproducibility**: You can rerun tests the same way at any point.
- **Traceability**: Links tests to specific requirements or functions.
- **Quality assurance**: Instructors, clients, or reviewers can verify that your code has been thoroughly tested.

### 3.2 Standard Test Case Template

| Field             | Explanation                                              |
|------------------|----------------------------------------------------------|
| Test ID          | A unique identifier (e.g., UT02_AdditionEdgeCase)        |
| Test Objective   | A short sentence describing the intent of the test       |
| Test Environment | Details of the context (e.g., Processing version, OS)    |
| Test Steps       | Step-by-step actions to carry out the test               |
| Expected Output  | What the output should be if the code is working correctly |
| Actual Output    | The result observed when the test was run                |
| Pass/Fail Status | Mark as "Pass" if output matches expectation, else "Fail"|

### 3.3 Example

| Field            | Value                                 |
|------------------|----------------------------------------|
| Test ID          | UT03_SubtractionNegativeInput          |
| Objective        | Ensure subtracting a positive number from a smaller number results in a negative output |
| Environment      | Processing 4.3 on Windows 11           |
| Steps            | Call subtract(3, 7)                    |
| Expected Output  | -4                                     |
| Actual Output    | -4                                     |
| Pass/Fail        | Pass                                   |

## 4. Regression Testing

### 4.1 What is Regression Testing?

Regression testing is the process of retesting previously passed test cases after new code changes are made. Its purpose is to verify that new changes have not broken existing functionality.

Even small code updates, like renaming variables or changing conditions, can have unintended consequences. Regression testing helps catch these issues.

### 4.2 Why It Matters

- Maintains trust in the system over time.
- Prevents introducing new bugs in old features.
- Crucial in collaborative projects or long-term codebases where many people contribute.
- Often integrated into CI/CD pipelines to automate frequent testing.

### 4.3 Best Practices

- Keep a library of previous test cases.
- Re-run these after every significant code change.
- Automate where possible.
- Log failures and investigate even if they appear unrelated to the latest changes.

## 5. Boundary Value Testing (BVT)

### 5.1 What is BVT?

Boundary Value Testing focuses on values at the edge of valid input ranges. Since most bugs occur at these edges, this type of testing is crucial.

**Example:**  
If a valid age range is 0–120, then test cases should include:

- Minimum valid: 0
- Maximum valid: 120
- Below minimum: -1
- Above maximum: 121

### 5.2 Common Errors Detected

- Off-by-one errors (`<=` vs `<`)
- Array out-of-bounds issues
- Overflow or underflow
- Incorrect input validation

### 5.3 Example

**Function:** `isValidScore(int score)`  
**Requirement:** Returns true if the score is between 0 and 100 (inclusive)

**Boundary test cases:**

- `isValidScore(0)` → true
- `isValidScore(100)` → true
- `isValidScore(-1)` → false
- `isValidScore(101)` → false

## 6. Testing in Processing

### 6.1 Manual Testing via Helper Functions

Processing does not have a built-in test framework, but you can simulate testing by writing test functions and printing results.

**Steps:**

- Write small test functions for each feature.
- Call them inside `setup()` for a one-time test run.
- Print results as pass/fail indicators.
- Use boolean logic to test return values and expected outcomes.

### 6.2 Visual and User-Based Testing

If your program includes graphics, interaction, or animations, visual testing becomes more relevant:

- Use screenshots or frame captures to compare expected visuals.
- Ask test users to provide qualitative feedback on UI, animation smoothness, and responsiveness.
- Document these results formally with acceptance test formats.

# COMP1050 – Week 7: SDLC Testing & Project Management

## 1. Testing in the SDLC

Testing is not just about catching bugs at the end. It plays a **crucial role across all phases of development**.

### 1.1 When is Testing Done?

| Phase              | Testing Involvement Example                                           |
|--------------------|-----------------------------------------------------------------------|
| Requirements       | Verify requirements are testable (e.g., “system shall respond in <2s”)|
| Design             | Review system structure for testability                               |
| Implementation     | Unit testing of individual functions                                  |
| Integration        | Combine components and test interfaces                                |
| System Testing     | Full system test against specifications                               |
| Acceptance Testing | End-user validation before delivery                                   |
| Maintenance        | Regression tests to confirm updates don’t break existing code         |

### 1.2 Types of Testing

| Type                   | Purpose                                                |
|------------------------|--------------------------------------------------------|
| **Unit Testing**       | Test individual functions/methods                      |
| **Integration Testing**| Ensure modules/components work together                |
| **System Testing**     | Validate entire application meets requirements         |
| **Acceptance Testing** | Confirm with stakeholders that system meets expectations |
| **Regression Testing** | Re-test after changes to ensure no new bugs            |

## 2. Role of Testing in Agile and Waterfall

### 2.1 Waterfall

- Testing phase is separate and occurs after implementation.
- Issues may be harder to fix due to late discovery.

### 2.2 Agile

- Testing is integrated in each sprint.
- Tests are written *before* or *during* development (TDD).
- Constant feedback allows for earlier fixes and improved quality.

## 3. Project Management in Software Development

Project Management is about planning, executing, and tracking work to deliver software **on time, within scope, and budget**.

### 3.1 Why it Matters

- Coordinates tasks across teams
- Ensures accountability and responsibility
- Manages resources and deadlines
- Aligns development with business goals

## 4. Work Breakdown Structure (WBS)

### 4.1 What is WBS?

A WBS is a **hierarchical decomposition** of the project into smaller, manageable components.

### 4.2 Example WBS
Project: Build a Web App
├── 1. Requirements Gathering
│ ├── 1.1 Interview Stakeholders
│ └── 1.2 Document Requirements
├── 2. Design
│ ├── 2.1 UI Mockups
│ └── 2.2 Architecture Diagram
├── 3. Development
│ ├── 3.1 Frontend
│ ├── 3.2 Backend
│ └── 3.3 Database
└── 4. Testing
├── 4.1 Unit Testing
└── 4.2 System Testing


### 4.3 Benefits of WBS

- Improves clarity of scope
- Easier task assignment and tracking
- Helps estimate resources, timelines, and costs

## 5. Gantt Charts

### 5.1 What is a Gantt Chart?

A **Gantt Chart** is a type of bar chart that visually represents a project schedule over time.

### 5.2 Features

- **Tasks**: Each row represents a task.
- **Timeline**: Horizontal axis shows time.
- **Bars**: Length and position of bars represent start and end dates.
- **Dependencies**: Arrows can indicate task dependencies.

### 5.3 Gantt Chart Example

| Task                 | Start Date | End Date   | Duration | Dependencies  |
|----------------------|------------|------------|----------|----------------|
| Requirements         | Day 1      | Day 3      | 3 days   | -              |
| Design               | Day 4      | Day 6      | 3 days   | Requirements   |
| Development          | Day 7      | Day 14     | 8 days   | Design         |
| Testing              | Day 15     | Day 18     | 4 days   | Development    |
| Deployment           | Day 19     | Day 20     | 2 days   | Testing        |

## 6. Work Tracking Tools

### 6.1 GitHub Issues

GitHub provides a structured way to **track bugs, features, and tasks**:

- **Title**: Short summary of the issue
- **Description**: Details of the issue/feature
- **Assignees**: Who is responsible
- **Labels**: Type (e.g., bug, enhancement)
- **Milestones**: Grouping by delivery goal

> 🔄 GitHub issues can be linked to branches and pull requests for full traceability.

# COMP1050 – Week 8: Software Architecture & Design

## 1. Software Architecture vs Design

| Term         | Description |
|--------------|-------------|
| **Software Architecture** | The **high-level structure** of a system. It defines how components interact and how the system meets non-functional requirements (e.g., performance, scalability). |
| **Software Design** | The **detailed internal structure** of each component. It focuses on how the functionality is implemented. |

> **Analogy**:  
> - Architecture = blueprint of a house  
> - Design = placement of furniture, electrical wiring, etc.

---

## 2. Importance of Architecture

A good software architecture helps ensure:

- **System scalability**: Easy to grow with user demand.
- **Maintainability**: Easy to modify, fix bugs, or add features.
- **Performance**: Efficient handling of tasks and resources.
- **Reliability**: Less prone to crashes or inconsistent states.
- **Security**: Safeguards for protecting data and access.

## 3. Architectural Views (The 4+1 View Model)

This model breaks down software architecture into **five complementary views**:

| View Type       | Focus Area | Audience |
|------------------|------------|----------|
| **Logical View**     | Functionality (what the system does) | Developers |
| **Process View**     | Runtime behavior and concurrency | System integrators |
| **Development View** | Code structure and modularity | Developers |
| **Physical View**    | Deployment across hardware nodes | System engineers |
| **Use Case View**    | How users interact with the system | Stakeholders |

> These views ensure that **different stakeholders** (e.g., developers, clients, testers) understand the system from their relevant perspectives.

## 4. Architecture Patterns

### 4.1 Layered Architecture

- **Structure**: Components are organized into layers (e.g., Presentation, Business Logic, Data).
- **Each layer** has a specific role and communicates only with the layer directly beneath it.
- **Use case**: Web apps, enterprise software.

### 4.2 Client-Server Architecture

- **Server**: Hosts data and logic.
- **Client**: Requests services (e.g., browser).
- Scales well for distributed systems.

> Examples: Web browsers & web servers, multiplayer games.

### 4.3 Microservices Architecture

- System is split into **independent services** that communicate via APIs.
- Each microservice is small, focused, and deployable separately.
- Easier to scale and develop in parallel.
- Requires robust DevOps support.

### 4.4 Event-Driven Architecture

- System reacts to **events** or **messages** (e.g., user actions, data updates).
- Promotes **loose coupling** between components.
- Popular in real-time systems and streaming platforms.

## 5. Design Principles

### 5.1 Modularity

Break your program into **independent components or functions**. This improves:

- Readability
- Reusability
- Testability

### 5.2 Abstraction

- Hide implementation details.
- Use **interfaces or abstract classes** to separate what a component does from how it does it.

### 5.3 Encapsulation

- Protect internal object states by making variables **private** and providing **getters/setters**.
- Prevent external code from making unintended changes.

### 5.4 Separation of Concerns

Each component/module/class should handle **only one responsibility**.

> Bad: A class that handles both database connection and user interface.  
> Good: Separate `DatabaseManager` and `UIHandler` classes.

### 5.5 Loose Coupling & High Cohesion

| Term | Meaning |
|------|---------|
| **Loose Coupling** | Components are independent; changing one doesn't affect others much. |
| **High Cohesion** | A component only does one thing well and related tasks are grouped together. |

## 6. Design Patterns

Design patterns are **reusable solutions to common problems** in software design.

### 6.1 Singleton Pattern

- Ensures only **one instance** of a class exists.
- Useful for configurations, logging systems, or device drivers.

### 6.2 Factory Pattern

- Creates objects without exposing the instantiation logic.
- Lets you create different types of objects based on input or context.

### 6.3 Observer Pattern

- One object (the subject) notifies all subscribed observers of changes.
- Used in **event handling**, **GUIs**, and **data bindings**.

## 7. UML Diagrams

### 7.1 Class Diagram

Shows the **structure** of a system using:

- Classes
- Attributes
- Methods
- Relationships (e.g., inheritance, composition)

### 7.2 Sequence Diagram

Shows **object interactions over time**, like a timeline of function calls.

# COMP1050 – Week 9: Software Modelling & Quality

## 1. What is Software Modelling?

**Software modelling** is the process of creating abstract representations of a system to better understand and plan its design before implementation.

> Think of modelling as drawing the **blueprint** for your software before building it.

## 2. Why Model Software?

- **Visualize system structure and interactions**
- **Identify problems early**
- **Plan development more effectively**
- **Improve communication among team members**
- **Support documentation and maintenance**

## 3. Types of Software Models

### 3.1 Static Models

Describe **structure** – the “what exists” in the system.

- **Class Diagrams**
- **Object Diagrams**
- **Component Diagrams**

### 3.2 Dynamic Models

Describe **behavior over time** – how the system behaves or responds.

- **Use Case Diagrams**
- **Sequence Diagrams**
- **Activity Diagrams**
- **State Diagrams**

## 4. UML (Unified Modeling Language)

UML is a **standard visual language** used to describe software systems.

### Common UML Diagrams:

| Type              | Purpose |
|-------------------|---------|
| **Use Case Diagram** | Shows user interactions (functionalities) |
| **Class Diagram**     | Shows classes, attributes, and relationships |
| **Sequence Diagram**  | Shows object interactions over time |
| **Activity Diagram**  | Shows flow of logic (like a flowchart) |
| **State Diagram**     | Shows state changes of an object based on events |

### 4.1 Use Case Diagram

- Represents **functional requirements**
- Shows **actors** (users) and **use cases** (features)
- Focuses on **what** the system should do, not how

### 4.2 Class Diagram

- Represents system **structure**
- Contains:
  - **Class name**
  - **Attributes (variables)**
  - **Methods (functions)**
- Shows relationships: 
  - **Association** (uses a)
  - **Inheritance** (is a)
  - **Aggregation** (has a)

### 4.3 Sequence Diagram

- Describes how **objects interact in a specific scenario**
- Focuses on **message flow** between objects over time

### 4.4 Activity Diagram

- Shows the **flow of control** between activities
- Used to model **workflows, algorithms, and logic**

### 4.5 State Diagram

- Models an object’s **lifecycle and transitions**
- Shows states, events, and transitions
## 5. Software Quality

### 5.1 What is Software Quality?

Quality refers to **how well the software meets user expectations**, both functionally and non-functionally.

### 5.2 Quality Factors (ISO/IEC 25010)

| Quality Attribute     | Description |
|------------------------|-------------|
| **Functionality**      | Does it meet specified functions? |
| **Reliability**        | Does it perform consistently under conditions? |
| **Usability**          | Is it easy to use and understand? |
| **Efficiency**         | Does it use system resources wisely? |
| **Maintainability**    | Can it be easily changed or fixed? |
| **Portability**        | Can it run on different environments? |
| **Security**           | Is it protected against threats? |
| **Compatibility**      | Can it work with other systems? |

## 6. Techniques to Improve Software Quality

- **Code Reviews**: Review code with peers to find mistakes early.
- **Testing**: Perform unit, system, and regression testing.
- **Modular Design**: Design software with small, independent components.
- **Consistent Style**: Use standard naming and formatting.
- **Documentation**: Provide clear and concise technical and user documentation.
- **Version Control**: Track changes with Git or similar tools.

## 7. Measuring Quality

### 7.1 Metrics

| Metric Type          | Example |
|----------------------|---------|
| **Size Metrics**      | Lines of Code (LOC), Number of Classes |
| **Complexity Metrics**| Cyclomatic Complexity (number of decision paths) |
| **Defect Metrics**    | Number of bugs found during testing |
| **Performance Metrics** | Response time, memory usage |

# COMP1050 – Week 10: High-Level Software Architecture

## 🔹 What is Software Architecture?

Software architecture is the **blueprint of a software system**. It defines the overall **structure**, the way components interact, and how the system meets both **functional and non-functional requirements**.

It is not about detailed code; it’s about **designing how the system will work as a whole** before implementation begins.

### Key Questions Architecture Answers:

- What are the major components/modules of the system?
- How do these components interact?
- Where are the performance bottlenecks likely to be?
- How can the system be scaled or updated in the future?

## 🔹 Why is Architecture Important?

A well-designed architecture:

- Supports **scalability**, **maintainability**, and **reliability**
- Makes it easier to add or change features
- Reduces risk by identifying issues early
- Improves team communication through shared diagrams and models

## 🔹 High-Level vs Low-Level Design

| Aspect            | High-Level Architecture             | Low-Level Design                        |
|-------------------|--------------------------------------|------------------------------------------|
| Focus             | System structure and interactions   | Class and method-level implementation   |
| Abstraction       | Components, services, modules       | Functions, loops, variables             |
| Audience          | Architects, senior developers       | Developers, testers                     |
| Timing            | Early in SDLC                       | During implementation phase             |

## 🔹 Architectural Styles

Architectural styles (aka patterns) provide **reusable templates** for solving common structural problems in software systems.

### 1. Layered (n-tier) Architecture

- Organizes code into layers with **clear responsibilities**
- Common layers: UI → Business Logic → Data Access

**Pros:** Simple, good separation of concerns  
**Cons:** Slower for performance-critical applications

### 2. Client-Server Architecture

- **Clients** send requests, **servers** respond with data or services
- Examples: Web applications, multiplayer games

**Pros:** Supports remote access and scalability  
**Cons:** Server can be a bottleneck

### 3. Microservices Architecture

- System is split into **independent services** with their own data and logic
- Services communicate via APIs

**Pros:** Easy to scale, develop and deploy independently  
**Cons:** Complex communication and monitoring needed

### 4. Event-Driven Architecture

- Components **react to events or messages**
- Promotes loose coupling and asynchronous operations

**Pros:** Responsive systems, scalable  
**Cons:** Harder to debug and trace behavior

## 🔹 Non-Functional Requirements (NFRs)

These are **quality attributes** the architecture must support:

- **Performance** – How fast it responds
- **Scalability** – Can it handle more users/data?
- **Availability** – How often is it up and working?
- **Security** – How well is data protected?
- **Maintainability** – How easy is it to update/fix?

NFRs often drive **architectural decisions** more than functional ones.

## 🔹 Architecture Diagrams

Architecture diagrams are **visual blueprints** that show components, connections, and deployment.

### Types of Diagrams:

- **Component Diagram**: Shows modules/components and their relationships
- **Deployment Diagram**: Shows physical hardware and how software is distributed
- **Container Diagram (from C4 Model)**: Shows applications and services running inside servers/VMs
- **Sequence Diagrams**: Useful for runtime communication between components

## 🔹 C4 Model (Context, Container, Component, Code)

The **C4 model** provides four levels of software architecture views:

1. **Context Diagram** – Big-picture overview (users, systems)
2. **Container Diagram** – Apps, services, databases inside the system
3. **Component Diagram** – Breaks each container into detailed components
4. **Code Diagram** – Class/module-level (lowest level)

Used together, these provide a complete view from top to bottom.

## 🔹 Architecture Evaluation

### How do you know your architecture is good?

Use **ATAM** – Architecture Trade-off Analysis Method:

- Identify key **quality goals**
- Evaluate how well architecture supports them
- Highlight trade-offs (e.g., performance vs security)

Architecture is always about **trade-offs**. No perfect design exists.

# COMP1050 – Week 11: Traceability & Configuration Management

## 🔹 What is Traceability?

**Traceability** in software engineering is the practice of tracking and documenting the life of a requirement. It means being able to follow a requirement from its origin (e.g., a customer need) through to its implementation in code and validation through testing.

### Think of it like:
A GPS tracker on a requirement — you always know:
- Where it came from
- Where it is implemented
- Where it is tested
- What would break if it changed

##  Types of Traceability

### 1. Forward Traceability

- Tracks the requirement **forward** through the development process.
- Ensures that **every requirement is implemented** and tested.

**Example:**
Requirement R1 → leads to Design D1 → leads to Code Module M1 → leads to Test Case T1

### 2. Backward Traceability

- Tracks **backward** from code or test cases to the original requirement.
- Helps verify that **everything built has a purpose**.

**Example:**
You’re looking at Test T1. Backward traceability helps ensure it's tied to Requirement R1 — not a random or outdated test.

### 3. Bidirectional Traceability

- Combines both forward and backward traceability.
- Ideal for change impact analysis.

**Why it matters:**
If Requirement R1 changes, you can see:
- Which code modules are affected
- Which tests need updating
- Which stakeholders to inform

## Benefits of Traceability

- **Requirement coverage**: Makes sure nothing important is missed.
- **Change management**: Helps understand what needs to be changed if a requirement updates.
- **Audit trail**: Useful for clients, QA, and regulators to verify quality.
- **Improves collaboration**: Everyone knows how parts of the system are connected.

## Traceability Matrix

A **Traceability Matrix** is a table or spreadsheet used to link **requirements to code and tests**.

| Requirement ID | Description                 | Code Module       | Test Case ID   |
|----------------|-----------------------------|-------------------|----------------|
| REQ-01         | Allow users to log in       | login.js          | TC-001, TC-002 |
| REQ-02         | Allow password reset        | reset.js          | TC-003         |

**Use it to:**
- Prove that all requirements have been built and tested
- Find what to update if a requirement changes

##  What is Configuration Management (CM)?

**Configuration Management** is the discipline of **systematically controlling changes** to software, code, documents, and tools.

### In simple terms:
It’s about making sure that:
- Everyone works on the **correct version** of everything
- All changes are **recorded**
- You can **revert** to a previous version if needed
- Multiple people can safely **work together**

## Why Configuration Management Matters

Imagine building a group project without configuration management:

- Files get overwritten
- Nobody knows which version is the latest
- A bug fix accidentally deletes a new feature

CM **prevents chaos** by giving control, history, and collaboration tools.

## Key Concepts in CM

| Term | Explanation |
|------|-------------|
| **Configuration Item (CI)** | Any file or asset you track: source code, diagrams, documents, config files |
| **Version Control System (VCS)** | Software tool (e.g., Git) that tracks changes to files |
| **Baseline** | A stable, reviewed version of your project that you can return to |
| **Commit** | A snapshot of your project at a certain point |
| **Branch** | A separate working copy to develop features or fixes without affecting the main version |
| **Change Request** | A formal proposal to add, change, or delete something in the project |

## Git as a CM Tool

**Git** is the most popular modern version control system used to implement CM.

### Features of Git:

- **Track changes** with full history
- **Undo mistakes** easily
- **Branch and merge** work to experiment or collaborate
- **Collaborate** with remote teams using GitHub

### Common Git Commands for CM:

| Command | What It Does |
|---------|--------------|
| `git init` | Starts a Git repo in your folder |
| `git add` | Stages changes for a commit |
| `git commit -m "msg"` | Saves a snapshot of changes |
| `git log` | Shows all past commits |
| `git branch` | Lists or creates branches |
| `git merge` | Combines two branches |
| `git revert` | Undoes a previous commit safely |
| `git tag` | Marks stable releases like v1.0 |

## Change Management in Software Projects

Changes are **inevitable**. CM helps manage them carefully.

### Steps in Change Management:

1. **Raise a Change Request (CR)**  
   E.g., Add a dark mode feature

2. **Assess the Change**  
   Will it affect other parts? Is it risky? How long will it take?

3. **Approve/Reject**  
   Team lead or client decides whether to go ahead

4. **Implement & Test**  
   Devs write the code, QA tests it

5. **Update Documents & Traceability Matrix**  
   Keep everything up to date so the change is traceable

   
# COMP1050 – Week 12: Software Professionalism & Ethics

## What is Professionalism in Software Engineering?

Professionalism refers to how software engineers conduct themselves in their work and with others. It means behaving with honesty, integrity, responsibility, and respect in all aspects of software development.

A professional software engineer:
- Follows industry best practices
- Understands the social impact of their work
- Takes responsibility for their actions
- Prioritizes the needs and safety of users and society

This is important because software is now deeply embedded in our daily lives. A simple mistake or unethical choice in code can affect millions of people (e.g., health apps, banking, public transport systems).

## Why Ethics Matter in Software Development

Ethics in software engineering refers to making the right decisions, especially when there's a risk of harm, bias, or unfair outcomes.

Software engineers often have access to sensitive data and build systems that can affect human rights, safety, or privacy. They must make decisions that are:
- Fair
- Transparent
- Safe
- Respectful of user rights

For example, writing code that discriminates against certain users (intentionally or not) is unethical. Collecting user data without their knowledge is unethical. Letting known security flaws go unpatched is unethical.

## Types of Ethical Responsibilities

### 1. Responsibility to the Public
Engineers must always prioritize public interest and safety over company profit or personal benefit. They should avoid building or supporting harmful systems.

**Example:** Refusing to build software that invades user privacy or helps in mass surveillance without legal and ethical safeguards.

### 2. Responsibility to the Client and Employer
Engineers must provide honest, accurate information and work with integrity. They should not lie about progress or cover up mistakes.

**Example:** If a bug could cause customer data to leak, you must report it—even if it could delay the project.

### 3. Responsibility to the Profession
Engineers should support the growth of the profession by sharing knowledge, helping peers, and improving standards. They must not plagiarize or claim others’ work as their own.

**Example:** Contributing to open-source projects or mentoring junior developers.

### 4. Responsibility to Colleagues
Engineers must treat coworkers with respect and fairness, regardless of gender, race, beliefs, or role.

**Example:** Collaborating in a respectful and inclusive way during team projects.

## Key Ethical Dilemmas in Software

### 1. Data Privacy and Consent
Should you collect and use data that users haven’t explicitly agreed to share? Always follow principles of informed consent and transparency.

**Good Practice:** Clearly ask users to accept data collection and explain what it's used for.

### 2. Security and Backdoors
Should governments have backdoor access to secure systems? This is a real-world issue (e.g., Apple vs FBI). While it can help law enforcement, it risks weakening overall system security.

**Ethical Choice:** Consider both the benefits and the risk of misuse. Prioritize the long-term safety of all users.

### 3. Biased Algorithms
If your algorithm treats people unfairly based on gender or race, even unintentionally, that’s unethical.

**Ethical Development:** Test your systems for fairness and bias. Collect diverse data. Use explainable AI.

### 4. Whistleblowing
What if your company does something illegal or dangerous? As a professional, you may need to report it even if it puts your job at risk.

**Example:** Reporting unsafe autonomous driving code that’s about to go live.

## Ethics Frameworks and Codes of Conduct

### 1. ACS Code of Ethics (Australia)

The Australian Computer Society provides a professional code for all IT professionals. It includes key principles like:

- Honesty
- Trustworthiness
- Respect for privacy
- Professional development
- Social implications of computing

It encourages practitioners to act in the best interest of the public and to speak up when systems may cause harm.

### 2. IEEE/ACM Code of Ethics (Global)

The IEEE and ACM have a shared Software Engineering Code of Ethics. Key principles include:

- Public interest is always first
- Maintain integrity and independence in professional judgment
- Strive for high-quality, sustainable software
- Respect intellectual property and privacy

This code is used globally and gives developers a shared language to discuss ethical dilemmas.

## Ethical Decision-Making Process

When faced with a tough decision, follow these steps:

1. **Recognize the ethical issue**
   - Is someone being harmed?
   - Is this against user consent or trust?

2. **Gather all facts**
   - Understand the legal, technical, and personal impacts

3. **Consider stakeholders**
   - How will this affect users, clients, coworkers, the public?

4. **Evaluate your options**
   - Use principles like fairness, safety, respect

5. **Make and justify your decision**
   - Be ready to explain your reasoning based on ethical codes

6. **Reflect on the outcome**
   - Learn from the experience and improve your future decisions

## Software Liability and Accountability

As software becomes more critical (e.g., in health care, transport), the question arises:
**Who is responsible if something goes wrong?**

In many countries, developers or companies can be held legally responsible for damages caused by software bugs, security flaws, or ethical negligence.

This is why:
- Testing and documentation are so important
- Code reviews and ethics checks should be part of the process

## Ethical Tools and Best Practices

- Use **automated testing** to ensure code does what it's supposed to
- Conduct **code reviews** to catch unethical or risky decisions
- Write **clear privacy policies**
- Respect **user consent**
- Avoid collecting unnecessary data
- Practice **inclusive design** for accessibility and fairness


