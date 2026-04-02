# ZTD-HTML-CSS

A comprehensive HTML/CSS UI clone of **Zoho ToDo** application, covering all major views, pages, and use cases.

## Pages

| File | Description |
|------|-------------|
| `index.html` | **Agenda Board View** - Kanban-style board with Delayed, Today, This Week, and Upcoming columns. Includes New Task modal. |
| `agenda-list.html` | **Agenda List View** - Tabular list grouped by Delayed, Today, This Week, This Month, and Upcoming sections. |
| `my-day.html` | **My Day Board View** - Daily task board with To Do, In Progress, and Done columns. |
| `created-by-me.html` | **Created by Me List View** - Task list grouped by Personal tasks and Work tasks with status, priority, and due dates. |
| `task-detail.html` | **Task Detail / Edit View** - Split panel with task list on left and detailed task editing panel on right (title, description, notes, subtasks, timeline, comments). |
| `search.html` | **Search Results** - Search interface with filter chips (All, Tasks, Groups, Tags, Open, Completed, High Priority) and result list with highlighted matches. |
| `notifications.html` | **Notifications Panel** - Right-side notification panel with All/Unread tabs, notification items showing avatars, actions, and timestamps. |
| `settings.html` | **Settings - System** - System settings page with theme selection (Dark/Light/White), font settings, appearance options, and keyboard shortcuts. |

## Features

- Dark theme (Night mode) matching Zoho ToDo design
- - Responsive sidebar with navigation, tags, and groups
  - - Board view (Kanban) and List view layouts
    - - Create task modal with full form fields
      - - Task detail split-panel editing
        - - Search with filter chips and highlighted results
          - - Notification panel with unread indicators
            - - Settings page with theme and appearance options
              - - Cross-page navigation between all views
                - - CSS custom properties for easy theming
                 
                  - ## Tech Stack
                 
                  - - Pure HTML5 and CSS3
                    - - Google Fonts (Lato)
                      - - No JavaScript frameworks required
                        - - Shared stylesheet (`css/styles.css`)
                         
                          - ## Getting Started
                         
                          - 1. Clone the repository
                            2. 2. Open `index.html` in your browser
                               3. 3. Navigate between pages using the sidebar and top bar links
                                 
                                  4. ## File Structure
                                 
                                  5. ```
                                     ZTD-HTML-CSS/
                                     ├── css/
                                     │   └── styles.css          # Shared stylesheet for all pages
                                     ├── index.html              # Agenda Board View (Homepage)
                                     ├── agenda-list.html        # Agenda List View
                                     ├── my-day.html             # My Day Board View
                                     ├── created-by-me.html      # Created by Me List View
                                     ├── task-detail.html        # Task Detail / Edit Panel
                                     ├── search.html             # Search Results Page
                                     ├── notifications.html      # Notifications Panel
                                     ├── settings.html           # Settings Page
                                     └── README.md               # This file
                                     ```
