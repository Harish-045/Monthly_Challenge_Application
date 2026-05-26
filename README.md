# Monthly Challenges REST API

A Spring Boot REST API project to store and manage monthly challenges.

Architecture follows:
Browser → Controller → Service → Repository → Database

## Features

- Add monthly challenge
- View all challenges
- View challenge by month
- Update challenge
- Delete challenge

## Technologies Used

- Java
- Spring Boot
- Spring Web
- Spring Data JPA
- MySQL
- Maven

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /challenges | Get all challenges |
| GET | /challenges/{month} | Get challenge by month |
| POST | /challenges | Add challenge |
| PUT | /challenges/{id} | Update challenge |
| DELETE | /challenges/{id} | Delete challenge |

## Example JSON

```json
{
  "month":"January",
  "description":"Complete DSA Sheet"
}
```

## Run Project

1. Clone repository

```bash
git clone <https://github.com/Harish-045/Monthly_Challenge_Application>
```


2. Run application

## Author

Harish
