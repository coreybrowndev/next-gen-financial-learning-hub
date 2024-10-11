# Functional Requirements

## Group: Use Case 1 (UC1) - Administrator Creates Content
- **FR1: The system shall allow the Administrator to log in and access the content management dashboard.**  
  **Priority:** HIGH  
  **Use Case:** UC1  
  **Notes:** Ensures only authorized users can create content.

- **FR2: The system shall provide the Administrator with a button to trigger the "Add New Content" action.**  
  **Priority:** HIGH  
  **Use Case:** UC1  
  **Notes:** Allows the Administrator to easily initiate the content creation process.

- **FR3: The system shall provide a dropdown for selecting the type of content (course, lesson, quiz, assignment) to create.**  
  **Priority:** HIGH  
  **Use Case:** UC1  
  **Notes:** Enables flexibility in content creation based on type.

- **FR4: The system shall allow the Administrator to input details for the content based on the type selected.**  
  **Priority:** HIGH  
  **Use Case:** UC1  
  **Notes:** Supports the creation of various content formats with necessary details.

- **FR5: The system shall provide a save button that stores the newly created content in the database.**  
  **Priority:** HIGH  
  **Use Case:** UC1  
  **Notes:** Saves the newly created content securely in the system's database.

 - **FR6: Quizzes should generate a similar question if the original one is answered incorrectly.**  
  **Priority:** MEDIUM  
  **Use Case:** UC1  
  **Notes:** Allows User to be tested properly

- **FR7: The system shall add an entry of the new content to the version history log.**  
  **Priority:** MEDIUM  
  **Use Case:** UC1  
  **Notes:** Ensures that all created content is tracked with version history.

## Group: Use Case 2 (UC2) - Administrator Modifies Existing Content
- **FR1: The system shall allow the Administrator to log in and access existing content.**  
  **Priority:** HIGH  
  **Use Case:** UC2  
  **Notes:** Ensures only authorized users can modify existing course materials.

- **FR2: The system shall allow the Administrator to select an existing course and view its details.**  
  **Priority:** HIGH  
  **Use Case:** UC2  
  **Notes:** Facilitates content editing by allowing the selection of a specific course.

- **FR3: The system shall allow the Administrator to add, delete, or edit units, lessons, quizzes, and assignments within the selected course.**  
  **Priority:** HIGH  
  **Use Case:** UC2  
  **Notes:** Enables flexible editing of all aspects of the course.

- **FR4: The system shall update the version history log with each content modification.**  
  **Priority:** MEDIUM  
  **Use Case:** UC2  
  **Notes:** Tracks all content modifications to ensure accountability and traceability.

- **FR5: The system shall provide bulk editing features for quiz content.**  
  **Priority:** MEDIUM  
  **Use Case:** UC2  
  **Notes:** Improves efficiency by allowing multiple quiz questions to be edited at once.

- **FR6: The system shall maintain student performance metrics as historical data even after quiz content is modified.**  
  **Priority:** HIGH  
  **Use Case:** UC2  
  **Notes:** Guarantees integrity and availability of student performance data. 

## Group: Use Case 3 (UC3) - System Tracks Changes and Version History for Content
- **FR1: The system shall track every change made to content, including course, lesson, quiz, and assignment modifications.**  
  **Priority:** HIGH  
  **Use Case:** UC3  
  **Notes:** Ensures that all content changes are logged for future reference.

- **FR2: The system shall store a timestamp for each content modification.**  
  **Priority:** HIGH  
  **Use Case:** UC3  
  **Notes:** Provides a clear history of when changes were made.

- **FR3: The system shall update the version history log whenever the Administrator makes content changes.**  
  **Priority:** HIGH  
  **Use Case:** UC3  
  **Notes:** Automatically logs content changes to maintain version control.

- **FR4: The system shall allow the Administrator to view a detailed log of each version, including timestamps and specific content changes.**  
  **Priority:** MEDIUM  
  **Use Case:** UC3  
  **Notes:** Allows administrators to review the history of content changes for auditing purposes.

## Group: Use Case 4 (UC4) - Administrator Views Version History of Course Content
- **FR1: The system shall allow the Administrator to log in and access the version history of a course.**  
  **Priority:** HIGH  
  **Use Case:** UC4  
  **Notes:** Ensures only authorized users can view content version history.

- **FR2: The system shall display a list of all previous versions of the content, including timestamps.**  
  **Priority:** HIGH  
  **Use Case:** UC4  
  **Notes:** Displays all historical versions of the content for review.

- **FR3: The system shall allow the Administrator to select and view detailed information for any previous version.**  
  **Priority:** MEDIUM  
  **Use Case:** UC4  
  **Notes:** Allows the Administrator to inspect past versions of the content.

## Group: Use Case 5 (UC5) - Simplified Content Management
- **FR1: The system shall allow the Administrator to add, delete, or edit content (lessons, quizzes, etc.) through a simplified interface without needing to run scripts manually.**  
  **Priority:** HIGH  
  **Use Case:** UC5  
  **Notes:** Simplifies content management by eliminating the need for manual scripting.

- **FR2: The system shall automatically save all changes made to content.**  
  **Priority:** HIGH  
  **Use Case:** UC5  
  **Notes:** Ensures that all changes are securely saved without manual intervention.

- **FR3: The system shall update the version control log with all changes, including a timestamp.**  
  **Priority:** MEDIUM  
  **Use Case:** UC5  
  **Notes:** Tracks content modifications and ensures version control is maintained.

# Non-functional Requirements
- **NR1: The system shall maintain an uptime of 99.9% to ensure high availability for administrators.**  
  **Priority:** HIGH  
  **Notes:** Provides high reliability to ensure system access is uninterrupted.

- **NR2: The system shall support up to 5000 concurrent users without noticeable performance degradation.**  
  **Priority:** HIGH  
  **Notes:** Ensures scalability to handle multiple users efficiently.

- **NR3: The system shall load the content creation and editing interface in less than 2 seconds.**  
  **Priority:** MEDIUM  
  **Notes:** Provides fast system response to enhance user experience.

- **NR4: The system shall be compatible with all major browsers (Chrome, Firefox, Safari, Edge).**  
  **Priority:** MEDIUM  
  **Notes:** Ensures cross-browser compatibility for diverse user environments.

- **NR5: The system shall automatically back up all content changes and version logs daily.**  
  **Priority:** HIGH  
  **Notes:** Ensures data safety with regular backups.

- **NR6: The system’s user interface shall be intuitive and require minimal training for administrators to use effectively.**  
  **Priority:** MEDIUM  
  **Notes:** Provides a user-friendly interface to reduce the learning curve.



