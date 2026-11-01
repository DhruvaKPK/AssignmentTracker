# AssignmentTracker

## Project Overview
AssignmentTracker is a Java-based command-line application designed to help college students organize their assignments and manage deadlines.

As a Purdue student, I often have assignments from multiple classes, making it difficult to keep track of deadlines and priorities. This project aims to solve that problem by providing a simple way to manage coursework in one place.

## Project Goal
The goal of AssignmentTracker is to create an easy-to-use tool that allows students to organize assignments, prioritize tasks, and track their progress without needing a complicated application.

## MVP Features
The first version of AssignmentTracker will include:

- Add assignments with names, courses, due dates, and priorities.
- View all assignments in a readable format.
- Edit existing assignment information.
- Delete assignments that are no longer needed.
- Sort assignments by due date and priority.
- Mark assignments as completed.
- Save and load assignments using a CSV file.

## Future Features (Version 2.0)
Features planned for future development include:

- Deadline reminders and notifications.
- Weekly calendar view for upcoming assignments.
- Assignment completion statistics and study progress tracking.

## Tech Stack
- **Programming Language:** Java
- **Development Environment:** IntelliJ IDEA or VS Code
- **User Interface:** Command-line interface (CLI)
- **Data Storage:** CSV file (`assignments.csv`)
- **Version Control:** Git and GitHub
- **External APIs:** None

### Java Libraries
- `java.util.Scanner` - Handles user input.
- `java.util.ArrayList` - Stores assignments.
- `java.util.Comparator` - Sorts assignments.
- `java.time.LocalDate` - Manages due dates.
- `java.time.format.DateTimeFormatter` - Formats dates.
- `java.io` - Handles file reading and writing.

## How It Will Work
1. The user launches the Java application.
2. A command-line menu displays available options.
3. The user selects an operation such as adding or viewing assignments.
4. The program processes the request.
5. Assignment information is saved to a CSV file.
6. The user can continue managing assignments or exit.

## Planned Project Structure

AssignmentTracker/
- README.md
- src/
  - Main.java
  - Assignment.java
  - AssignmentManager.java
- docs/
  - eisenhower-matrix.md
  - system-diagram.drawio
  - system-diagram.png
- tests/

## Development Milestones
1. Set up the GitHub repository and Java project.
2. Create the Assignment class.
3. Build the command-line menu.
4. Implement adding and viewing assignments.
5. Implement editing and deleting assignments.
6. Add sorting and priority features.
7. Implement assignment completion tracking.
8. Add CSV file saving and loading.
9. Test, debug, and document the application.

## Project Documentation

### Eisenhower Matrix
The Eisenhower Matrix outlines the MVP features, future improvements, library usage, and features excluded from the project.

[View Eisenhower Matrix](docs/eisenhower-matrix.md)

### System Diagram
The system diagram shows how the command-line menu, AssignmentManager, Assignment class, and CSV storage interact.

![AssignmentTracker System Diagram](docs/system-diagram.png)

[View Editable Diagram](docs/system-diagram.drawio)

## Current Status
Project planning and initial repository setup are in progress. Implementation will follow the development milestones listed above.
