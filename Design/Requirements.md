# Functional Requirements

## Group: Use Case 1 (UC1) - Modify Course Content

- **FR1: The system shall allow the Administrator to log in to modify course content.**  
  **Priority:** HIGH  
  **Use Case:** UC1  
  **Notes:** Ensures only authorized users can make changes to course materials.

- **FR2: The system shall allow the Administrator to add or modify quiz questions and learning content.**  
  **Priority:** HIGH  
  **Use Case:** UC1  
  **Notes:** Facilitates course management and ensures up-to-date content.

- **FR3: The system shall save all updates made to course content in the database.**  
  **Priority:** HIGH  
  **Use Case:** UC1  
  **Notes:** Ensures data integrity and that all modifications are recorded.

- **FR4: The system shall maintain a version history log of the content edits.**  
  **Priority:** MEDIUM  
  **Use Case:** UC1  
  **Notes:** Allows tracking of changes and rollback capabilities if needed.

- **FR5: The system shall allow bulk editing of quiz questions for efficiency.**  
  **Priority:** MEDIUM  
  **Use Case:** UC1  
  **Notes:** Facilitates quicker updates to quizzes with multiple questions.

## Group: Use Case 2 (UC2) - Student Performance Metrics Preservation

- **FR5: The system shall allow the Administrator to modify or delete quiz content.**  
  **Priority:** HIGH  
  **Use Case:** UC2  
  **Notes:** Provides flexibility in course management while ensuring metrics are preserved.

- **FR6: The system shall check for associated student metrics related to any modified or deleted quiz content.**  
  **Priority:** HIGH  
  **Use Case:** UC2  
  **Notes:** Ensures that historical performance data is not lost.

- **FR7: The system shall maintain student performance metrics as historical data even after quiz content is modified.**  
  **Priority:** HIGH  
  **Use Case:** UC2  
  **Notes:** Guarantees integrity and availability of student performance data.

- **FR8: The system shall allow administrators to generate reports on student performance metrics, including historical data.**  
  **Priority:** MEDIUM  
  **Use Case:** UC2  
  **Notes:** Provides valuable insights for instructors and administrators.

---

# Non-functional Requirements

- **NR1: The system shall ensure an uptime of 99.9% over a year.**  
  **Priority:** HIGH  
  **Notes:** Ensures reliability for users accessing the system at any time.

- **NR2: The system shall support up to 5000 concurrent users without performance degradation.**  
  **Priority:** HIGH  
  **Notes:** Ensures scalability during peak usage periods.

- **NR3: The system shall provide a response time of under 2 seconds for any content modification action.**  
  **Priority:** MEDIUM  
  **Notes:** Enhances user experience by ensuring quick feedback during course management.

- **NR4: The system shall be compatible with major web browsers (Chrome, Firefox, Safari, and Edge).**  
  **Priority:** MEDIUM  
  **Notes:** Ensures accessibility for a wide range of users.

- **NR5: The system shall provide regular backups of course content and student metrics at least once a day.**  
  **Priority:** HIGH  
  **Notes:** Ensures data integrity and disaster recovery.


