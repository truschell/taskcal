# TaskCal

TaskCal is a simple, single-page web application for managing tasks and scheduling them on a weekly calendar view. It combines a task management system with an interactive calendar interface, allowing users to create, organize, and schedule tasks efficiently.

## Features

- **Weekly Calendar View**: Display a 7-day week calendar with hourly time slots
- - **Task Management**: Create, edit, and delete tasks with detailed information
  - - **Task Properties**:
    -   - Task title and description
        -   - Duration in minutes
            -   - Status tracking (To Do, In Progress, Complete)
                -   - Optional scheduling on the calendar
                    - - **Drag & Drop**: Drag tasks to schedule them on specific time slots
                      - - **Status Indicators**: Visual status pills showing task progress (TODO, IN_PROGRESS, COMPLETE)
                        - - **Delete Confirmation**: Confirmation dialog before permanently deleting tasks
                          - - **Navigation**: Previous/Next buttons to navigate through different weeks
                           
                            - ## How to Use
                           
                            - 1. **Open the Application**: Open `index.html` in a web browser
                              2. 2. **Create a Task**: Click the "+" button to open the new task modal
                                 3. 3. **Fill Task Details**:
                                    4.    - Enter a task title
                                          -    - Add optional description
                                               -    - Set duration in minutes
                                                    -    - Select status (To Do, In Progress, or Complete)
                                                         -    - Optionally set a schedule time
                                                              - 4. **Save Task**: Click "Save" to create the task
                                                                5. 5. **Schedule Task**: Drag a task from the list to a specific time slot on the calendar
                                                                   6. 6. **Manage Tasks**: Edit or delete tasks using the action buttons on each task card
                                                                      7. 7. **Navigate**: Use Previous/Next buttons to view different weeks
                                                                        
                                                                         8. ## Technical Details
                                                                        
                                                                         9. - **Technology**: HTML5, CSS3, JavaScript (Vanilla)
                                                                            - - **Architecture**: Single HTML file with embedded CSS and JavaScript
                                                                              - - **No Dependencies**: Runs completely in the browser with no external dependencies
                                                                                - - **Local Storage**: Tasks are stored in browser memory during the session
                                                                                 
                                                                                  - ## File Structure
                                                                                 
                                                                                  - ```
                                                                                    taskcal/
                                                                                    └── index.html    Main application file (HTML, CSS, and JavaScript combined)
                                                                                    ```

                                                                                    ## Browser Compatibility

                                                                                    Works on all modern browsers that support:
                                                                                    - HTML5
                                                                                    - - CSS3 Flexbox
                                                                                      - - ES6 JavaScript
                                                                                       
                                                                                        - ## Getting Started
                                                                                       
                                                                                        - 1. Clone or download this repository
                                                                                          2. 2. Open `index.html` in your web browser
                                                                                             3. 3. Start managing your tasks!
                                                                                               
                                                                                                4. ## Future Enhancements
                                                                                               
                                                                                                5. Potential features for future versions:
                                                                                                6. - Local storage persistence
                                                                                                   - - Task filtering and sorting
                                                                                                     - - Recurring tasks
                                                                                                       - - Task categories/tags
                                                                                                         - - Export/import functionality
                                                                                                           - - Dark mode support
