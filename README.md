# Vanilla Web Stack

A development environment using Docker with PHP, PostgreSQL, and Adminer.

## Stack
- PHP 8.2 with Apache
- PostgreSQL 15
- Adminer for database management

## Setup
1. Install Docker Desktop
2. Clone this repository
3. Run `docker-compose up --build`
4. Access:
   - Web app: http://localhost:8080
   - Adminer: http://localhost:8081

## Development
Place your PHP, HTML, CSS, and JavaScript files in the `src` directory.

## Database Connection
- Host: db
- Database: myapp
- Username: webuser
- Password: secret
- Port: 5432
