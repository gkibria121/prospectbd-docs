---
id: task-db-component
title: Task Database Component
sidebar_label: Task Database Component
---

# Task Database Component

*Component Identifier:* `TaskDBComponent`

*Title:* Task Database

## Properties
- **TaskInfo**:
  - **Type**: Object
  - **Description**: Contains the information and status of all tasks stored in the database.

## Methods
- **RetrieveTaskInfo()**: Provides task information for the **TaskManagementComponent**.
- **StoreTaskInfo()**: Stores updates to tasks received from the **TaskManagementComponent**.

## Links
- **TaskManagementComponent**: Retrieves and stores task information.
