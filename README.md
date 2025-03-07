# mc_securisation_api
mc_securisation_api

```python
from models import UserInDB  
users = [
    UserInDB(username="jdoe", first_name="John", last_name="Doe", password="hashed_password123"),
    UserInDB(username="asmith", first_name="Alice", last_name="Smith", password="securepass456")
]
```python


```python
[
    {
        "username": "jdoe",
        "first_name": "John",
        "last_name": "Doe",
        "password": "hashed_password123"
    },
    {
        "username": "asmith",
        "first_name": "Alice",
        "last_name": "Smith",
        "password": "securepass456"
    }
]
```python
