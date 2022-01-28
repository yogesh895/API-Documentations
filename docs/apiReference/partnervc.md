<h1>Partner API</h1>
<b>HTTP Method:</b> &nbsp;&nbsp;&nbsp;[POST](#){ .md-button .md-button--primary} &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>Endpoint:</b>&nbsp;&nbsp;&nbsp; [https://groot.homingos.com/api/orders/partnervc](https://groot.homingos.com/api/orders/partnervc)

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
    	"order_id":"a4b835b8-3532-4662-8e55-275bfb2dc0f7",
    	"augmented_image":"https://homingos-magik.s3.ap-south-1.amazonaws.com/vibo/prod/print/ee08ea85-82bf-47bb-9b03-1a868d72a2fd.jpeg",
    	"anv_id":"V023412",
    	"is_fulfilled":false
    	},
    "message":"Videocard Added",
    "status":200,
    "error":false
    }
    ```










