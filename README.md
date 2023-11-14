# Api test - README

## Introduction

Welcome to the Api test testing collection! This README serves as a guide to understanding the purpose of the collection, what is being tested, the tools used, and why we chose this API for testing.

## Table of Contents

- [Introduction](#introduction)
- [Postman Collection Information](#postman-collection-information)
- [Collection Structure](#collection-structure)
  - [Folder: 1 - Goal Operations](#1-folder-1---goal-operations)
  - [Folder: 2 - Future Adventures](#2-folder-2---future-adventures)
- [Variables](#variables)
- [Testing Scope](#testing-scope)
- [Testing Tools](#testing-tools)
- [API Selection](#api-selection)
- [Getting Started](#getting-started)

## Postman Collection Information

- **Collection Name:** Testowanie
- **Postman ID:** ab741256-de75-483b-ba15-e5460129df4a
- **Exporter ID:** 31026504
- **Schema:** [Postman Collection Schema](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

## Collection Structure

The collection is organized into folders, each representing a set of related API requests.

### 1. Folder: 1 - Goal Operations

This folder contains a set of API requests related to goals:

#### 1.1. Request: get goals

- **Method:** GET
- **URL:** [http://127.0.0.1:8000/goals/{goal_id}?goals_id=2](http://127.0.0.1:8000/goals/{goal_id}?goals_id=2)
- **Purpose:** Retrieve information about a specific goal by providing the `goal_id` as a parameter in the URL.

#### 1.2. Request: get username

- **Method:** GET
- **URL:** [http://127.0.0.1:8000/goals/domi](http://127.0.0.1:8000/goals/domi)
- **Purpose:** Retrieve information about a user's goals by providing the username in the URL.

#### 1.3. Request: post goals

- **Method:** POST
- **URL:** [http://127.0.0.1:8000/goals?goal=mmm](http://127.0.0.1:8000/goals?goal=mmm)
- **Purpose:** Create a new goal by sending a POST request with the goal information as a query parameter.

#### 1.4. Request: delete goals

- **Method:** DELETE
- **URL:** [http://127.0.0.1:8000/goals/12f32d16-f983-4b07-a1e7-943a295ba6c6](http://127.0.0.1:8000/goals/12f32d16-f983-4b07-a1e7-943a295ba6c6)
- **Purpose:** Delete a specific goal by providing the `goal_id` in the URL.

#### 1.5. Request: PUT GOALS

- **Method:** PUT
- **URL:** [http://127.0.0.1:8000/goals/1](http://127.0.0.1:8000/goals/1)
- **Purpose:** Update an existing goal by sending a PUT request with the updated information.

### 2. Folder: 2 - Future Adventures

This folder is currently empty and reserved for future additions.

## Variables

- **Variable Key:** url
- **Variable Value:** [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
- **Purpose:** This variable serves as the base URL in requests, ensuring flexibility and ease of maintenance.

## Testing Scope

### What is Tested

In this project, we focus on testing various goal-related operations, including retrieval, creation, and modification.

### Why it's Important

Testing these operations ensures the reliability and robustness of the API, providing a seamless user experience.

## Testing Tools
Tools Used

1.Postman:
Role: Postman is a versatile API testing tool that facilitates the creation, sharing, and testing of APIs. It simplifies the testing process with features like request building, automated testing workflows, and collaboration capabilities.

2.NewRelic:
Role: NewRelic aids in application performance monitoring and analysis. It provides insights into system performance, helping identify bottlenecks, errors, and areas for improvement. This tool ensures that the API functions optimally under various conditions.



## API Selection

### Why This API

We chose the Api Test API because:

- **Extensive Functionality:**
  - Api Test provides a wide range of features that align with our testing requirements.

- **Simplified Design:**
  - Its straightforward and efficient design streamlines testing for our team.

- **Community Assistance:**
  - Api Test's engaged community ensures rapid issue resolution and access to valuable resources.

Selecting Api Test supports our goal of enhancing functionality and ensuring an efficient testing experience for our application.

## Conclusion

This README provides an overview of the testing strategy employed in this project, the tools selected for testing, and the rationale behind choosing the specific API.

