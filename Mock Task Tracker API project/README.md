# Project: Task Tracker API (Mock)
This project was completed as part of the **Postman API Beginner Learning Pathway**. It demonstrates my ability to design a functional API environment, simulate server behavior, and write automated validation scripts.

## 🚀 Key Features Implemented
*   **Full CRUD Suite:** Configured GET, POST, PUT, and DELETE endpoints to manage tasks.
*   **Mock Server Integration:** Utilized a Postman Mock Server to simulate a live backend, allowing for realistic request/response cycles.
*   **Example Responses:** Created saved examples for each status code (200 OK, 201 Created, 204 No Content) to facilitate frontend-backend contract testing.
*   **Automated Testing:** Developed **post-response test scripts** (JavaScript) to validate status codes, response times, and JSON body structure.

## 🧪 API Endpoints Tested

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| **GET** | `/tasks` | Retrieves all tasks stored in the mock service. |
| **POST** | `/tasks` | Creates a new task (Validates JSON body & required fields). |
| **PUT** | `/tasks/:id` | Updates an existing task using path parameters and variables. |
| **DELETE** | `/tasks/:id` | Removes a task and validates a `204 No Content` response. |

## 🛠️ How to Review
1. Import the `Task_Tracker_Collection.json` file into Postman.
2. Ensure the **Task Tracker Environment** is selected (to enable `baseURL` and `taskId` variables).
3. Open the **Scripts** tab on any request to view my JavaScript validation logic.

---
*This project serves as a practical demonstration of my readiness for a Junior QA / API Tester role.*
