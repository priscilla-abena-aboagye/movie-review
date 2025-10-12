# Movie Review API

A Django REST Framework–based API that allows users to register, log in, and post movie reviews.
Each review includes a title, content, rating, and creation date.
Users can view, create, update, or delete their own reviews while viewing others’ publicly.

### Features 
- `User Authentication`: Register, log in, and log out.

- `Secure Reviews`: Only logged-in users can post or modify reviews.

- `RESTful Endpoints`: CRUD operations for reviews.

- `Permission Control`: Authenticated users can write; others can only read.

## Acomplished so far
### 1
- Set up Django and Django REST Framework  
- Created project `review_api` and app `review`  
- Registered apps in settings.py  
- Confirmed server runs successfully

### 2
- Created `Review` model and added the fields 
- Registered Review model in Django admin  

### 3
- serialization and authentication
- allow users CRUD
- CRUD operations for movie reviews
- Authenticated users can post/edit their reviews