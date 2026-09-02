## Exp 8: Reproducing an Image Using Prompts for Image Generation

# Reg. No. 212225230075

## Aim:
To demonstrate the ability of text-to-image generation tools to reproduce an existing image by crafting precise prompts. The goal is to identify key elements within the image and use these details to generate an image as close as possible to the original.

# AI-Assisted Workflow Automation Using Structured Prompts

## Objective

The objective of this exercise is to help learners understand how **structured prompt engineering can be used to automate common project-management and technical communication tasks**.

Learners will design structured prompts to generate emails, meeting minutes, task plans, project schedules, requirement documents, and frequently asked questions (FAQs). The activity demonstrates how AI can transform unstructured project information into organized and reusable outputs.

The engineering case study used in this exercise is **College Symposium Management**.

---

# 1. Introduction

Managing a college symposium involves several activities such as planning events, assigning responsibilities, communicating with participants, tracking deadlines, documenting requirements, and answering frequently asked questions.

Traditionally, these activities may require considerable manual effort. AI-assisted workflow automation can help organize and generate project-related information using structured prompts.

The workflow can be represented as:

**Project Information → Structured Prompt → AI Processing → Generated Output → Human Review → Final Document**

AI does not replace the project team. Instead, it acts as an assistant that helps reduce repetitive documentation and communication work.

---

# 2. Engineering Case Study – College Symposium Management

### Project Title

**AI-Assisted College Symposium Management System**

### Project Objective

To organize and manage a college symposium efficiently by automating communication, task planning, scheduling, requirement documentation, and FAQ generation.

### Major Activities

* Event planning
* Registration management
* Participant communication
* Venue management
* Volunteer coordination
* Speaker coordination
* Technical support
* Food and accommodation planning
* Certificate distribution
* Feedback collection

---

# 3. Overall Automated Workflow

```text
                 COLLEGE SYMPOSIUM
                       │
                       ↓
              Project Information
                       │
                       ↓
              Structured Prompts
                       │
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
   Email Writing   Task Planning   Requirements
        │              │              │
        ↓              ↓              ↓
 Meeting Minutes   Scheduling      FAQ Generation
        │              │              │
        └──────────────┼──────────────┘
                       ↓
                 Human Review
                       ↓
                Final Documents
```

---

# 4. Automation 1 – Email Writing

Emails are required for communication with students, faculty members, speakers, judges, sponsors, and participants.

### Structured Prompt

```text
Act as a professional college event coordinator.

Create an email for a college symposium.

Purpose: Invite students to participate in the symposium.
Audience: Engineering students.
Event: Annual Technical Symposium.
Tone: Professional and friendly.

Include:
- Event name
- Date and venue placeholders
- Registration information
- Major activities
- Registration deadline
- Contact information placeholder

Keep the email concise and easy to understand.
Do not invent missing event details.
```

### Expected Output

The AI generates a structured invitation email containing the event information and a clear call to action.

### Human Verification

The organizer should verify:

* Date
* Time
* Venue
* Registration link
* Contact details
* Event name

---

# 5. Automation 2 – Meeting Minutes

After each planning meeting, the discussion can be converted into structured meeting minutes.

### Input

Example meeting information:

```text
Meeting Date: 10 September
Participants: Event Coordinator, Faculty Coordinator, Student Volunteers

Discussion:
- Venue needs to be finalized.
- Registration portal should be prepared.
- Three student volunteers will handle registration.
- Speaker invitations need to be sent.
- Posters should be prepared before the promotion date.
```

### Structured Prompt

```text
Convert the following meeting notes into professional Meeting Minutes.

Include:
1. Meeting date
2. Participants
3. Agenda
4. Key discussion points
5. Decisions taken
6. Action items
7. Responsible person
8. Deadline

Do not add information that is not present in the notes.
Use a clear table for action items.
```

### Expected Structure

| Action Item                 | Responsible Person  | Deadline |
| --------------------------- | ------------------- | -------- |
| Finalize venue              | Event Coordinator   | TBD      |
| Prepare registration portal | Technical Team      | TBD      |
| Manage registration         | Student Volunteers  | TBD      |
| Send speaker invitations    | Faculty Coordinator | TBD      |
| Prepare promotional poster  | Design Team         | TBD      |

---

# 6. Automation 3 – Task Planning

A symposium contains many tasks that need to be assigned to different team members.

### Structured Prompt

