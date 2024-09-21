---
id: task-management-component
title: Task Management Component
sidebar_label: Task Management Component
---

# Task Management Component

*Component Identifier:* `TaskManagementComponent`

*Title:* Task Management

## Properties
- **TaskList**:
  - **Type**: Array
  - **Description**: A list of tasks assigned to workers.
- **TaskProgress**:
  - **Type**: Object
  - **Description**: The current status and progress of each task.

## Methods
- **AssignTasks()**: Assigns tasks to workers based on order details.
- **UpdateTaskProgress()**: Receives updates from workers and updates the task progress.

## Links
- **OrderSystemComponent**: Receives order data and assigns tasks.
- **WorkerPage**: Sends task updates from workers.
