# GET IT DONE - Task Manager

GET IT DONE is a polished single-page to-do app built with plain HTML, CSS, and JavaScript. It is designed for fast task capture, simple filtering, and local persistence without any build step or external framework.

## Overview

The app focuses on quick task management with a bold, high-contrast interface. Tasks can be added, marked complete, filtered, and cleared directly in the browser. All data is stored locally using `localStorage`, so your list stays available after refreshes and browser restarts.

## Features

- Add tasks instantly from the input field or by pressing Enter
- Mark tasks as active or completed
- Filter the list by All, Active, or Completed
- View live counters for total, active, and completed tasks
- Track progress with a completion bar
- Clear all completed tasks in one action
- See timestamped task entries
- Receive toast notifications for common actions
- Persist data locally in the browser using `localStorage`
- Responsive layout for desktop and mobile screens

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts: Bebas Neue and Space Mono

## Project Structure

- `index.html` - The full application, including markup, styles, and logic

## How to Run

This project does not require installation or a package manager.

1. Open the `todo-app` folder in VS Code.
2. Open `index.html` in your browser.
3. Use VS Code Live Server or any static file server if you want automatic refresh while developing.

If you are using Live Server:

1. Install the Live Server extension in VS Code.
2. Right-click `index.html`.
3. Choose Open with Live Server.

## Usage

1. Type a task into the input field.
2. Press Enter or click `+ Add`.
3. Click the checkbox area to mark a task completed.
4. Use the filter buttons to switch between All, Active, and Completed tasks.
5. Click the delete button to remove a single task.
6. Use Clear Completed to remove finished tasks in bulk.

## Persistence

Tasks are saved in the browser under the `gid_tasks_v1` key. This means:

- Your tasks remain after refreshing the page
- Your tasks remain after closing and reopening the browser
- Clearing site data will remove the saved list

## Customization

You can adjust the app by editing `index.html` directly.

- Change the visual theme by editing the CSS variables in `:root`
- Update the title and tagline in the header
- Modify task limits, labels, or toast messages in the JavaScript section
- Replace fonts by changing the Google Fonts import in the `<head>`

## Browser Support

The app should work in all modern browsers that support:

- `localStorage`
- `querySelectorAll`
- CSS custom properties
- Standard ES6 JavaScript features

## Notes

- This is a client-side only app; no backend is required.
- There is no database, account system, or cloud sync.
- All task data lives in the current browser profile.

## Future Improvements

Possible enhancements if you want to expand the project:

- Edit existing tasks inline
- Add due dates or priority levels
- Add drag-and-drop reordering
- Support task categories or tags
- Add dark/light theme toggles
- Export and import task data

## License

No license has been specified for this project yet. Add one if you plan to share or publish it publicly.
