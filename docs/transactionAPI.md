# E-commerce API

**HOST**: `http://35.223.80.52/`

### Make Payment API

**URL** : `/make_payment/<invoice_id>`

**Method** : `POST`

## Success Response

**Code** : `HTTP 201 CREATED`

**Content example**

```json
		{"content": "Transaction successful!", "transaction_id": 2020202020 }
```

## Error Responses

**Condition** : If Transaction failed

**Code** : `400 Bad Request`


```json
	{"Error": "Details error wil be listed here"}
```