# spring-reddit-clone
Reddit clone built using Spring Boot, Spring Security with JPA Authentication, Spring Data JPA with MySQL, Spring MVC. The frontend is built using Angular - You can find the frontend source code here - https://github.com/Ozodbek97/angular-reddit-clone

# Recent Changes

 
- Added 'spring-boot-starter-validation' dependency in pom.xml file to support Java Bean Validation annotations.
- *IMPORTANT*: Removed Legacy JWT Authentication Mechanism and replaced it with latest Spring Security JWT Support.
- Adapted SecurityConfig.java class according to latest Spring Security configuration settings, see method configure(AuthenticationManagerBuilder) inside SecurityConfig.java class
- Set spring.jpa.open-in-view property as false.

 
# Front end code
https://github.com/Ozodbek97/angular-reddit-clone

# Screenshots
1. Home Page

![Home Page](https://github.com/Ozodbek97/spring-reddit-clone/blob/master/src/main/resources/images/reddit-screenshot-updated.PNG)

2. View Post Page

![View Post Page](https://github.com/Ozodbek97/spring-reddit-clone/blob/master/src/main/resources/images/reddit-screenshot-updated.PNG)

3. Create Post Page

![Create Post Page](https://github.com/Ozodbek97/spring-reddit-clone/blob/master/src/main/resources/images/create-post.PNG)

4. Create Subreddit Page

![Create Subreddit Page](https://github.com/Ozodbek97/spring-reddit-clone/blob/master/src/main/resources/images/create-subreddit.PNG)

5. User Profile Page

![User Profile Page](https://github.com/Ozodbek97/spring-reddit-clone/blob/master/src/main/resources/images/user-profile.PNG)