```text
Act as a project management assistant.

Create a task plan for managing a college technical symposium.

Divide the tasks into:
- Planning
- Registration
- Technical
- Publicity
- Venue
- Hospitality
- Finance
- Event-day activities

For every task provide:
Task ID, Task Description, Responsible Team, Priority,
Dependency, and Status.

Use "TBD" where information is not provided.
```

### Sample Task Plan

| ID  | Task                     | Team          | Priority | Dependency       | Status  |
| --- | ------------------------ | ------------- | -------- | ---------------- | ------- |
| T01 | Finalize event theme     | Core Team     | High     | None             | Pending |
| T02 | Confirm venue            | Logistics     | High     | T01              | Pending |
| T03 | Create registration form | Technical     | High     | Event details    | Pending |
| T04 | Design poster            | Publicity     | Medium   | Event details    | Pending |
| T05 | Invite speakers          | Faculty Team  | High     | Speaker list     | Pending |
| T06 | Arrange certificates     | Documentation | Medium   | Participant list | Pending |

---

# 7. Automation 4 – Project Scheduling

AI can convert the task list into a project schedule.

### Structured Prompt

```text
Create a project schedule for a college symposium.

Use the following tasks and dependencies.

Prepare a table containing:
- Task
- Start Date
- End Date
- Duration
- Dependency
- Responsible Team

Identify tasks that can be performed simultaneously.
Do not assume exact dates unless they are provided.
Use placeholders for missing information.
```

### Example Schedule

| Task                    | Start  | End    | Dependency     |
| ----------------------- | ------ | ------ | -------------- |
| Event Planning          | Day 1  | Day 3  | None           |
| Venue Confirmation      | Day 2  | Day 4  | Event Planning |
| Registration Setup      | Day 3  | Day 6  | Event Planning |
| Publicity               | Day 5  | Day 12 | Poster         |
| Speaker Coordination    | Day 3  | Day 10 | Speaker List   |
| Final Event Preparation | Day 11 | Day 14 | Major Tasks    |

The schedule helps the team understand task dependencies and identify activities that can happen in parallel.

---

# 8. Automation 5 – Requirement Documentation

Requirement documentation defines what the symposium management system needs to accomplish.

### Structured Prompt

```text
Act as a systems analyst.

Prepare a Software Requirements Specification outline for a
College Symposium Management System.

Include:
1. Functional requirements
2. Non-functional requirements
3. User roles
4. Inputs
5. Outputs
6. System constraints
7. Security requirements
8. Performance requirements

Separate functional and non-functional requirements clearly.
Do not invent requirements that are not relevant to symposium management.
```

### Functional Requirements

* Student registration
* Participant information management
* Event management
* Schedule management
* Volunteer assignment
* Email notification
* Attendance tracking
* Certificate management
* Feedback collection

### Non-Functional Requirements

* Usability
* Reliability
* Security
* Performance
* Availability
* Maintainability
* Scalability

---

# 9. Automation 6 – FAQ Generation

Participants often ask similar questions regarding registration, venue, events, certificates, and schedules.

AI can convert available information into an FAQ document.

### Structured Prompt

```text
Generate an FAQ document for a college technical symposium.

Use only the information provided below.

Organize questions into:
- Registration
- Events
- Venue
- Schedule
- Certificates
- Technical Support
- Contact Information

Provide short and clear answers.
If an answer is not available, write "Information not provided"
instead of inventing an answer.
```

### Sample FAQs

**Q1. Who can participate in the symposium?**
A: Eligible students can participate according to the event rules.

**Q2. Where will the symposium be conducted?**
A: The venue details will be provided by the event organizers.

**Q3. How can participants register?**
A: Participants can register through the official registration process.

**Q4. Will participants receive certificates?**
A: Certificate details should be confirmed with the event organizers.

---

# 10. Structured Prompt Template

A structured prompt can follow this format:

```text
ROLE:
Define who the AI should act as.

CONTEXT:
Provide background information about the project.

TASK:
Clearly state what needs to be generated.

INPUT:
Provide the information that AI should use.

CONSTRAINTS:
Specify what AI should and should not do.

OUTPUT FORMAT:
Specify table, bullet points, email, report, etc.

QUALITY REQUIREMENTS:
Specify accuracy, clarity, professional tone, and completeness.
```

### Example

