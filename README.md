<p align="center">
  <img src="./public/logo.png" />
</p>

<p align="center">
  <a href="#about">About</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#preview">Preview</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#building">Building</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#contributing">Contributing</a>&nbsp;&nbsp;&nbsp;
</p>


## About
<strong>Beer Stock</strong> is a API for managing beer stocks. However, the main focus is to develop unit tests to cover and validate the application.


## Preview
#### Tests Coverage
<p align="center">
  <img src="./public/7.png" />
</p>

#### Beer Stock
```
POST: http://localhost:8080/api/v1/beers
```
<p align="center">
  <img src="./public/1.png" />
</p>

```
GET: http://localhost:8080/api/v1/beers/{name}
```
<p align="center">
  <img src="./public/2.png" />
</p>

```
GET: http://localhost:8080/api/v1/beers
```
<p align="center">
  <img src="./public/3.png" />
</p>

```
DELETE: http://localhost:8080/api/v1/beers/{id}
```
<p align="center">
  <img src="./public/4.png" />
</p>

```
PATCH: http://localhost:8080/api/v1/beers/{id}/increment
```
<p align="center">
  <img src="./public/5.png" />
</p>

```
PATCH: http://localhost:8080/api/v1/beers/{id}/decrement
```
<p align="center">
  <img src="./public/6.png" />
</p>



## Back-end Technologies
This project was developed using the following technologies:
- [Spring](https://spring.io/)
- [Java](https://www.oracle.com/br/java/technologies/javase-jdk11-downloads.html)
- [JPA + Hibernate](https://spring.io/projects/spring-data-jpa)
- [JUnit](https://junit.org)
- [Mockito](https://site.mockito.org)
- [Hamcrest](https://hamcrest.org)
- [MapStruct](https://mapstruct.org)


## Building
You'll need [Java 11+](https://www.oracle.com/br/java/technologies/javase-jdk11-downloads.html) and [Maven](https://maven.apache.org/download.cgi) installed on your computer in order to build this app.

```bash
$ git clone https://github.com/eric-souzams/beerstock.git
$ cd /beerstock
$ mvn spring-boot:run
```


## Contributing
This repository is currently under development. If you want to contribute please fork the repository and get your hands dirty, and make the changes as you'd like and submit the Pull request.