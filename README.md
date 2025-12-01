## Employee Search Database Project

This is a simple Java Swing application that connects to a MySQL database and lets you:

- **Load departments and projects** from a database (for example, a `COMPANY` database).
- **Search employees** by selected departments and/or projects, with optional **NOT** filters.
- View matching employees in an on-screen text area.

---

## Project Files

- **`EmployeeSearchFrame.java`** – Main GUI window (frame), buttons, lists, and message popups.
- **`DatabaseConfig.java`** – Reads `database.prop` and creates a JDBC connection.
- **`DatabaseQueries.java`** – Contains methods to:
  - Load all department names
  - Load all project names
  - Search employees by department/project filters
- **`database.prop`** – Stores database connection settings (URL, user, password, driver).
- **`lib/mysql-connector-j-9.5.0.jar`** – MySQL JDBC driver used by the Java app.