```text
ROLE:
Act as a college event project manager.

CONTEXT:
A technical symposium is being organized by the engineering department.

TASK:
Create a task management plan.

INPUT:
Use the provided list of symposium activities.

CONSTRAINTS:
Do not invent missing deadlines or responsible persons.

OUTPUT:
Provide a table with Task ID, Task, Team, Priority,
Dependency, Deadline, and Status.

QUALITY:
Use concise, professional, and clearly organized language.
```

---

# 11. Complete Automated Workflow

The complete workflow can be organized as follows:

| Stage | Input                      | AI Task               | Output               |
| ----- | -------------------------- | --------------------- | -------------------- |
| 1     | Event information          | Analyze project       | Project summary      |
| 2     | Communication requirements | Generate email        | Professional email   |
| 3     | Meeting notes              | Structure information | Meeting minutes      |
| 4     | Project activities         | Organize tasks        | Task plan            |
| 5     | Task dependencies          | Create schedule       | Project schedule     |
| 6     | System needs               | Analyze requirements  | Requirement document |
| 7     | Participant information    | Generate questions    | FAQ document         |
| 8     | All outputs                | Review                | Final documentation  |

---

# 12. Human Review and Validation

AI-generated outputs should be reviewed before they are used.

The project team should check:

### Accuracy

Are dates, names, locations, and responsibilities correct?

### Completeness

Are all important tasks and requirements included?

### Consistency

Do the email, schedule, meeting minutes, and FAQ contain consistent information?

### Readability

Is the information easy to understand?

### Privacy

Does the output unnecessarily expose personal or confidential information?

### Hallucination Control

Has AI added information that was not provided?

---

# 13. Advantages of AI-Assisted Workflow Automation

### 1. Saves Time

Repeated documentation tasks can be generated quickly.

### 2. Improves Organization

Unstructured notes can be converted into tables and structured documents.

### 3. Reduces Repetitive Work

Frequently repeated communication tasks can be automated.

### 4. Improves Consistency

A common format can be maintained across documents.

### 5. Supports Project Management

Tasks, dependencies, and responsibilities can be organized systematically.

### 6. Improves Communication

Clear emails, FAQs, and meeting minutes can be generated quickly.

---

# 14. Limitations

AI-assisted automation also has limitations:

* AI may misunderstand incomplete information.
* AI can generate incorrect assumptions.
* Dates and schedules must be verified.
* Human approval is required for important communications.
* Confidential information should be handled carefully.
* AI-generated requirements may not reflect actual stakeholder needs.
* Automated outputs can contain formatting or factual errors.

Therefore, **human review must remain part of the workflow**.

---

# 15. Deliverable – Automated Workflow Documentation

The final submission should contain:

### 1. Project Overview

* Project title
* Objective
* Problem statement
* Scope

### 2. Workflow Diagram

Show the complete automation process from input to final output.

### 3. Structured Prompts

Include prompts used for:

* Email writing
* Meeting minutes
* Task planning
* Project scheduling
* Requirement documentation
* FAQ generation

### 4. Generated Outputs

Include the AI-generated documents.

### 5. Validation

Document how the outputs were checked for:

* Accuracy
* Completeness
* Consistency
* Readability
* Hallucinated information

### 6. Before-and-After Comparison

Show the difference between raw project information and AI-structured output.

### 7. Final Workflow

```text
Project Input
     ↓
Structured Prompt
     ↓
AI Processing
     ↓
Email / Minutes / Tasks / Schedule
     ↓
Requirements / FAQs
     ↓
Human Verification
     ↓
Final Approved Documents
```

---

# 16. Expected Learning Outcomes

After completing this exercise, learners will be able to:

* Design structured prompts for workflow automation.
* Automate repetitive technical communication tasks.
* Convert unstructured information into structured documents.
* Generate professional emails and meeting minutes.
* Create project task plans and schedules.
* Document functional and non-functional requirements.
* Generate FAQs from verified project information.
* Identify the limitations of AI-generated outputs.
* Apply human verification to AI-assisted workflows.
* Document an end-to-end engineering workflow.

---

## Conclusion

AI-assisted workflow automation can improve the efficiency of engineering project management by converting project information into structured and useful outputs. In the **College Symposium Management** case study, structured prompts can be used to automate email writing, meeting minutes, task planning, project scheduling, requirement documentation, and FAQ generation.

The most important principle is that AI-generated content should be **reviewed and validated by humans before it is used**. By combining structured prompting with human verification, learners can develop efficient, reliable, and professional workflows for real-world engineering projects.


## Result

Thus,the given prompt executed successfully
