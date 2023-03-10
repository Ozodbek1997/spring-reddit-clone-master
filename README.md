# spring-reddit-clone
Reddit clone built using Spring Boot, Spring Security with JPA Authentication, Spring Data JPA with MySQL, Spring MVC. The frontend is built using Angular - You can find the frontend source code here - https://github.com/Ozodbek97/angular-reddit-clone-master

# Recent Changes

 
- Added 'spring-boot-starter-validation' dependency in pom.xml file to support Java Bean Validation annotations.
- *IMPORTANT*: Removed Legacy JWT Authentication Mechanism and replaced it with latest Spring Security JWT Support.
- Adapted SecurityConfig.java class according to latest Spring Security configuration settings, see method configure(AuthenticationManagerBuilder) inside SecurityConfig.java class
- Set spring.jpa.open-in-view property as false.

 
# Front end code
https://github.com/Ozodbek97/angular-reddit-clone

# Screenshots
1. Home Page

 ![1](https://user-images.githubusercontent.com/26486928/224223878-285cc15a-2d0f-4c3e-90f9-06103e8b37fd.png)

2. View Post Page

 
![2](https://user-images.githubusercontent.com/26486928/224223894-df6e827f-097c-4293-9432-1c60a1569095.png)

3. Create Post Page

 
![3](https://user-images.githubusercontent.com/26486928/224223908-dd1265b6-093b-490f-948b-679fdc9e93e2.png)

4. Create Subreddit Page

 ![4](https://user-images.githubusercontent.com/26486928/224223916-1c9f55ca-3fbf-43af-9609-8a4b5158911b.png)


5. User Profile Page
![5](https://user-images.githubusercontent.com/26486928/224223930-7f0e5bd8-2e0b-4a44-a56c-c6fc22601fba.png)

 
