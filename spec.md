# Rashid Application Specification

## Entities

### Task

- A `Task` represents a unit of work which a `User` can complete
- A `User` represents the authenticated individual using the application

## Actors

### User

A `User` is an authenticated individual person who uses the application

### Guest

A `Guest` is an un-authenticated individual person who uses the application

## Features

### 1) Tasks

#### 1-1 - Task Completion

- 1-1-1: A `User` can complete a `Task`
- 1-1-2: A `User` can un-complete a `Task`

#### 1-2 - Task Creation

- 1-2-1: A `User` can create a `Task`

#### 1-3 - Task Deletion

- 1-3-1: A `User` can delete a `Task`

#### 1-4 - Task List

- 1-4-1: A `User` can see a list of `Tasks`

### 2) Authentication

#### 2-1 - User Login

- 2-1-1: A `Guest` can log in or authenticate to the application by entering their email address and password.

#### 2-2 - User Logout

- 2-2-1: A `User` can log out of the application.


