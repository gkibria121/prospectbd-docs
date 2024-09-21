---
id: order-system-component
title: Order System Component
sidebar_label: Order System Component
---

# Order System Component

*Component Identifier:* `OrderSystemComponent`

*Title:* Order System

## Properties
- **OrderDetails**:
  - **Type**: Object
  - **Description**: Contains details of the client’s order.
- **OrderStatus**:
  - **Type**: String
  - **Description**: Displays the current status of the order.

## Methods
- **SubmitOrder()**: Sends order details to the **TaskManagementComponent**.
- **ReceiveOrderData()**: Receives order data from the **TaskManagementComponent**.

## Links
- **ClientPage**: Displays order details and status.
- **TaskManagementComponent**: Sends the order details for task assignment and management.
