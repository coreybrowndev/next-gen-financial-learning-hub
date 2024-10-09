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
  - Editing content is a core feature of the application. The system should allow an Administrator of the system to handle the modification of content including and/all content added to the system (such as courses, lessons, quizzes, and assignments). The content editing process must be simplified compared to the previous system that required manual script execution.
