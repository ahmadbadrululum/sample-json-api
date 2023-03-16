## REST API PRODUCT SERVICE
------------------------------------------------------------------------------------------

#### Product Detail

<details>
 <summary><code>GET</code>/api/v1/product - <code>(get product by variation id)</code></summary>

##### Parameters

> | name              |  type     | data type      | description                         |
> |-------------------|-----------|----------------|-------------------------------------|
> | `id`              |  required | int ($int64)   | The specific stub numeric id        |


##### Responses

> | http code     | content-type                      | response                                        |
> |---------------|-----------------------------------|-------------------------------------------------|
> | `200`         | `application/json`                | [response  product detail](product-search.json) |
> | `400`         | `application/json`                | `{"code":"400","message":"Bad Request"}`        |
