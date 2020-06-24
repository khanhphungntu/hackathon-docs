# Transaction API

**HOST**: `https://e-context-279708.df.r.appspot.com`

## Add credit card API

**URL** : `/card/`

**Method** : `POST`

**Body request**

```json
{
    "sender_key": "0I4ZDiPP50q0BA3CsA1DqggSQgUmD6lf", //public key of buyer
    "recipient_key": "t8YKfZM8Kgk58zVVK9qFhT4p0fJWLGUl",  // public key of seller
    "amount": 100,
    "currency": "SGD"
}
```

### Success Response

**Code** : `200 Ok`

**Content example**

```json
    {
        "response": "Money is transfered successfully!",
        "transactionIdentifier": 819277640650270
    }
```

### Error Responses

**Condition** : If body content fields are not correct.

**Code** : `404 Bad Request`

**Content** : `{"Error": "Details error wil be listed here"}`
