# locus
**Introduction to using the api**  
API endpoint `https://locus.fkkas.com/api/` 

Send a `GET` request to get all states in Nigeria
`curl https://locus.fkkas.com/api/states` 

**Response**
```javascript
  { 
    data: [
      {
      id: 6, 
      name: "Abia State", 
      alias: "abia"
      }, 
      {
      "id":1,
      "name":"Abuja (FCT) State",
      "alias":"abuja"
      }
     ]
   }
```
Send a `GET` request to get all state regions by adding the state `alias` to `curl https://locus.fkkas.com/api/regions/{alias}` 

**Example**
`curl https://locus.fkkas.com/api/regions/abuja`

```javascript
  { 
    data: [
        {
        "id":6,
        "name":"Abaji"
        },
      {
      "id":7,
      "name":"Apo District"
      }, 
      {
      "id":8,
      "name":"Asokoro",
      }
     ]
   }
```

Send a `GET` request to get all in nigeria `curl https://locus.fkkas.com/api/all` 

**Response** 
```javascript
  { 
    data: [
      {
      id: 6, 
      name: "Abia State", 
      alias: "abia"
      }, 
      {
      "id":1,
      "name":"Abuja (FCT) State",
      "alias":"abuja"
      }
     ]
   }
```

**Yah!!! Drop your issues if any**


