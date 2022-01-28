<h1>Order Details API</h1>
<b>HTTP Method:</b> &nbsp;&nbsp;&nbsp;[GET](#){ .md-button .md-button--primary} &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>Endpoint:</b>&nbsp;&nbsp;&nbsp; [https://groot.homingos.com/api/orders/orderdetails](https://groot.homingos.com/api/orders/orderdetails)

#### Use Case:
Get authorisation token by inputting id and password

#### Request Attributes:
| Attribute   | Description    |
| :---------- | :--------------|
| `email`     | Fetch resource |
| `password`  | Update resource|

#### Response Attributes:
- `data`

| Attribute   | Description    |
| :---------- | :--------------|
| `token`     | Fetch resource |
| `client_name`  | Update resource|
| `client_user_phone_number`| Update resource|
| `client_username`  | Update resource|
| `client_user_name`  | Update resource|
| `client_user_email`  | Update resource|
| `client_user_email`  | Update resource|

- `message`
- `status`
- `error`
<br>
<br>

#### Demo:
=== "CURL Request"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```

=== "Response"

    ```json
    {
    "data":
    	{
    	"token":"08ceae08e844dc9692d4108677f5210842baf8a0",
    	"client_name":"917303736274",
    	"client_user_phone_number":"7303736274",
    	"client_username":"917303736274",
    	"client_user_name":"Amit",
    	"client_user_email":"xamit.94@gmail.com",
    	"client_credits":199763
        },
    "message":"Token generated successfully",
    "status":200,
    "error":false
    }
    ```










