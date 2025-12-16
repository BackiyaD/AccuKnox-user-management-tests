# OrangeHRM Automation Testing – Playwright (Java)

This repository contains an end-to-end automation testing framework for the OrangeHRM application, built using Playwright with Java, TestNG, and Page Object Model (POM) design pattern. The project covers User Management workflows such as adding users, searching users, handling duplicate users, updating roles, deleting users, and validating login scenarios.

**Tech Stack**

Language: Java (JDK 8)
Automation Tool: Playwright (Java)
Test Framework: TestNG
Build Tool: Maven
Design Pattern: Page Object Model (POM)
Browser Support: Chromium (configurable)
Reporting: TestNG Default Reports

**Test Scenarios Covered**

Add new user
Search existing user
Search non-existent user
Prevent duplicate username creation
Update user role
Delete user
Validate updated user login
Admin login
Logout validation
Updated user login verification

**How to Run the Test Cases**
Run using TestNG XML
Navigate to: src/test/resources/OrangeHRMTestNG.xml

Run Individual Test Class
Navigate to: src/test/java/OrangeHRMtest/UserManagementTests.java
