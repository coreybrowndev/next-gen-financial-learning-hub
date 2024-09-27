# Business Requirements

This BRD outlines the business needs for improving the current Learning Course Platform. The goal is to simplify course management, maintain current technology with Tailwind CSS and React, and preserve student metrics, while allowing for flexible content changes with version control.

## BR1: Tailwind CSS and React Integration for Front-end
The system must use **Tailwind CSS** for styling and **React** for the front-end. Tailwind is currently used in the existing system for styling the course content that lives within a database, the current system pulls content from the database already pre-styled. The business wants to maintain this technology as it is already being utilized. In addition, React JS is a widely used technology for creating web application systems, it uses a component-based structure and renders these various components to create the UI quickly, reducing development time.

## BR2: Simplified Course Content Management with Version Control
The system must support a simplified method for making changes to the course content. When managing the content of the various quizzes and courses, the system must allow for flexible and quick content changes. This is neccessary to reduce the current manual, time-consuming process of editing the current JSON based file which has all of the content stored in it. Administrators should be able to make flexible content changes without running scripts manually, the current process is slow as it requires executing a script each time to publish changes to the content. A version control feature must be implemented to track changes made to course content, allowing for historical viewing of content changes over time.
  
## BR3: Persistance of current student metrics
The system must maintain student performance metrics even when quiz or course content is modified or removed. When administrators edit or delete content related to quizzes or courses, all student metrics (e.g., quiz scores, course completions) should remain unaffected. The preservation of metrics is crucial for making sure accurate reporting and progress tracking for both instructors and students are maintained, regardless of changes made to course content, even if the original course content is deleted. 
