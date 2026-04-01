# Todo List Application

**Difficulty:** Advanced

**Concepts:** CRUD Operations, File Persistence, Data Structures, Menu Systems, Data Formatting

---

## Description

Create a fully functional todo list application where users can manage their tasks. Tasks persist between program runs by saving to a file.

CRUD stands for Create, Read, Update, Delete - the four basic operations for managing data.

---

## Requirements

- Display a menu with options:
  - View all tasks
  - Add a new task
  - Mark a task as complete
  - Delete a task
  - Quit
- Each task should have:
  - A description
  - A status (complete or incomplete)
  - An ID or number for reference
- Save tasks to a file so they persist after closing
- Load tasks from the file when the program starts

---

## Example

*Lines starting with `>` represent user input.*

```
=== Todo List ===

Your tasks:
[1] [ ] Buy groceries
[2] [X] Finish homework
[3] [ ] Call mom

Options:
(A)dd task
(C)omplete task
(D)elete task
(Q)uit

Choose an option:
> A
Enter task description:
> Walk the dog
Task added!

Your tasks:
[1] [ ] Buy groceries
[2] [X] Finish homework
[3] [ ] Call mom
[4] [ ] Walk the dog

Choose an option:
> C
Enter task number to mark complete:
> 1
Task marked as complete!

Your tasks:
[1] [X] Buy groceries
[2] [X] Finish homework
[3] [ ] Call mom
[4] [ ] Walk the dog

Choose an option:
> Q
Tasks saved. Goodbye!
```

---

## Hints

*There are many ways to solve this challenge. These hints may not apply to your language or approach.*

<details>
<summary>Hint 1</summary>

Store tasks in a list/array of objects or dictionaries, each containing the task description and completion status.

</details>

<details>
<summary>Hint 2</summary>

For file storage, you can use plain text (one task per line with a marker for completion) or JSON format for more structure.

</details>

<details>
<summary>Hint 3</summary>

Load tasks at the start of the program and save after any change, or save when the user quits.

</details>

---

## Bonus Challenges

- [ ] Add due dates to tasks
- [ ] Add priority levels (high, medium, low)
- [ ] Sort tasks by completion status, date, or priority
- [ ] Add categories or tags
- [ ] Add a search function
- [ ] Support multiple todo lists
