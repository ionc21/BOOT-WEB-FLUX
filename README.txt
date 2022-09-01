
BUILDING A REST API WITH FUNCTIONAL ENDPOINTS
Hi. Thanks for watching this course. Here you can find some notes and resources related to the content shown in this module.


Links:
Spring WebFlux documentation for Functional Endpoints
https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html#webflux-fn

Reactive Spring Article
https://github.com/joshlong/reactive-spring-article


cURL commands
curl -v http://localhost:8080/products
curl -v -H "Content-Type: application/json" -d "{\"name\":\"Black Tea\", \"price\":1.99}" http://localhost:8080/products/
curl -v -H "Content-Type: application/json" -d "{\"name\":\"Black Tea\", \"price\":2.99}" -X PUT http://localhost:8080/products/[ID]
curl -v http://localhost:8080/products
curl -X DELETE http://localhost:8080/products

BUILDING AN API CLIENT WITH WEBCLIENT
Hi. Thanks for watching this course. Here you can find some notes and resources related to the content shown in this module.


Links:
Spring WebFlux documentation for WebClient
https://docs.spring.io/spring/docs/current/spring-framework-reference/web-reactive.html#webflux-client

Sending HTTP requests with Spring WebClient
https://reflectoring.io/spring-webclient/

Spring Boot - How to use WebClient
https://gustavopeiretti.com/spring-boot-how-to-use-webclient/

Spring Boot WebClient Cheat Sheet
https://medium.com/swlh/spring-boot-webclient-cheat-sheet-5be26cfa3e

TESTING WEBFLUX ENDPOINTS WITH WEBTESTCLIENT
Hi. Thanks for watching this course. Here you can find some notes and resources related to the content shown in this module.


Links:
WebTestClient Documentation
https://docs.spring.io/spring/docs/current/spring-framework-reference/testing.html#webtestclient

MockBean Documentation
https://docs.spring.io/spring-boot/docs/current/api/org/springframework/boot/test/mock/mockito/MockBean.html

WebFluxTest Documentation
https://docs.spring.io/spring-boot/docs/current/api/org/springframework/boot/test/autoconfigure/web/reactive/WebFluxTest.html

AutoConfigureWebTestClientDocumentation
https://docs.spring.io/spring-boot/docs/current/api/org/springframework/boot/test/autoconfigure/web/reactive/AutoConfigureWebTestClient.html

Auto-configured Spring WebFlux Tests
https://docs.spring.io/spring-boot/docs/current-SNAPSHOT/reference/htmlsingle/#boot-features-testing-spring-boot-applications-testing-autoconfigured-webflux-tests

Example of reactive web application
https://github.com/idugalic/reactive-company

Spring 5 Reactive playground
https://github.com/hantsy/spring-reactive-sample