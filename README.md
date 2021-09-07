# appointment-system

## 7-Day Psychology Web application using Spring MVC JAVA

#### Note: I cannot share code of this project because it is a group project and we are not allowed to share code.

- allow user to book appointment through web application.
- To develop web application. I use different tools and technology.
- I have completed login, user registration, and email send functionality in this project.


##### Mockflow wireframe tool to create prototype of web page:

![1](https://user-images.githubusercontent.com/85042722/132343996-cf7465be-9bc5-4924-8157-e0698d0d296c.png)

##### JSP pages of User Interface

![2](https://user-images.githubusercontent.com/85042722/132344162-77f132df-b1e1-4d18-9e28-d998c131aa74.jpg)

##### Login page User Interface

![3](https://user-images.githubusercontent.com/85042722/132344304-8b4a6a31-e02d-4c2a-af12-ef33bf262b85.jpg)

##### Login page code

![4](https://user-images.githubusercontent.com/85042722/132344440-6440eba8-9afa-42e0-94f6-34f18084e69a.jpg)

##### Application Context.xml file for database table creation
 
the Java code file of User model that automatically converted into a Database table when project run

![5](https://user-images.githubusercontent.com/85042722/132344577-51bbaf7a-99f0-4896-881e-09ce688cbcf5.jpg)

##### User model

![6](https://user-images.githubusercontent.com/85042722/132344816-dd141fa1-2631-40b6-a297-4fd55d45a410.jpg)

##### web_user database table

user model shows the database table field name in User.java file in code with get and set methods and also with constraint. Furthermore, these private variables are converted into database table column.

![7](https://user-images.githubusercontent.com/85042722/132345014-10071a59-ea25-43ff-a7f5-8eb75060183e.jpg)


##### Login page code explain

When a user tries to access the login page of a web application then the Get method from the file controller will call. Here in the below image shows the Get method for login page.

![8](https://user-images.githubusercontent.com/85042722/132345275-5d0430e7-e5fc-4548-b867-3dcfd963f549.jpg)

##### Post method of login code

Here the @RequestMapping user can get the page URL such as login.papa which will show in the URL bar of the browser and any hacker cannot predict which actual file will be requested. Which will provide security.

Similarly, the login function has a POST method where request goes into the database to find user email, role and password. If the password is correct then respect users will login and see the dashboard according to the role.

![9](https://user-images.githubusercontent.com/85042722/132345489-b5cae994-9f8f-4d3b-b2ad-b5f56ae4c3cb.jpg)


##### findUser() method in abstract class

when the user enter the role, email id and password into login form, it will come into login post method through @ModelAttribute(“loginObject”) parameter where all data binded into java object then it will the findUser() method.

![10](https://user-images.githubusercontent.com/85042722/132345791-094f99c1-c99f-4f72-aff1-dc156672f4fb.jpg)

##### findUser() method implementation

![11](https://user-images.githubusercontent.com/85042722/132345892-5430b5e0-316e-4787-9348-20a31cc5d646.jpg)


## Tools and Technology used:

1. Eclipse IDE 2020-03 
2. Apache Tomcat v9.0
3. MySQL Workbench 8.0.18, HeidiSQL 11.0
4. Java Development kit 13
5.  Bitbucket
6.  SourceTree

### Home page 

![12](https://user-images.githubusercontent.com/85042722/132346341-06fb11c2-d73c-42c0-8c45-f0f2ba795b22.jpg)


### Email for Patient Registration Account

![14](https://user-images.githubusercontent.com/85042722/132346486-f3a01d9e-903d-421b-98bb-fccb708d9357.jpg)


