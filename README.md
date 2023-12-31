# <h1 align = "center"> 🧑‍💻Online Food Delivery👌 </h1>
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.1.3-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
</p>  

![online-food-delivery-industry-min](https://github.com/DeepakKDEV/ApicrudOperation/assets/142679882/11625f4d-3afe-4a4f-a634-7d9a1bf6114f)
   
 ## Overview
   <p>🔸This is simple Food Delivery App built using Spring Boot framework. The idea was to build a simple Food Delivery App to perform basic CRUD operations                  with some validations and auhentication.
   </p>
   
## :one: Frameworks and Languages Used -
    1. SpringBoot
    2. JAVA-17
    3. Postman
    4. MySQL
    5. Swagger
    
## :two: Dependency Used
    1. Spring Web
    2. Spring Boot Dev Tools
    3. Lombok
    4. Spring Data JPA
    5. MySQL Driver
    6. Validation
    7. Swagger
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
## :three: Dataflow (Functions Used In)
### :white_flower: 1. Model - This used to show the mirror of our database which involves real world entities.
#### :o: AuthenticationToken.java
#### :o: Admin.java
#### :o: Order.java
#### :o: User.java
#### :o: Enum Entity
 - status
     -Gender
     -TypeFood
#### :o: SignInAuthentication.java(DTO)
          signInput

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### :white_flower: 2. Service - This Layer is used to perform business functionalities.
#### :o: AdminService.java
#### :o: FoodItemServicee.java
#### :o:AuthenticationTokenService.java
#### :o: UserService.java
#### :o: OrderService.java


----------------------------------------------------------------------------------------------------------------------------------------------------

### :white_flower: 3. Controller - This Controller is used to create RestApi's and perform basic CRUD operations.
#### :o: AdminController.java
#### :o: UserController.java

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### :white_flower: 4. Repository : data access object (DAO) is an object that provides an abstract interface to some type of database or other persistence mechanisms.
#### :o: AdminRepo.java
#### :o: IFoodItemRepo.java
#### :o: IAuthenticationRepo.java
#### :o: IUserRepo.java
#### :o: IorderRepo.java


-------------------------------------------------------------------------------------------------------------------------------------------------------
### :white_flower: 5. Dto : Data transfer object
#### :o: Signup.java
#### :o: SignInInput.java
#### :o: SignOut.java
-------------------------------------------------------------------------------------------------------------------------------------------------------

#### :white_check_mark: User Controller

```java
http://localhost:8080//user/signUp
```
```java
http://localhost:8080//signIn/user
```
```java
http://localhost:8080//Order/by/user
```
```java
http://localhost:8080//Order/by/user
```
```
## :five: Test Rest Api's
#### :white_check_mark: Admin Controller
```java
http://localhost:8080/Admin/signUp
```

```java
http://localhost:8080/signIn/Admin
```

```java
http://localhost:8080/update/order/id/{id}
```

```java
http://localhost:8080/get/order
```
```java
http://localhost:8080/get/Foods

```java
http://localhost:8080/get//Delete/by/id/{id}


## :six: Documentation in Swagger
```java
 http://localhost:8080/swagger-ui/index.html#/
```
Admin & User Controller![Screenshot_10](https://github.com/DeepakKDEV/FoodDelivery/assets/142679882/399bebb1-d5c0-43eb-8929-0e246b7c3337)


## :seven: View in mySql Database

![Screenshot_8](https://github.com/DeepakKDEV/FoodDelivery/assets/142679882/c48a3e77-abeb-4fbd-a5ae-5ad440fd3254)





#  Summary
- :small_orange_diamond:  This is a sample Food Delivery App that allows two users :
- :one: User
- :two: Admin
- :small_orange_diamond: Admin users have all access to perform all the CRUD operations whereas the normal users can only Order Food and view the .
-  :small_orange_diamond: The API is built using mySQL database to store the Food Delivery ,ingredients and all its fields . IP Address of the deployment link must be static to ensure its availability. Additionally , the Api's uses annotation based validations to ensure that all the user inputs are valid before being processed.
-  :small_orange_diamond: Therefore , this project provides a scalable and secure API that allows to manage all the datas.



 <!-- Acknowledgments -->
## Acknowledgments
- Thank you to the Spring Boot and Java communities for providing excellent tools and resources.

<!-- Contact -->
## Contact📲
For questions or feedback, please contact : Avadhesh Shukla👍
- Maild Id 📧: avadheshsukla1636@gmail.com

<h1 align="center">Thank You💖...<h1>
<h3 align = "center"> ***********************************************************<h3>


