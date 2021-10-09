# Instagram-API-Clone
It is a basic version of a RESTful API based on Instagram where we can
create user, get the users, create post and get post and get all posts of an
user.


## Description

A User has the Following details

    - Id
    - Name
    - Email
    - Password

A post has the Following details

    - Id
    - Caption
    - Image URL
    - Posted Timestamp

### Major Features

- **Feature 1-** Create an User using the details by the POST request
- **Feature 2-** Get an User using their ID by GET request
- **Feature 3-** Create a Post using the details by POST request
- **Feature 4-** Get a Post using the details of ID by GET request
- **Feature 5-** Get all Posts of  User using the the Unique ID of the User by GET request
- **Feature 6-** Impelmented Pagination to get all Posts of  User using the the Unique ID of the User by GET request

### Additonal Features

- Hashed to protect password so that it cannot be Reverse Engineered
- Implemented Thread security by Implementing Locks
- Fully Structured Code with code reusability
- Pagination for the list endpoint


eature 5-** Get all Posts of  User using the the Unique ID of the User by GET request
- **Feature 6-** Impelmented Pagination to get all Posts of  User using the the Unique ID of the User by GET request

### Additonal Features

- Hashed to protect password so that it cannot be Reverse Engineered
- Implemented Thread security by Implementing Locks
- Fully Structured Code with code reusability
- Pagination for the list endpoint

## Run Locally

Clone the project

```bash
  git clone https://github.com/ayan2809/Instagram-API-Clone
```

Install Dependencies
```bash
  git init test3
```

Run the Code

```bash
   go run instagram.go
```
