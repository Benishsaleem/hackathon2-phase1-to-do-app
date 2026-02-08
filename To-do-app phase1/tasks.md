## Tasks for 'To-do app phase1'

This file outlines the tasks for implementing the 'To-do app phase1' feature. Tasks are organized by user story and include file paths for clarity.

### Setup and Foundational Tasks

* [ ] T001 Create project structure: `src/components`, `src/utils`, `src/services`, `src/store`.
* [ ] T002 Initialize version control (if not already done).
* [ ] T003 Install necessary dependencies (e.g., React, state management library, testing library).
* [ ] T004 Set up basic linting and formatting rules.

### User Story: Add New To-Do Item

* [P] [ ] T005 [US1] Create `src/components/TodoInput.tsx` for the input field and add button.
* [P] [ ] T006 [US1] Implement logic in `src/store/todoSlice.ts` (or equivalent) to handle adding new todos.
* [ ] T007 [US1] Connect `TodoInput` to the store to dispatch the add todo action.
* [ ] T008 [US1] Define and validate the data structure for a single to-do item (e.g., `id`, `text`, `completed`).
* [ ] T009 [US1] Add unit tests for the add todo functionality in `src/store/todoSlice.ts`.

### User Story: View To-Do List

* [P] [ ] T010 [US2] Create `src/components/TodoList.tsx` to display a list of to-do items.
* [P] [ ] T011 [US2] Create `src/components/TodoItem.tsx` to render a single to-do item.
* [ ] T012 [US2] Fetch and display the list of to-dos from the store in `TodoList`.
* [ ] T013 [US2] Implement rendering of `TodoItem` within `TodoList`, passing down to-do data.
* [ ] T014 [US2] Add unit tests for `TodoList` and `TodoItem` components.

### User Story: Mark To-Do Item as Complete

* [P] [ ] T015 [US3] Add a checkbox or similar UI element in `TodoItem.tsx` for marking completion.
* [P] [ ] T016 [US3] Implement logic in `src/store/todoSlice.ts` to toggle the `completed` status of a to-do item.
* [ ] T017 [US3] Connect the UI element in `TodoItem` to dispatch the toggle completion action.
* [ ] T018 [US3] Add visual indicators in `TodoItem` to show whether a to-do is completed (e.g., strikethrough).
* [ ] T019 [US3] Add unit tests for the toggle completion functionality in `src/store/todoSlice.ts`.

### User Story: Delete To-Do Item

* [P] [ ] T020 [US4] Add a delete button in `TodoItem.tsx`.
* [P] [ ] T021 [US4] Implement logic in `src/store/todoSlice.ts` to remove a to-do item by its ID.
* [ ] T022 [US4] Connect the delete button in `TodoItem` to dispatch the delete todo action.
* [ ] T023 [US4] Add unit tests for the delete todo functionality in `src/store/todoSlice.ts`.

### User Story: Edit To-Do Item

* [P] [ ] T024 [US5] Add an edit button/icon in `TodoItem.tsx`.
* [P] [ ] T025 [US5] Implement a modal or inline editing interface for modifying an existing to-do's text.
* [P] [ ] T026 [US5] Implement logic in `src/store/todoSlice.ts` to update the text of a to-do item.
* [ ] T027 [US5] Connect the edit interface to dispatch the update todo action.
* [ ] T028 [US5] Add unit tests for the update todo functionality in `src/store/todoSlice.ts`.

### Acceptance Criteria:

*   All user stories are implemented.
*   All tasks are represented as checklist items.
*   File paths are included for relevant tasks.
*   Independently testable tasks are identified.
*   Parallelizable tasks are marked with `[P]`.

### Critical Files for Implementation
- `C:\\Users\\BINI\\Desktop\\hckathon2\\To-do-app phase1\\tasks.md` - The main file for task management.
- `C:\\Users\\BINI\\Desktop\\hckathon2\\To-do-app phase1\\src\\store\\todoSlice.ts` - Core logic for managing to-do state.
- `C:\\Users\\BINI\\Desktop\\hckathon2\\To-do-app phase1\\src\\components\\TodoInput.tsx` - UI component for adding new tasks.
- `C:\\Users\\BINI\\Desktop\\hckathon2\\To-do-app phase1\\src\\components\\TodoList.tsx` - Component for displaying the list of tasks.
- `C:\\Users\\BINI\\Desktop\\hckathon2\\To-do-app phase1\\src\\components\\TodoItem.tsx` - Component for rendering individual tasks.
