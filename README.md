# RESTful-APIs-with-Python-3-and-Flask

This is a RESTful APIs using a combination of Python 3 and Flask.

## Features

- Postman [API Documenation](https://documenter.getpostman.com/view/24066287/2s8YYEMPRX)
- HTTP methods (*GET, POST, PUT, DELETE* request) --> CRUD operations used for simulation test to RESTful Services
- Endpoints:  (used for communication and data transfer)
  - GET/super_simple
  - GET/not_found
  - GET/parameters
  - GET/url_variables
  - GET/planets
  - GET/retrieve_password
  - GET/planet_details
  - POST/register
  - POST/login
  - POST/add_planet
  - PUT/update_planet
  - DELETE/remove_planet
- Authorization bearer token used for generating token authorization that is a very long and unique token

- | Success and Error codes | Status |
  | --- | --- |
  | `200` | OK |
  | `201` | Created |
  | `202` | Accepted |
  | `401` | Unauthorized |
  | `404` | Not found |
  | `409` | Conflict |

## Database Model
| SQLite | DB Browser |
| --- | --- |
| *User* | planetary's users |
| *Planet* | planet's details |

###### **The application and SQLite database are used only for testing. As of now, they are not allowed to push into production.*

## Other Site
Mailtrap.io. : Email testing, automate test flows to retrieve password
