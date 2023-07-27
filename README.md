Web Application Testing with Robot Framework

## Introduction

Welcome to my web application testing project using Robot Framework. I leverage the powerful capabilities of Robot Framework, along with the Browser and Faker libraries, to conduct comprehensive tests on a web application. The objective is to create a new user and validate required fields, ensuring a seamless user experience on the web application.

## Installation

Before running the tests, make sure you have Robot Framework and the required libraries installed. Follow these simple steps to set up the project:

1. Clone this repository to your local machine:

```bash
git clone <repository_url>
cd web-app-testing-robot-framework
```

2. Install project dependencies:

```bash
pip install -r requirements.txt
```

## Test Scenarios

Here are the key test scenarios covered in this project:

### Create New User for the Luma App

1. Precondition for New User Account
2. Enter Required Details for New User
3. Click Create Account Button and Assert User Creation Success

### Verify That User Cannot Omit Required Fields When Creating a New Account

1. Verify That User Cannot Omit Firstname
2. Verify That User Cannot Omit Lastname
3. Verify That User Cannot Omit Email
4. Verify That User Cannot Omit Password
5. Verify That User Cannot Omit Confirmed Password

### Edit User Address Details

1. Edit User Address Details with Phone Number, Street Address, City, and Postcode

## Keywords

Below are the essential keywords used in the tests:

- `Navigate to Home Page`: Opens the web application in the browser.
- `Precondition for New User Account`: Sets up the system for creating a new user account.
- `Edit User Address Details`: Allows users to edit their address details.
- `Enter Login Credentials and Click on the Login Button`: Enters user login credentials and clicks the login button.
- `Enter Required Details for New User`: Enters the required details for creating a new user account.
- `Enter Details for New User and Omit Required Fields`: Enters user details for account creation, omitting specified required fields.
- `Delete Address`: Deletes the user's address.

## Test Cases

Here are the key test cases for different test scenarios:

### Test Case 1: Create New User for the Luma App

This test case demonstrates creating a new user account on the Luma app.

### Test Case 2: Verify That User Cannot Omit Required Fields When Creating a New Account

This test case validates that the web application correctly enforces the requirement of specific fields during account creation.

### Test Case 3: Edit User Address Details

This test case verifies the functionality of editing user address details on the web application.
