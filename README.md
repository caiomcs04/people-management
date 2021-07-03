
# Person API

> A REST API with Spring Boot for registering and managing people in an organization, deployed in the cloud (Heroku). An exercise to see the main REST architectural style concepts involved during project development.

## Prerequisites

> - An IDE of your choice
> - **Java** with version greater than or equal to 8 - [Java Donwload](https://www.java.com)

## Installation

> - Clone this project in your machine with the command:
> ```
> 	git clone https://github.com/caiomcs04/personalapi.git
> ```

## Execution in localhost

> - Open **personalapi** folder using an IDE of your choice
>
> - Load marven changes in build.gradle file if your IDE doesn't do it automatically
>
> - Run PersonalapiApplication(~/personalapi/src/main/java/one/dio/personalapi)
>
> - After starting the service go to [H2 memory bank](http://localhost:8083/h2)
>
> - Change **JDBC URL** to **jdbc:h2:~/personalapi**
>
> ![Captura de tela de 2021-06-29 20-08-40](https://user-images.githubusercontent.com/66964367/123878905-598f3f00-d916-11eb-9e84-2e8def3f533e.png)
>
> - Then press conect to get access to memory bank
>
> - You can execute any crud using an API develoment plataform of your choice
>
> - Or you can use [Swagger](http://localhost:8082/swagger-ui.html#/) as well
> 
>![Captura de tela de 2021-06-29 20-20-06](https://user-images.githubusercontent.com/66964367/123879556-82640400-d917-11eb-9e00-2c60ba2cb888.png)

## Functionalities

> You will be able to test all functionalities in [Swagger](http://localhost:8082/swagger-ui.html#/) 
> And also will be able to check the audit and data base in [H2](http://localhost:8082/h2)

## Contribution

> - To contribute to this project, fork this project, make the changes you want and create a pull request;
> - Futher i will implement a composite primary key for some classes and some business rules aswell 

## Authors

> - **Caio Moreira de Carvalho Sampaio** - [Linkedin](https://www.linkedin.com/in/caio-sampaio-b02a3669/) | [Email](caio6c@yahoo.com.br)

## Special thanks 

> Digital Innovation One and Satander Bank for the fullstack scholarship opportunity
