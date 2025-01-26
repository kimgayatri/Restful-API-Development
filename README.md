# RESTful API for Library Inventory System

## Base URL:
http://localhost:3000/api/books

## Endpoints:

| Method | Endpoint      | Description              |
|--------|---------------|--------------------------|
| GET    | /api/books    | Get all books             |
| GET    | /api/books/:id| Get a book by ID          |
| POST   | /api/books    | Add a new book            |
| PUT    | /api/books/:id| Update a book             |
| DELETE | /api/books/:id| Delete a book             |

## Example Requests

### GET /api/books
Response:
```json
[
  {
    "_id": "60a7df123e7a5900d6e080b3",
    "title": "The Great Gatsby",
    "author": "F. Scott Fitzgerald",
    "isbn": "1234567890",
    "publishedDate": "1925-04-10"
  }
]