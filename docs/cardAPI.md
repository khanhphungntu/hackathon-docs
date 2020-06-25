# E-commerce API

**HOST**: `http://35.223.80.52/`

## Add credit card API

**URL** : `/save_card/`

**Method** : `POST`

**Body request**

```json
{
    "email": "khanh26688@gmail.com",
    "card_number": "4895070000003551", 
    "full_name": "Khanh",
    "expiry_date": "10/20",
    "ccv": "022",
	"uid": "Yo6m5z2panXU4jDAtTuzoeTE3hH3"
}
```

### Success Response

**Code** : `201 Created`

### Error Responses

**Condition** : If creation fails.

**Code** : `400 Bad Request`

## View credit card API

**URL** : `/view_card/<uid>`

**Method** : `GET`

### Success Response

**Code** : `200 Success`

**Content example**

```json
	{
    "public_key": "BDjqIuAhhR29ZZ8s1RwTtEwc2NP3zeVh",
    "card_details": {
        "full_name": "Khanh",
        "expiry_date": "12/23",
        "card_number": "1234567891012345",
        "ccv": 686
    }
```

### Error Responses

**Condition** : If public key not found.

**Code** : `404 Not found`

**Content** : `{"content": "Card does not exist in the database"}`


**Condition** : If body content fields are not correct.

**Code** : `400 Bad Request`


## Remove credit card API

**URL** : `/del_card/<uid>`

**Method** : `DELETE`

### Success Response

**Code** : `200 Success`

**Content example**

```json
    {"content": "Deleted Successfully"}
```

### Error Responses

**Condition** : If public key not found.

**Code** : `404 Not found`

**Content** : `{"content": "Card does not exist in the database"}`