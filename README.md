# SEN-Assignment-

This project is a simple Python-based command-line To-Do List application.
It allows users to add tasks, view tasks, mark tasks as completed, and store
tasks persistently using a JSON file.

--------------------------------------------------
SOFTWARE DEVELOPMENT LIFE CYCLE (SDLC)
--------------------------------------------------

1. REQUIREMENT ANALYSIS
- The user needs a simple task manager.
- The application must:
  • Add tasks
  • Display tasks
  • Mark tasks as completed
  • Save data between runs

2. PLANNING
- Decide to use Python for simplicity.
- Choose JSON file storage instead of a database.
- Design a menu-driven CLI interface.

3. DESIGN
- Tasks are stored as a list of dictionaries.
- Each task has:
  • title (string)
  • completed (boolean)
- Functions are created for each operation:
  • add_task()
  • view_tasks()
  • complete_task()

4. DEVELOPMENT (CODING)
- Python code is written using:
  • File handling
  • JSON module
  • Functions
  • Loops and conditionals

5. TESTING
- Manual testing is performed:
  • Adding multiple tasks
  • Completing tasks
  • Restarting the program to ensure data persistence
- Edge cases such as invalid input are handled.

6. DEPLOYMENT
- The application can be run locally using:
  python todo_app.py
- No external libraries required.

7. MAINTENANCE
- Future improvements can include:
  • Due dates
  • Task deletion
  • GUI or web version
  • User authentication
