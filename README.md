## Student Spring Boot Application

### APIs

## API Endpoints

### List All Students

- **URL:** `/api/students`
- **Method:** `GET`
- **Description:** Retrieves a list of all students.
- **Response:**

```json
  [
    {
      "id": 1,
      "name": "John Doe",
      "age": 22
    },
    {
      "id": 2,
      "name": "Jane Smith",
      "age": 24
    }
  ]
```

### Get Student by ID

- **URL:** `/api/students/{id}`
- **Method:** `GET`
- **Description:** Retrieves a student by their ID.
- **Response:**

```json
{
  "id": 1,
  "name": "John Doe",
  "age": 22
}

```

### Create New Student

- **URL:** `/api/students`
- **Method:** `POST`
- **Description:** Creates a new student.
- **Request:**
    
```json
    {
    "name": "John Doe",
    "age": 22
    }
```

- **Response:**

```json
{
  "id": 1,
  "name": "John Doe",
  "age": 22
}
```

### Update Student

- **URL:** `/api/students/{id}`
- **Method:** `PUT`
- **Description:** Updates an existing student.
- **Request:**

```json
{
  "name": "Jane Smith",
  "age": 24
}
```

- **Response:**

```json
{
  "id": 2,
  "name": "Jane Smith",
  "age": 24
}
```


### Delete Student

- **URL:** `/api/students/{id}`
- **Method:** `DELETE`
- **Description:** Deletes a student by their ID.
- **Response:**

```json
{
  "id": 2,
  "name": "Jane Smith",
  "age": 24
}
```
