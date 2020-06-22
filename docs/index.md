# E-commerce API

**HOST**: `https://e-context-279708.df.r.appspot.com`

## Add credit card API

**URL** : `/card/add`

**Method** : `POST`

**Body request**

```json
{
	"email": "khanh26688@gmail.com",
	"card_number": "1234567891012345", // must be 16 digits
	"full_name": "Khanh",
	"expiry_date": "12/23",
	"ccv": 686 //must be length of 3
}
```

### Success Response

**Code** : `201 Created`

**Content example**

```json
    {
        "email": "khanh26688@gmail.com",
        "public_key": "SSTSjgyG0njbhIWLoTepDmwPJQtn6yMy"
    }
```

### Error Responses

**Condition** : If body content fields are not correct.

**Code** : `400 Bad Request`

**Content** : `{"Error": "Details error wil be listed here"}`


## Remove credit card API

**URL** : `/card/delete`

**Method** : `DELETE`

**Body request**

```json
{
	"public_key": "sYP6iAiSFKAi3rSt82hP8IC2jZyhnztk"
}
```

### Success Response

**Code** : `200 Success`

**Content example**

```json
    {"response": "Record is deleted successfully!"}
```

### Error Responses

**Condition** : If public key not found.

**Code** : `404 Not found`

**Content** : `{"Error": "Public key does not match any record"}`


**Condition** : If body content fields are not correct.

**Code** : `400 Bad Request`

**Content** : `{"Error": "An error occur"}`