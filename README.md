## 🧩 Part C — Student Attendance Portal (JSP + Servlet + JDBC)

**Objective:** Develop a student attendance portal using JSP (frontend) and Servlets (backend).

**Database Table:**
CREATE TABLE Attendance (
StudentID INT,
AttendanceDate DATE,
Status VARCHAR(10)
);

**Features:**

* JSP form for attendance input
* Servlet inserts data into the database
* Success message shown via JSP

**How to Run:**

1. Run `create_attendance_table.sql` in MySQL to create the Attendance table.
2. Update the database username and password in `AttendanceServlet.java`.
3. Copy the `PartC_AttendancePortal` folder into Tomcat’s `webapps` directory.
4. Start Tomcat and open `http://localhost:8080/PartC_AttendancePortal/attendance.jsp`.
5. 
