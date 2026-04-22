classDiagram
    class User {
        +String username
        +String email
        +login()
        +createTask()
    }
    class Task {
        +String title
        +String status
        +Date dueDate
        +updateStatus()
    }
    User "1" -- "*" Task : manages
