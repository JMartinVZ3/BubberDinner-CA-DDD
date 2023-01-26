# Buber Dinner Api

- [Buber Dinner API](#buber-dinner-api)
    - [Auth](#auth)
        - [Register](#register)
            - [Register Request](#register-request)
            - [Register Response](#register-response)
        - [Login](#login)
            - [Login Request](#login-request)
            - [Login Response](#login-response)

## AUTH

### Register

``` js
POST {{host}}/auth/register
```

#### Register Request

```json
{
    "firstName": "Martin",
    "lastName: "Veliz",
    "email": "jmartinvz@outlook.com",
    "password": "test123"
}
```

#### Register Response

```js
200 OK
```

```json
{
    "id": "9d7d28a3-2081-4463-be10-e514242dd73c"
    "firstName": "Martin",
    "lastName: "Veliz",
    "email": "jmartinvz@outlook.com",
    "password": "test123"
}
```