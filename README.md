# Api Test - README

## Introduction

Welcome to the Api Test collection! This README serves as a guide to understand the purpose of the collection, what's being tested, the tools used, and why we chose this API.

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
- [Conclusion](#conclusion)

## Postman Collection Information

- **Collection Name:** Api Test
- **Postman ID:** ab741256-de75-483b-ba15-e5460129df4a
- **Exporter ID:** 31026504
- **Schema:** [Postman Collection Schema](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

## Collection Structure

The collection is organized into folders, each representing a set of related API requests.

### 1. Folder: 1 - Goal Operations

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

### 2. Folder: 2 - Future Adventures

This folder is currently empty and reserved for future additions.

## Variables

- **Variable Key:** url
- **Variable Value:** [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
- **Purpose:** This variable serves as the base URL in requests, ensuring flexibility and ease of maintenance.

## Testing Scope

### What is Tested

The project focuses on testing various goal-related operations, including retrieval, creation, and modification.

### Why it's Important

Testing these operations ensures the reliability and robustness of the API, providing a seamless user experience.

## Testing Tools

### Tools Used

1. **Postman:**
   - **Role:** Versatile API testing tool for request building, automated workflows, and collaboration.

2. **NewRelic:**
   - **Role:** Application performance monitoring for insights into system performance and optimization.

## API Selection

### Why This API

We chose the Api Test API for:

- **Extensive Functionality:** Comprehensive features aligned with testing requirements.
- **Simplified Design:** Straightforward and efficient for testing.
- **Community Assistance:** Active community for quick issue resolution.

Selecting Api Test supports our goal of enhancing functionality and ensuring an efficient testing experience.

## Conclusion

This README provides an overview of the testing strategy, tools, and the rationale behind choosing the Api Test API. Happy testing!

