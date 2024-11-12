## Administrator
- Manages course content, oversees system functionality, and generates reports. Administrators can modify course content and track version history of changes.
## Instructor
- Manages courses and views student metrics related to performance. Instructors are responsible for course-specific content.
## Student
- Enrolls in courses, completes quizzes, and tracks personal performance metrics.
## Course
- Represents a specific educational course containing units, sections, lessons, and quizzes for enrolled students.
## Quiz
- Contains questions related to the course and keeps track of students who have completed it.
## Question
- Represents individual questions within a quiz, with answer options.
## PeforamnceMetric
- Tracks the performance of a student on a specific quiz.
## VersionHistory
- Maintains a log of changes made to the course content for tracking purposes.


# Domain Model 

```mermaid
classDiagram
    class Administrator {
        +String adminId
        +String name
        +String email
        +login()
        +modifyCourseContent()
        +viewReports()
    }

    class Instructor {
        +String instructorId
        +String name
        +String email
        +manageCourses()
        +viewStudentMetrics()
    }

    class Student {
        +String studentId
        +String name
        +String email
        +viewCourseContent()
        +completeQuizzes()
        +trackPerformanceMetrics()
    }

    class Course {
        +String courseId
        +String title
        +String description
        +List<Quiz> quizzes
        +List<Student> enrolledStudents
    }

    class Quiz {
        +String quizId
        +String title
        +List<Question> questions
        +List<Student> completedBy
    }

    class Question {
        +String questionId
        +String content
        +List<String> answerOptions
    }

    class PerformanceMetric {
        +String metricId
        +String studentId
        +String quizId
        +int score
        +Date completionDate
    }

    class VersionHistory {
        +String versionId
        +String courseId
        +String changesMade
        +Date timestamp
    }

    Administrator --> Course : manages
    Administrator --> VersionHistory : tracks
    Instructor --> Course : manages
    Student --> Course : enrolls
    Student --> Quiz : completes
    Quiz --> Question : consists of
    Quiz --> PerformanceMetric : generates
    Course --> Quiz : contains
    PerformanceMetric --> Student : records for


