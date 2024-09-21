---
id: usage_database
title: Usage Database
description: Stores and tracks service usage data for customers, including usage frequency and service details.
---

## Fields

| Field Name  | Type    | Description                                    |
|-------------|---------|------------------------------------------------|
| Usage ID    | Integer | Unique ID for the service usage entry          |
| Customer ID | Integer | ID of the customer using the service           |
| Service ID  | Integer | ID of the service being used                   |
| Usage Data  | Text    | Detailed information about the service usage   |
| Start Date  | DateTime| Timestamp when the service usage started       |
| End Date    | DateTime| Timestamp when the service usage ended         |

## Actions

- **Log Usage**: Records new service usage data into the database.
- **Retrieve Usage**: Retrieves usage details based on the customer or service ID.
- **Update Usage**: Updates existing service usage information.
- **Delete Usage**: Deletes a specific usage entry from the database.

## Methods

### `logUsage(customerId, serviceId, usageData)`

- **Description**: Records a new usage entry in the database for a given customer and service.
- **Parameters**:
  - `customerId`: The ID of the customer using the service.
  - `serviceId`: The ID of the service being used.
  - `usageData`: Detailed information about the usage, such as duration or specifics of service consumption.
- **Returns**: The newly created usage entry’s ID.

### `getUsage(usageId)`

- **Description**: Retrieves details of a specific usage entry based on the usage ID.
- **Parameters**:
  - `usageId`: The ID of the usage entry to retrieve.
- **Returns**: The usage data, including service and duration information.

### `updateUsage(usageId, updatedData)`

- **Description**: Updates an existing usage entry with new data.
- **Parameters**:
  - `usageId`: The ID of the usage entry to update.
  - `updatedData`: The new data to update in the usage entry.
- **Returns**: Confirmation that the usage entry has been updated.

### `deleteUsage(usageId)`

- **Description**: Deletes a specific usage entry from the database.
- **Parameters**:
  - `usageId`: The ID of the usage entry to delete.
- **Returns**: Confirmation that the usage entry has been deleted.

---

The **Usage Database** component allows efficient tracking of how services are consumed by customers, providing insight into service utilization and customer engagement.
