# Vault Scholars TODO App

This is a starter project for your **mid-course project**: building a TODO app
using only **HTML, CSS, and JavaScript**.

## How to run it

1. Open `index.html` directly in your browser.
2. Start editing the files inside the `assets/` folder and refresh your browser
   to see changes.

## Folder structure

```text
todo-app/
├── index.html          # Main HTML page
├── assets/
│   ├── css/
│   │   ├── base.css        # Colors, fonts, resets, global styles
│   │   ├── layout.css      # Page layout (header, main, footer, cards)
│   │   └── components.css  # Buttons, task list, small UI pieces
│   ├── js/
│   │   ├── app.js          # Main app "brain" (event listeners + logic)
│   │   ├── dom.js          # DOM helper functions (rendering tasks)
│   │   └── storage.js      # Optional: functions for localStorage
└── README.md
```

## Your job

- Fill in the TODOs in `app.js` to:
  - Read values from the form.
  - Add new task objects to the `tasks` array.
  - Mark tasks as completed.
  - Delete tasks.

- Fill in the TODOs in `dom.js` to implement DOM helper functions for rendering tasks.

- Fill in the TODOs in `storage.js` to implement localStorage functions for persisting tasks.

- Use the helper functions from:
  - `dom.js` to render tasks.
  - `storage.js` to persist tasks between page loads using `localStorage`.

- Note: There is a placeholder task element in the HTML for reference. Remove it once you implement the rendering logic.

- Feel free to update the CSS styles to personalize your project.

As you work, try to keep your code organized and readable. Pretend you are
handing this project to another developer who has never seen it before.

## Submission

To submit your project:

1. Create a new branch from `main`.
2. Implement your code on that branch.
3. Submit a pull request to `main`.

We'll review the pull request and approve it if it matches the expected output for the project.
