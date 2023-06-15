#User API SPEC

## Register User API

- Endpoint : POST /api/users
- Request Body - 

``` json
{
    "username": "mahardikakdenie",
    "password": "password",
    "name": "Mahardika Kessuma Denie",

}
```
- Response Body Success : 

``` json

{
    "data": {
        "username": "mahardikakdenie",
        "name": "Mahardika Kessuma Denie"
    },
    "errors": "Message",
}

```
- Response Body Error : 

``` json

{
    "data": {},
    "errors": "Message",
}

```

## Login User API

## Update User API

## Get User API

## Logout User API
