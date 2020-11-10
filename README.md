# End-to-end tests for the Socks shop

Simple e2e tests built in cypress for this [__application__](https://github.com/microservices-demo/microservices-demo) 

Default baseUrl:

~~~json
{
    "baseUrl": "http://localhost:80"
}
~~~

Overwrite baseUrl:

~~~sh
CYPRESS_baseUrl=<baseUrl> npm run e2e
~~~