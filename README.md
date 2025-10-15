# Movie Review API

A Django REST Framework–based API that allows users to register, log in, and post movie reviews.
Each review includes a title, content, rating, and creation date.
Users can view, create, update, or delete their own reviews while viewing others' publicly.

### Features 
- `User Authentication`: Register, log in, and log out.

- `Secure Reviews`: Only logged-in users can post or modify reviews.

- `RESTful Endpoints`: CRUD operations for reviews.

- `Permission Control`: Authenticated users can write; others can only read.

## Endpoints
To register
- `/api/register/` 
- POST
```json
{
  "username": "xxxxxx",
  "email": "xxxxx",
  "password": "xxxxxx"
}
```
To log in 
- `/api/login/`
- POST
```json
{
  "username": "abena",
  "password": "abenapassword123"
}
```
To create reviews
- `/api/reviews/`
- POST
```json
{
  "title": "Naruto",
  "content": "A mind-blowing experience.",
  "rating": 4
}
```
To get all reviews
- `/api/reviews/`
- GET

To update reviews 
- `/api/reviews/1/`
- PUT
```json
{
  "title": "Naruto",
  "content": "Still a great movie after rewatching!",
  "rating": 4
}
```
To delete a review 
- `/api/review/1/`
- DELETE
```json
{
  "username": "abena",
  "password": "abenapassword123"
}
```

To search a review 
- `/api/review/?search=Sollo`
- GET

To filter a rating 
- `/api/review/?rating=4`
- GET

---
