# Actors
- Administrator
  - Responsible for managing the system, including adding/removing courses, managing course content, and ensuring data integrity.
  - Has access to all features, including course creation, content updates, and version control.
- Instructor
  - Manages the course and manages the students assigned to their course, including viewing student metrics.
  - Limited access compared to the Admin, focus on student interactions and course management.
- Student
  - Participates in courses by viewing content, completing quizzes, and tracking their performance metrics.
  - Can only view their own data, and cannot modify course content or interact with the admin features.

# Use Cases
- UC1: Modify Course Content
  
| **Name of Use Case:**       | Modify Course Content                           |
|-----------------------------|---------------------------------------------|
| **Description:**             | Administrator applies edits to an existing course and/or quiz or creates a new course or quiz  |
| **Actors:**                  | Administrator                                    |

Flow: 
- The instructor logs into the system and selects the course to edit.
- The instructor adds or modifies quiz questions or learning content.
- The system saves the updates made to the course content and stores the changes in the database.
- The system adds a new entry of the edit to the version history log of the content.

[Link to Business Requirement](/Design/BusinessRequirements.md#br2-simplified-course-content-management-with-version-control)



- UC2: Student Performance Metrics Preservation
  
| **Name of Use Case:**       | Student Performance Metrics Preservation                           |
|-----------------------------|---------------------------------------------|
| **Description:**             | Administrator modifies or deletes content related to a specific quiz, which was previously completed by student.  |
| **Actors:**                  | **Primary**: Administrator : **Secondary**: Student                                    |

Flow: 
- The Administrator modifies or deletes content related to a specific quiz.
- The system checks for associated student metrics related to the quiz.
- The system maintains student metrics, making sure historical data remains intact even after content changes.
- The updated course content is saved, and the student metrics are maintained unedited as historical data in the reports.

[Link to Business Requirement](/Design/BusinessRequirements.md#br3-persistance-of-current-student-metrics)
