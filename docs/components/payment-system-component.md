---
id: payment-system-component
title: Payment System Component
sidebar_label: Payment System Component
---

# Payment System Component

*Component Identifier:* `PaymentSystemComponent`

*Title:* Payment System

## Properties
- **PaymentInfo**:
  - **Type**: Object
  - **Description**: Contains payment information provided by the client.
- **PaymentConfirmation**:
  - **Type**: Object
  - **Description**: Confirms the payment has been successfully processed.

## Methods
- **SubmitPayment()**: Sends the client's payment information to the system.
- **ReceiveConfirmation()**: Receives the payment confirmation from the system.

## Links
- **ClientPage**: Sends payment info and receives confirmation.
- **OrderSystemComponent**: Updates the order system with payment confirmation.
