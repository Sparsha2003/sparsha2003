You are an expert AI developer. Generate a React‐based productivity web application (“PomodoroTodo”) that seamlessly combines a to-do list with the Pomodoro time-management technique. Use HTML5, modern CSS (flexbox/grid, CSS modules or styled-components), and JavaScript/TypeScript. The app should be mobile-responsive and optimized for desktop.

1. **Project Scaffold & Architecture**  
   - Provide a Create-React-App (or Vite) scaffold.  
   - Organize code into src/components, src/hooks, src/context, src/styles, src/utils.  
   - Use functional components, React Hooks, and Context API for global state.  
   - Persist tasks and settings in localStorage.

2. **To-Do List**  
   - Display a list of tasks with:  
     - A text label,  
     - A tomato-icon button on the right to launch the timer,  
     - A checkbox or “mark done” button that crosses the task out and moves it to a completed section.  
   - Allow adding, editing, deleting, and drag-and-drop reordering of tasks.  
   - Animate the addition/deletion of tasks (fade-in/out).

3. **Pomodoro Timer**  
   - Clicking the tomato icon opens an overlay/modal timer styled as a realistic tomato:  
     - A circular SVG or CSS-shaped dial with a subtle emboss effect.  
     - Default work duration of 25 minutes, editable via “+”/“–” controls.  
     - A start/pause/reset button.  
     - A live digital countdown in the center.  
   - When work timer ends:  
     - Automatically start a break timer of 5 minutes (styled as a coffee-cup icon or soft green circle).  
     - Play a gentle sound or vibration.  
     - After break, return to the task list view.

4. **Customization & Settings**  
   - A Settings page/modal where users can:  
     - Set default work/break durations.  
     - Toggle automatic break start.  
     - Choose color themes (e.g. “Tomato Red,” “Mint Green,” “Midnight Dark”).  
   - Persist settings in localStorage.

5. **Progress Dashboard**  
   - At the top or in a sidebar, show:  
     - Total tasks for today, completed tasks count.  
     - Pomodoros completed this session and daily streak.  
     - A simple bar chart or donut chart (use a lightweight chart library) showing progress.

6. **Aesthetics & UX**  
   - Use a warm, motivating palette: reds/oranges for “work,” greens/blues for “break,” neutrals for background.  
   - Employ soft drop-shadows, rounded corners (border-radius: 8px+), smooth transitions for hover/focus.  
   - Ensure all interactive elements have clear hover/focus states for accessibility.  
   - Support keyboard shortcuts:  
     - Start/pause timer (Space),  
     - Next task (N),  
     - Open settings (S).

7. **Code Quality & Documentation**  
   - Include PropTypes or TypeScript interfaces for all components.  
   - Write JSDoc comments for major functions.  
   - Provide a README.md with setup, development, and build instructions.

Generate the complete file structure and full source code for all components, styles, context providers, and utility functions so I can run the app out of the box.
