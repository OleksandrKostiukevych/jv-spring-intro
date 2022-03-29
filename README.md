# Spring Framework intro

- Implement UserService and UserDao
  
    ```java
      public interface UserService {
          User add(User user);
      
          List<User> getAll();
      }
    ```
  
- User should have `age`, `name` fields and overridden `equals()` and `hashcode()`

- In the Main class configure ApplicationContext and show how you are saving User into DB and
  reading him back

- Configure DataSource

- Understand the main concepts of Spring framework:
    - ApplicationContext
    - Bean
    - Bean Autowiring
    - Difference between @Bean and @Autowired and @Qualifier
    - What does each annotation used in videos mean?

__You can check yourself using this__ [checklist](https://mate-academy.github.io/jv-program-common-mistakes/java-spring/intro/java-spring-intro)
