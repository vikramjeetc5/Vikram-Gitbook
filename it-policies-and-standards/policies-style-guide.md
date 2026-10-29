# Policies Style Guide

This page sets the writing and formatting rules for the pages in the IT Policies and Standards folder. Follow it when you write or edit a policy, so every policy looks the same and is easy to check. For how-to pages, see the How-to Style Guide.

| Owner                                | Document type | Version | Last updated    |
| ------------------------------------ | ------------- | ------- | --------------- |
| IT / Information Security Department | Style guide   | 1.0     | 29 October 2026 |

### Policy Page Template

Every policy follows this order:

1. Opening paragraph: what the policy covers and who it applies to
2. Info hint with the key idea, and a link to the matching how-to guide
3. Policy details table
4. Rules at a glance (a table of the key requirements)
5. Process (stepper), only if the policy has one
6. Detailed rules (expandables)
7. Responsibilities (table)
8. Compliance and exceptions
9. Related pages

### Policy Details Table

Every policy starts with the same table, with the same rows in the same order:

| Row                | Content                                               |
| ------------------ | ----------------------------------------------------- |
| Owner              | The department that maintains the policy              |
| Policy type        | IT policies and standards                             |
| Version            | Starts at 1.0 and changes with each approved revision |
| Effective date     | When the policy starts to apply                       |
| Last reviewed      | The date of the latest review                         |
| Next review        | Usually twelve months after the last review           |
| Approval authority | The role that approves changes                        |

### Wording Rules

| Topic            | Rule                                                          | Example                                   |
| ---------------- | ------------------------------------------------------------- | ----------------------------------------- |
| Requirements     | Use "must" for a requirement and "must not" for a prohibition | "Employees must lock their screen."       |
| Advice           | Use "should" only for recommendations, and mark them as such  | "Use a passphrase."                       |
| Level            | Label each rule in a table as Required or Recommended         | See Rules at a glance                     |
| Length           | One rule per sentence or bullet                               | Not "Do X, Y and Z, and also W"           |
| Roles            | Name the role, not "someone"                                  | "The IT Department verifies the request." |
| Numbers          | Give exact values, and keep them in one table                 | "14 characters", "7 days"                 |
| Cross-references | Link to the related policy instead of repeating it            | "See the **Password Policy**."            |

### Which Block for Which Content

| Content                                                              | Block                                         |
| -------------------------------------------------------------------- | --------------------------------------------- |
| Policy details, rules at a glance, responsibilities, fixed standards | Table                                         |
| A process with an order, such as handling a compromise               | Stepper                                       |
| Detailed rules and edge cases most readers will not need             | Expandable                                    |
| Content that differs by operating system or situation                | Tabs, with one or two short words as titles   |
| The key idea of the policy                                           | Hint: info                                    |
| A prohibited action, or the strictest rule                           | Hint: danger                                  |
| Consequences, exceptions, or "do not bypass"                         | Hint: warning                                 |
| A branching approval or decision path                                | Mermaid diagram, only where it adds something |

### Compliance and Exceptions Section

Every policy ends its content with these two parts:

* **Compliance:** a warning hint that says what happens when the policy is not followed, plus where to report violations.
* **Exceptions:** a list saying that an exception needs a documented reason, a risk assessment where appropriate, approval from the designated authority, a limited scope and duration, and a review date.

### Naming and Links

* Page titles end in "Policy" or "Guidelines".
* Use the same name in the title, the sidebar, the cards, and every link.
* Link only to pages that exist. Remove a reference if its page is not published.
* Related pages go in one line at the end, in bold, and each one is linked.

### Review and Version Control

* Review every policy at least once a year, and update "Last reviewed" and "Next review".
* Change the version number whenever the rules change.
* Record who approved the change in the approval authority row.

### Before You Publish

* [ ] The page follows the template in order
* [ ] The policy details table is complete
* [ ] Every rule says Required or Recommended
* [ ] All exact values (lengths, deadlines, times) are in one table
* [ ] Every link opens the right page
* [ ] Tables and tabs display in full on a phone
* [ ] Compliance and exceptions are included
