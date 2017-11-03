# StatusKoder

I webshoppen (customers, products, orders) skal i nu tilføje statuskoder i koden.

Status koderne kan inddeles i følgende kategorier

* 1xx - Informal
* 2xx, - Successful
* 3xx - further action needs to be taken by the user agent in order to fulfill the request
* 4xx - Client Error
* 5xx - Server Errors

I kan læse om statuskoder [her](https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html)    

Et eksempel er at hvis et product ikke findes skal der sendes statuskoden 404.
Hvis serveren "cracher" skal der sendes en anden statuskode.

Vi laver dette sammen ved tavlen lidt senere i dag.
