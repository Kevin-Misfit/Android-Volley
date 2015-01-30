# Android-Volley
--------
由于业务需求，这里将Google官方的网络请求框架Volley做了一些小小的更改：原来Volley在返回HTTP状态码的时候，并没有提供返回状态码对应的状态字符串(状态段串/状态描述/状态原因段串)的方法，所以在NetworkResponse类里新增了statusText字段，并修改了相应的构造方法，使其能够在获取到Http状态码的时候也能获取到状态描述字符串
