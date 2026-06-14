# usermanagement_platform

A Django RESTful API platform for user management.

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Endpoints

- `GET /api/users/`
- `POST /api/users/`
- `GET /api/users/{id}/`
- `PUT /api/users/{id}/`
- `PATCH /api/users/{id}/`
- `DELETE /api/users/{id}/`

Authentication: unauthenticated users can read, authenticated users can modify.
