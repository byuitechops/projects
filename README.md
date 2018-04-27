# The Project Process

When a new project is given to the team, this is the process it should follow on the [Techops Development Projects Board](https://github.com/orgs/byuitechops/projects/5):

1. Before any code or design is completed for the project, a new issue needs to be created on the board by adding a new note, then converting it into an issue:
    - The issue should be created in this repository.
    - If it is an approved project, it should be added to the **Approved** column.
        - Create a new repository and put the link to it in the description of the new issue.
    - If it is a potential project, it should be added to the **Investigation** column.
        - You should not create a repository yet, but add it when it becomes approved.
    - If known, assign the issue to the developers who will be working on it.
    - Give it one of the existing labels based on the time the project will take (best guess):
      - *mini*: less than a week
      - *small*: less than a month
      - *medium*: less than two months
      - *large*: more than two months
      
2. When design has started on the project, move it into the **In Progress** column. It should remain there until the project is officially complete.

3. If a project is completed, but requires ongoing maintenance (i.e. the Qualtrics Sync tool), it should be given the *Ongoing Maintenance* label and all other labels should be removed. Move it into the **Ongoing Maintenance** column until a time when it no longer needs maintenance.

4. A project is complete and can be moved into the **Complete** column when:
    - It no longer requires maintenance
    - It has no features left to add that **need** to be added
    - Thorough documentation has been added
    - The customer is satisfied with the tool
