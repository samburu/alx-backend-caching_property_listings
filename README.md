# alx-backend-caching_property_listings
A Django property listing app with Dockerized PostgreSQL and Redis caching.

## Setup
Build and start services:
```
docker-compose up -d
```
Install Python dependencies:
```
pip install django django-redis psycopg2-binary
```
Run migrations:
```
python manage.py migrate
```
Start the Django server:
```
python manage.py runserver
```
## Services
PostgreSQL: Database for property listings
Redis: Cache backend for Django
## Features
Property model: title, description, price, location, created_at
Multi-level caching (to be implemented)