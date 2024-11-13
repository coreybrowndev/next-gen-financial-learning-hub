# Business Requirements

This BRD outlines the business needs for improving the current Learning Course Platform. The goal is to simplify course management, maintain current technology with Tailwind CSS and React, and preserve student metrics, while allowing for flexible content changes with version control.

## BR1: Store and track changes made to course content for historical tracking purposes while maintaining existing student metric data
The client emphasized in the discovery meeting that a version control feature must be implemented to track changes made to course content within the new CMS, ths will allow for historical viewing of content changes as they occur over time. The system must maintain student performance metrics even when quiz or course content is modified or removed. When administrators make edits or delete content related to quizzes or courses, all student metrics (e.g., quiz scores, course completions) should remain unaffected. The preservation of metrics is crucial for making sure accurate reporting and progress tracking for both instructors and students are maintained, regardless of changes made to course content, even if the original course is deleted.

## BR2: Automate the existing course content management system
In the discovery meeting, the client mentioned that the system must support a simplified method for creating new content and making changes to existing content. When managing the content, the system must allow for flexible modification of content including the creation, the deletion, and editing of already existing content. This is neccessary to reduce the current manual, time-consuming process of editing the current JSON based file which has all of the content stored in it. Administrators should be able to make flexible content changes without running scripts manually, the current process is slow as it requires executing a script each time to publish changes to the content.


