# RESTFUL API DEVELOPMENT

**Company**: CODTECH IT SOLUTIONS

**NAME**: GAYATRI SAINATH NEHE

**INTERN ID**: CT08IAB

**DOMAIN**: SOFTWARE DEVELOPMENT

**BATCH DURATION**: January 10th, 2025 to February 10th, 2025

**MENTOR NAME**: NEELA SANTOSH KUMAR

# ENTER DESCRIPTION OF TASK PERFORMED NOT LESS THAN 500 WORDS

## Base URL:
http://localhost:3000/api/books

# OUTPUTS
![Image](https://github.com/user-attachments/assets/4d889375-3bdf-486c-b8eb-e586adfaf9e1)


![Image](https://github.com/user-attachments/assets/43de8c6a-37f5-4b67-825e-c820d16a77a2)


![Image](https://github.com/user-attachments/assets/4b7411de-c400-4aec-9e1d-2128631d385c)

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



