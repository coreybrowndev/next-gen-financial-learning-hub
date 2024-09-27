# Business Requirements

A more simplified system for managing existing and new courses within the current Learning Course Platform, 

## BR1: Tailwind CSS and React Integration for Front-end
The system must use **Tailwind CSS** for styling and **React** for the front-end. Tailwind is currently used in the existing system for styling the course content that lives within a database, the current system pulls content from the database already pre-styled. The business wants to maintain this technology as it is already being utilized. In addition, React JS is a widely used technology for creating web application systems, it uses a component-based structure and renders these various components to create the UI quickly, reducing development time.

## BR2: Simplified Course Content Management with Version Control
The system must support a simplified method for making changes to the course content. When managing the content of the various quizzes and courses, the system must allow for flexible content changes. This is neccessary to reduce the current manual, time-consuming process of editing the current JSON based file which has all of the content stored in it. The current process is slow as it requires executing a script each time to publish changes to the content. The new system will provide version history features of content changes overtime.
  
## BR3: Persistance of current student metrics
When managing quizzes and courses, the system must preserve student performance metrics while also allowing for flexible content changes. When potentially deleting or modifying content related to quizzes and/or courses, the system should maintain metrics regardless of content edits. This is vital for maintaining accurate records for both instructors and students, if content is removed from the system, student metrics should remain unaffected, preserving historical data in the system.
