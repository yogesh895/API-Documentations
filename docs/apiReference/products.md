<h1>Product API</h1>
<b>HTTP Method:</b> &nbsp;&nbsp;&nbsp;[GET](#){ .md-button .md-button--primary} &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<b>Endpoint:</b>&nbsp;&nbsp;&nbsp; [https://groot.homingos.com/api/orders/products](https://groot.homingos.com/api/orders/products)

#### Use Case:
GET list of all Products Available for the Client company of logged in client user

#### Response Attributes:
- `data`

| Attribute   | Description    |
| :---------- | :--------------|
| `id`     | Fetch resource |
| `pricing`  | Update resource|
| `fulfilment_lvl`| Update resource|
| `active`  | Update resource|
| `pdf_size`  | Update resource|
| `client`  | Update resource|
| `product`  | Update resource|
| `product_type`  | Update resource|
| `credits`  | Update resource|

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
    {"data":[
    	{"id":"c6db39a2-84bd-42be-80e8-fb62ff39a438",
    	"pricing":99,
    	"fulfilment_lvl":"PDF",
    	"active":true,
    	"pdf_size":500,
    	"client":"a4819588-da22-46b8-b1fa-df2f83777877",
    	"product":"b972bba1-f7a1-4172-8388-64f1f4a7d7aa",
    	"product_type":"VIDEOCARD",
    	"credits":199763
    	}
     ],
    "message":"All Products",
    "status":200,
    "error":false}
    ```

