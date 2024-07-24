# api_project

## Description

The api_project is an api built using the Django framework. This project serves as a book api.

## Features and later additional features

- User authentication and authorization
- CRUD operations for books, posts, blogs etc
- Responsive design using Bootstrap
- REST API for interacting with the application programmatically


## Requirements

- Python 3.x
- Django 3.x or later
- MySQL

## Installation

### 1. Clone the repository

```sh
git clone https://github.com/tofa-eM365/api_project.git
cd api_project
```

### 2. Create and activate a virtual environment

```sh
python -m venv env
```

### Windows

```sh
env\Scripts\activate
```
### macOS/Linux

```sh
source env/bin/activate
```

### 3. Install dependencies
```sh
pip install -r requirements.txt
```

### 4. Configure the database

Update the DATABASES setting in api_project/api_project/settings.py with your database configuration.

### 5. Run migrations

```sh
python manage.py migrate
```
### 6. Run the development server
```sh
python manage.py runserver

Visit http://127.0.0.1:8000/ in your web browser to see the application running.
```

### Usage
API Endpoints
GET /api/model/ - List all items
POST /api/model/ - Create a new item
GET /api/model/<id>/ - Retrieve an item
PUT /api/model/<id>/ - Update an item
DELETE /api/model/<id>/ - Delete an item


### Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit your changes
5. Push to the branch
6. Open a pull request

### License
This project is licensed under the MIT License. See the LICENSE file for more details.

### Acknowledgements
Django Documentation
ALX Software Engineering
