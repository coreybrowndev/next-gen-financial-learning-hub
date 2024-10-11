# Actors
- Administrator
  - Responsible for managing the system, has access to all features, including course creation, content updates, and version control.


# Use Cases
- UC1: An individual Administrator creates content
  - [BR2](/Design/BusinessRequirements.md#br2-simplified-course-content-management-with-version-control)
  - Administrator
  - Flow: 
    - Administrator logs into the system.
    - Administrator selects button to trigger add new content action.
    - Administrator chooses the content type from the dropdown to create.
    - Administrator completes content field(s) respective to selected content type.
    - Administrator selects button to save content to system 
    - The system adds a new entry of the created content to the version history log of the content.
  - Creating content is the core feature of the application. The system should allow an Administrator of the system to handle the flexible creation of content (such as courses, lessons, quizzes, and assignments). The content management process must be simplified compared to the previous system that required manual script execution.
 
- UC2: An individual Administrator makes changes to existing content
  - [BR2](/Design/BusinessRequirements.md#br2-simplified-course-content-management-with-version-control)
  - Administrator
  - Flow: 
    - Administrator logs into the system.
    - Administrator selects existing course to view its details.
    - (Optional) Administrator may choose to add new unit.
    - (Optional) Administrator may choose to delete unit.
    - (Optional) Administrator may choose to edit lesson content.
    - (Optional) Administrator may chooses quiz to edit.
    - The system adds a new entry of the changes to the version history log.
  - Editing content is a core feature of the application. The system should allow an Administrator of the system to handle the modification of content including all content added to the system (such as courses, lessons, quizzes, and assignments). The content editing process must be simplified compared to the previous system that required manual script execution.
 
- UC3: System tracks changes and version history for modified content within the system
  - [BR1](/Design/BusinessRequirements.md#br2-simplified-course-content-management-with-version-control)
  - Administrator
  - Flow:
    - Precondition: Administrator is logged into the system and viewing content.
    - Administrator selects a course to edit.
    - Administrator makes changes to the content (e.g., modifying lessons, quizzes, or units)..
    - The system tracks all changes and updates the version history log with a new entry for each edit.
    - (Optional) Administrator can view the version history of the course, with timestamps and the specific changes made.
    - Postcondition: The course content is updated, and the change history is logged.
  - Tracking changes to content is a core feature of the application. The system should allow an Administrator of the system to make changes to content, and upon creating changes store specific information regarding the changes made and timestamps when those changes were executed.
 
- UC4: An Administrator can view the version history of course content
  - [BR1](/Design/BusinessRequirements.md#br2-simplified-course-content-management-with-version-control)
  - Administrator
  - Flow:
    - Precondition: Course content has undergone previous modifications.
    - Administrator logs into the system.
    - Administrator selects a course from the list of courses.
    - Administrator chooses to view the version history of the course.
    - The system displays a list of previous versions with timestamps and changes made.
    - Administrator can select any version to view details about.
  - Viewing changes to content is an important feature of the application. The system should allow an Administrator of the system to view historical changes made to content, viewing specific and relevant information about the changes that were made to the content.
 
- UC5: Simplified Content Management
  - [BR2](/Design/BusinessRequirements.md#br2-simplified-course-content-management-with-version-control)
  - Administrator
  - Flow:
    - Precondition: Administrator is logged into the system.
    - Administrator selects a course to create or edit.
    - Administrator modifies the content without the need to run scripts manually.
    - The system allows the Administrator to add, delete, or edit lessons and quizzes in a simplified interface.
    - The system automatically saves the changes and updates the content version control log.
    - Postcondition: The content is updated in a simplified manner, with no manual script execution required.
  - Simplified content management is a core important feature of the application. The system should allow an Administrator to manage content in a simplified manner compared to the exisiting system. 
