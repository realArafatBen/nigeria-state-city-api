# Nigeria State and Region API
**Introduction to using the api** 

Locus is an awesome api to fetch all states, cities and region in Nigerian!! 
I was in of it, when i made it. So feel free to use it for your own need. 

API endpoint `https://locus.fkkas.com/api/` 

Send a `GET` request to get all states in Nigeria
`curl https://locus.fkkas.com/api/states` 

**Response**
```javascript
  { 
    data: [
      {
      id: 6, 
      name: "Abia", 
      alias: "abia"
      }, 
      {
      "id":1,
      "name":"Abuja (FCT)",
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
      name: "Abia", 
      alias: "abia"
      }, 
      {
      "id":1,
      "name":"Abuja (FCT)",
      "alias":"abuja"
      }
     ]
   }
```

**Yah!!! Drop your issues if any**


