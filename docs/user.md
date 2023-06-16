#User API SPEC

## Register User API

- Endpoint : POST /v1/users/register
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

- Endpoint GET /v1/users/login

- Request Body : 

``` json

{
    "username": "mahardikakdenie",
    "password": "password",
}

```

- Response body Success

``` json

{
    "data": {
        "token": "unique:token",
    },
}

```




## Update User API

## Get User API

## Logout User API
