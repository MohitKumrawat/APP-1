# DJANGO CALLER-ID

## Runserver
```
python manage.py runserver
```

## Test the API

### To search a contact by phone
```
Private Route: http://localhost:8000/?phone=345678
Request Type: GET
```

### To mark a contact as SPAM
```
Private Route: http://localhost:8000/mark-spam/345678/
Request Type: POST
Data:
    {
    }
```

### To view all the contacts
```
Public Route: http://localhost:8000/global-view/
Request Type: GET
```