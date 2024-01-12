# AgileNestApi

AgileNestApi is a task/project management API built with Laravel, Bootstrap for the front-end, and JSON for response format. It leverages Laravel Sanctum for security and includes middleware for handling CRUD operations.

## Installation

Follow these steps to get AgileNestApi up and running on your local environment:

### Prerequisites

1. **Composer:**
   - Install [Composer](https://getcomposer.org/) if you haven't already.

2. **XAMPP or Similar:**
   - Install [XAMPP](https://www.apachefriends.org/index.html) or another web server with PHP and MySQL.

### Setting Up Laravel

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/AgileNestApi.git**
   
**Customization**
**Frontend:**
Customize the Bootstrap-based frontend located in the resources/views directory.

**API Routes:**
Customize the API routes in routes/api.php to match your specific requirements.

**Usage**
AgileNestApi is now running locally. You can use tools like Postman to interact with the API endpoints.

**API Endpoints**
**GET /tasks:** Get all tasks.
**GET /tasks/{id}:** Get a specific task.
**POST /tasks:** Create a new task.
**PUT /tasks/{id}:** Update a task.
**DELETE /tasks/{id}:** Delete a task.

**Security**
AgileNestApi uses Laravel Sanctum for API authentication. Ensure you have configured your sanctum properly for secure API access.
