# E-commerce API

**HOST**: http:localhost:8000

### Create account API

**URL** : `/platform/create`

**Method** : `POST`

**Body request**

```json
{
	"email": "email@gmail.com",
    "password": "123456",
    "name": "Visa"
}
```

## Success Response

**Code** : `200 Success`

**Content example**

```json
    {"Success": "Account is created successfully!"}
```

## Error Responses

**Condition** : If email has already been registered.

**Code** : `400 Bad Request`

**Content** : `{"Error": "Email has already been registered"}`
