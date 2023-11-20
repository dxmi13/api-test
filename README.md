# Api Test - README

## Introduction

Welcome to the Api Test collections! This README serves as a guide to understand the purpose of the collection, what's being tested and the tools used.

## Table of Contents

- [Introduction](#introduction)
- [Postman Collection Information](#postman-collection-information)
- [Collection Structure](#collection-structure)
  - [Folder: 1 - Collection 1](#1-folder-1---goal-operations)
  - [Folder: 2 - Collection 2](#2-folder-2---future-adventures)
- [Variables](#variables)
- [Testing Scope](#testing-scope)
- [Testing Tools](#testing-tools)
- [API Selection](#api-selection)
- [Conclusion](#conclusion)

## Postman Collection Information

- **Collection Name:** Api Test
- **Postman ID:** ab741256-de75-483b-ba15-e5460129df4a
- **Exporter ID:** 31026504
- **Schema:** [Postman Collection Schema](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

## Collection Structure

The collection is organized into folders, each representing a set of related API requests.

### 1. Folder: 1 - Collection 1

This folder contains API requests related to goals.

#### 1.1. Request: get goals

- **Method:** GET
- **URL:** [http://127.0.0.1:8000/goals/{goal_id}?goals_id=2](http://127.0.0.1:8000/goals/{goal_id}?goals_id=2)
- **Purpose:** Retrieve information about a specific goal.

#### 1.2. Request: get username

- **Method:** GET
- **URL:** [http://127.0.0.1:8000/goals/domi](http://127.0.0.1:8000/goals/domi)
- **Purpose:** Retrieve information about a user's goals.

#### 1.3. Request: post goals

- **Method:** POST
- **URL:** [http://127.0.0.1:8000/goals?goal=mmm](http://127.0.0.1:8000/goals?goal=mmm)
- **Purpose:** Create a new goal.

#### 1.4. Request: delete goals

- **Method:** DELETE
- **URL:** [http://127.0.0.1:8000/goals/12f32d16-f983-4b07-a1e7-943a295ba6c6](http://127.0.0.1:8000/goals/12f32d16-f983-4b07-a1e7-943a295ba6c6)
- **Purpose:** Delete a specific goal.

#### 1.5. Request: PUT GOALS

- **Method:** PUT
- **URL:** [http://127.0.0.1:8000/goals/1](http://127.0.0.1:8000/goals/1)
- **Purpose:** Update an existing goal.

### 2. Folder: 2 - Collection 2

#### 2.1. Request: get account block list

- **Method:** GET
- **URL:** ("https://api.imgur.com/3/account/me/block")
- **Purpose:** Retrieve your account's block list.

#### 2.2. Request: get token

- **Method:** GET
- **URL:** ("https://api.imgur.com/oauth2/token")
- **Purpose:** Get token for oauth2.

#### 2.3. Request: get images

- **Method:** GET
- **URL:** ("https://api.imgur.com/3/account/me/images")
- **Purpose:** Get images from your account.

#### 2.4. Request: post comment-vote

- **Method:** POST
- **URL:** ("https://api.imgur.com/3/comment/1/vote/'up'")
- **Purpose:** Post comment-vote

#### 2.5. Request: put settings

- **Method:** PUT
- **URL:** ("https://api.imgur.com/3/account/dxmi133/settings")
- **Purpose:** Put your account's settings

#### 2.6. Request: delete a comment

- **Method:** DELETE
- **URL:** ("https://api.imgur.com/3/comment/1")
- **Purpose:** Deletes a comment by id

## Variables

- **Variable Key:** url
- **Variable Value:** [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
- **Purpose:** This variable serves as the base URL in requests, ensuring flexibility and ease of maintenance.

## Testing Scope

### What is Tested

The project focuses on testing various api requests from GoalApi and

### Why it's Important

Testing these operations ensures the reliability and robustness of the API, providing a seamless user experience.

## Testing Tools

### Tools Used

1. **Postman:**
   - **Role:** Versatile API testing tool for request building, automated workflows, and collaboration.


## API Selection

GoalsApi and Imgur Api

## SECRET VARIABLES

Imgur Api needs Oauth2 token to work. That's why users should use config.json.example file to put in their own credentials and then delete the rename it to config.json for it to work.

## Conclusion

This README provides an overview of our testing APIs process and our requests.
We used this API, cause that was the only tutorial on yt, that we understood 
 about testing API :)

