# E-commerce API

**HOST**: http:localhost:8000

### Create invoice API

**URL** : `/create_invoice`

**Method** : `POST`

**Body request**

```json
{
    "seller_id": 3,
    "buyer_id": 2,
    "amount": 4.30,
    "description": "Clear Case 1"
}
```

## Success Response

**Code** : `HTTP 201 CREATED`

**Content example**

```json
		{
			"seller_id":3,
			"buyer_id":2,
			"amount":4.3,
			"description":"Clear Case 1"
		}
```

## Error Responses

**Condition** : If GET/PUT/DELETE request is performed instead of POST

**Code** : `400 Bad Request`


### Get invoice API

**URL**: `/get_invoice/:id`

**Method**: `GET`

## Success Response

**Code** : `HTTP 200 OK`

**Content example**

```json
		{
			"seller_id":3,
			"buyer_id":2,
			"amount":4.3,
			"description":"Clear Case 1"
		}
```

## Error Responses

**Condition** : If invoice ID is not found.

**Code** : `HTTP 404 Not Found`

**Condition** : If POST/PUT/DELETE request is performed instead of POST

**Code** : `400 Bad Request`
