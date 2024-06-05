# Tickets in Github

We use Github tickets (or "issues") to define and track issues and potential issues at the repository level.

## When to Create a Ticket

Tickets should generally be created for:
- **Defects**: To note any defect observed in the application.
- **Enhancements**: To suggest any feature or improvement.
- **Development Tasks**: To define any feature or enhancement tasked for development.
- **Non-Coding Tasks**: To define non-coding tasks on which a milestone is dependent.

Any code change pushed to a repository should be associated with a ticket, with only rare exceptions.

### Who Can Create a Ticket?

Any person in STG/LIT may create a ticket in an STG/LIT project repository. Our projects often include partners outside STG/LIT, and those project team members may also create tickets in the appropriate repository.

## Anatomy of a Ticket

### Title

- Concise, clear, and self-explanatory.
- For suggested features or enhancements, consider beginning the title with "Consider".
- Titles may be updated/edited later as needed.

### Description

The description should concisely, yet sufficiently, describe the scope of work and desired result. It should be specific enough that a pull request addressing this ticket can be tested to determine whether it accurately implements the change.

#### For Defects (Bugs)

Include the following:
- Steps to reproduce the defect, and any relevant context (e.g., environment/server, browser used).
- The result deemed defective.
- The expected result.
- A screenshot (if relevant).
- Any potentially relevant areas of code identified (if possible).

#### Adding Comments

Comment liberally in the Description section. Github doesn't charge us per word.

If a discussion about a ticket occurs in real life, add notes into the ticket to capture the important points of the discussion. This helps:
- Clarify conclusions.
- Ensure everyone can refer back to it later.

### Tags (Labels)

Tagging tickets is optional but useful. These tags should be used when applicable:
- `Bug`: For defects.
- `Enhancement`: For suggested features or improvements.
- `Wontfix`: When tagging a ticket as "Wontfix" and closing it, add a comment explaining why.
- `Proposed`
- `High Priority`: For marking critical defects and "must-do" enhancements for a milestone.

Multiple tags may be applied to a ticket. Ad-hoc tags may be created and used as appropriate per project.

### Assignee

- When creating a ticket, this may (and often should) be left empty.
- The Assignee is generally assigned by the project manager, although this depends on the project.

### Milestone

- The Milestone is generally assigned by the project manager.

## Pull Requests Are Github Issues (Tickets) Too

As far as Github is concerned, a Pull Request ("PR") is just another type of Issue. We like the creator of a Pull Request to include:
- A reference back to the ticket, for easier navigation (e.g., "refs #123").
- Notes telling the tester how to test the PR.

---

For more information on Github's features, including notifications, references, and mentions, see [Github's guide to notifications, references, mentions, etc.](https://guides.github.com/features/issues/index.html#notifications).
