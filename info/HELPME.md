1. Docker:
- image-> buildo/h2database:latest
- port-> 8082:8082

jdbc:h2:mem:demo
username=sa
password=password12@

2. How to run:
   + Application run as debug
   - gradle build -x test
   - in git bash ./gradlew build -x test

3. POST http://localhost:8080/user/name
4. GET http://localhost:8080/users
5. PUT http://localhost:8080/user/1?name=tester
6. DELETE http://localhost:8080/user/3

