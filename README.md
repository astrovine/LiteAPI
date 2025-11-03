My submission for second semester exams. A CRUD, RESTful API for managing users, courses, and enrollments.


## Features

  * **User Management:** Create, Read, Update, Delete, and Deactivate users.
  * **Course Management:** Create, Read, Update, Delete, and Close enrollment for courses.
  * **Enrollment:** Enroll active users into open courses, prevent duplicate enrollments, and mark courses as completed.
  * **Reporting:** View all enrollments, enrollments for a specific user, or users enrolled in a specific course.
  * **Validation:** **Pydantic** for data validation.


### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/astrovine/-Lite-API
    cd lite-API
    ```

2.  **Create and activate a virtual environment** (recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On macOS/Linux
    # venv\Scripts\activate   # On Windows
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

### Running the API

Start the server using `uvicorn`:

```bash
uvicorn main:app --reload
```

The API will now be running at `http://127.0.0.1:8000`.
