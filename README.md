# spring-interview
## 1. Why Spring is so popular?
### a. Dependency Injection
#### Before Spring
```java
ProductDao productDao = new ProductDaoImpl();
```
  * if we want to change the implementation of ProductDao, we need to change the ProductDaoImpl class.
  
#### After Spring
```java
@Autowired
ProductDao productDao;
```
  * If we want to change the implementation of ProductDao, we don't need to change the ProductDaoImpl class. Just change the xml configuration file.
  * Spring will inject the dependency automatically.(inversion of control)

### b. Spring IoC framework is the reason why Spring is popular.

### c. Spring has really good integration with other frameworks.



