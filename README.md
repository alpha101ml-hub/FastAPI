# FastAPI
FastAPI -> Fast Application Programming Interface

Backend Framework - running on same type of server and essentially controlling the data.

API: facilitates the access and control of data.

##### https://training.devlaunch.us/tim?video=123
##### https://training.devlaunch.us = Domain
##### /tim = Path/Endpoint
##### ?video=123 = Query Parameter

### API Reference
#### /books
| HTTP Method | Endpoint | Description |
| :--- | :--- | :--- |
| **GET** | `/books` | List of all the books in the database |
| **GET** | `/books/{bookId}` | Retrieves a book based on their ID |
| **POST** | `/books` | Create a book |
| **PUT** | `/books/{bookId}` | Method to update a book |
| **DELETE** | `/books/{bookId}` | Delete a book based on their ID |


#### Think of an API as a backend server that handles all data operations-creating, reading, updating and deleting.
