# .NET/C# Mobile Assignment Overview

**Objective:** Create a mobile application using .NET MAUI that interacts with a RESTful API, implements advanced features such as search, filtering, and data visualization, and includes comprehensive unit tests.

## Assignment Details

### Task 1: Mobile Application Development
- **Create a mobile application** that allows users to manage a list of tasks with the following features:
  - **User Authentication:** Implement OAuth2 authentication using a third-party provider (e.g., Google or GitHub).
  - **Task Management Interface:** Users can add, edit, delete, and view tasks. Each task should include:
    - Title
    - Description
    - Due Date
    - Priority Level (Low, Medium, High)
  
- **Search and Filtering:**
  - Implement a search feature that allows users to find tasks by title or description.
  - Provide filtering options based on:
    - Due date (e.g., today, this week, overdue)
    - Priority level (e.g., Low, Medium, High)

- **Data Visualization:**
  - Create a dashboard that displays statistics about tasks using charts or graphs (consider using a library like Microcharts). Include visual representations for:
    - Total number of tasks
    - Number of completed tasks
    - Number of overdue tasks
    - Distribution of tasks by priority level

### Task 2: RESTful API Integration
- **Develop a REST API** using ASP.NET Core that supports the following endpoints:
  - `GET /tasks` - Retrieve all tasks for the authenticated user.
  - `POST /tasks` - Create a new task.
  - `PUT /tasks/{id}` - Update an existing task.
  - `DELETE /tasks/{id}` - Delete a task.

- **NOTE: Database Interaction:** Use Entity Framework Core with an in-memory database for simplicity. Ensure proper handling of database connections and CRUD operations.

### Task 3: Unit Testing
- Write unit tests for both the mobile application and the API using xUnit or NUnit.
- Ensure that tests cover:
  - API endpoint responses.
  - Business logic related to task management, search functionality, and filtering.

### Task 4: Documentation
- Provide clear documentation on how to set up and run both the mobile application and the API.
- Include a brief explanation of the design choices made during development.

## Evaluation Criteria
1. **Code Quality:** Adherence to C# coding standards, readability, and maintainability.
2. **Functionality:** The application should meet all specified requirements and function correctly without errors.
3. **Advanced Features Implementation:** Successful integration of search/filtering and data visualization features.
4. **Testing:** Coverage of critical paths in both the application and API through unit tests.
5. **Documentation:** Clarity and completeness of setup instructions and design rationale.

## Submission Instructions
- Candidates should submit their code repository (e.g., GitHub) along with any necessary files to run the applications.
- Include a README file that outlines the project structure, setup instructions, and any additional notes.
- This assignment is time-bounded to 5 days.