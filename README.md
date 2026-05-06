# QA Selenium Automation Project – TestBlog Admin

This project demonstrates automated testing of a web application admin panel using Selenium WebDriver and Java.

Tested application:
https://testblog.kurs-qa.cubes.edu.rs/admin/posts

The project was created as a final automation testing exercise during QA training.

---

## Technologies Used

- Java
- Selenium WebDriver
- TestNG
- Maven
- Page Object Model (POM)

---

## Project Structure

src
 ├─ main
 │   └─ java
 │       └─ webpages
 │           LoginPage.java
 │           PostsAddPage.java
 │           PostsListPage.java
 │
 └─ test
     └─ java
         TestLogin.java
         TestAddPosts.java
         TestPostsList.java

---

## Automated Test Scenarios

### Login Test
Tests user login functionality with valid credentials.

### Add Post Test
Automates creation of a new blog post through the admin panel.

### Search Post Test
Checks if the created post appears in the posts table.

### Table Validation
Verifies that the post exists in the list after creation.

---

## Example Test Flow

1. Open admin login page
2. Enter username and password
3. Login to admin panel
4. Navigate to posts page
5. Create new post
6. Verify that the post appears in the posts list

---

## Purpose of the Project

The goal of this project is to demonstrate:

- Selenium UI automation
- Page Object Model structure
- Working with XPath and CSS selectors
- Automated verification of web elements

---

## Author

Jasna Katić Komad  
Junior QA Automation Engineer

## Application Under Test

[screenshots/ScreenPasword.png]](https://drive.google.com/file/d/18XxgFh8xk9IIWloyhsxJ2iw-dv2njRxB/view?usp=sharing)
[screenshots/BUGReoprt_01.png]](https://drive.google.com/file/d/15Hyh30PUQVVRbRCPTtXD0XOKNbO639hc/view?usp=sharing)
[screenshots/BUGReoprt_02.png]([screenshots/BUGReoprt_02.png](https://drive.google.com/drive/u/0/folders/1rw5WTjMq-dCxi5L7sZKVwtAWXuAZpLgS))

## How to Run Tests

1. Clone repository
2. Open project in IntelliJ IDEA
3. Install Maven dependencies
4. Run TestNG tests

Command:

mvn test

