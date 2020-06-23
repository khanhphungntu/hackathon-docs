# E-commerce API

### When making a request to the Backend, always pass the user token in the Header's Authorization Field

**Sample**:

```javascript
import firebase from "firebase";

firebase.auth().currentUser.getIdToken(/* forceRefresh */ true).then(function(idToken) {
      axios.get(`http://127.0.0.1:8000/get_invoice/1`, { headers: { Authorization: idToken } })
      .then(res => {
        console.log(res.data);

      });
    }).catch(function(error) {
      // Handle error
    });
```

## Error Responses

**Condition** : If token is not passed or wrong token is passed

**Code** : `401 Unauthorized`