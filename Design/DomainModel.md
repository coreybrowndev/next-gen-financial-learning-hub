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

