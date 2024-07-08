Book Database
====

The books database is a CRUD app that uses an SQLite database for storing information about books (title, author, publication year, and ISBN). Entries in the db can be viewed, updated, sorted, deleted, and reinserted. Data is persistent and will be saved when application is closed and/or reopened.

SQLite is used to connect to the database and define its functionalities. Tkinter is used to create the simple and intuitive user interface.

Available Actions
---
- View all
- Search entry (fill corresponding field(s) to be used as search keys)
- Add entry (fill in fields, duplicate entries will be permitted)
- Update (select entry and modify necessary fields)
- Delete

Installing, Compiling and Running
---
- To build books database from the command line tkinter must be up-to-date and supported
   Warning: new versions of MacOS may not support tkinter. App should be run from VSCode or other IDE with tkinter support.
- If all modules are supported, run from the command line with ```python database.py```
- Alternatively, run from your IDE with its ```build and run``` option
- Application will open with your entries displayed
- When adding/modifying entries, press ```view all``` to see updated contents of SQLite db
