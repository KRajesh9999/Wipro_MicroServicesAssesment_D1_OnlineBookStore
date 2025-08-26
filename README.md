# Online Book Store RESTful API - ASP.NET Core

## Problem Statement
This project is about building and testing a RESTful API for an **online book store** using **ASP.NET Core**.  
The API provides **CRUD (Create, Read, Update, Delete)** operations on books and authors, following **RESTful principles**.  
---

## Features
- CRUD operations for **Books** and **Authors**
- RESTful URI routing with **attribute routing**
- Associations between **Books** and **Authors**
- In-memory or SQLite database
- Proper **HTTP status codes** and error handling
- JSON-based responses
- Debugging with **Postman** and **Fiddler**
---

## API Endpoints

### Books
|--------|----------------------|-------------------------|
| GET    | `/api/books`         | Get all books           |
| GET    | `/api/books/{id}`    | Get book by ID          |
| POST   | `/api/books`         | Create a new book       |
| PUT    | `/api/books/{id}`    | Update a book           |
| DELETE | `/api/books/{id}`    | Delete a book           |

### Authors
|--------|---------------------------------|-------------------------|
| GET    | `/api/authors`                  | Get all authors         |
| GET    | `/api/authors/{id}`             | Get author by ID        |
| POST   | `/api/authors`                  | Create new author       |
| PUT    | `/api/authors/{id}`             | Update author           |
| DELETE | `/api/authors/{id}`             | Delete author           |
| GET    | `/api/authors/{authorId}/books` | Get books by author     |

---

## Setup Instructions
1. Clone repo:
   ```sh
   git clone https://github.com/your-username/bookstore-api.git
   cd bookstore-api
## 2. Run the project:
dotnet run

## 3. API will be available at:

https://localhost:5001/api/books
https://localhost:5001/api/authors

---

Services Snaps:
1. Available Servies:
   <img width="1912" height="956" alt="Serivices" src="https://github.com/user-attachments/assets/340a7e43-f932-4925-a717-7190a14de38a" />

2. Get Authors
   <img width="1916" height="955" alt="GetAuthors" src="https://github.com/user-attachments/assets/cc8c6f9a-fe15-49ad-bc58-c54f3880b837" />

3. Get Authors by ID:
   <img width="1906" height="928" alt="GetAuthorsById" src="https://github.com/user-attachments/assets/25148c45-64b7-4731-b7c3-de861baea60f" />

4. Post Authors:
   <img width="1912" height="746" alt="PostAuthors" src="https://github.com/user-attachments/assets/3b2d523d-11db-483f-8e41-69c3c7a55027" />

5. Get Books:
   <img width="1919" height="754" alt="GetBooks" src="https://github.com/user-attachments/assets/9a9ca6f1-a815-45fe-a5a0-33dfb9648e51" />

6. Post Books:
   <img width="1919" height="949" alt="PostBooks" src="https://github.com/user-attachments/assets/d0837da7-d383-4e37-8518-8a2164ee02e9" />

