---
id: quote_database
title: Quote Database
description: Stores and manages generated quotes for services, including pricing information and service details.
---

## Fields

| Field Name  | Type    | Description                                   |
|-------------|---------|-----------------------------------------------|
| Quote ID    | Integer | Unique ID for the quote                       |
| Service ID  | Integer | ID of the service associated with the quote   |
| Customer ID | Integer | ID of the customer requesting the quote       |
| Quote Data  | Text    | Detailed information about the quote, including estimated cost and service description |
| Created At  | DateTime| Timestamp when the quote was created          |
| Updated At  | DateTime| Timestamp when the quote was last updated     |

## Actions

- **Store Quote**: Stores a newly generated quote into the database.
- **Retrieve Quote**: Retrieves a specific quote based on the quote ID.
- **Update Quote**: Updates the details of an existing quote.
- **Delete Quote**: Deletes a specific quote from the database.

## Methods

### `createQuote(serviceId, customerId, quoteData)`

- **Description**: Creates and stores a new quote in the database for a given service and customer.
- **Parameters**:
  - `serviceId`: The ID of the service for which the quote is generated.
  - `customerId`: The ID of the customer requesting the quote.
  - `quoteData`: Detailed information about the quote, including pricing and service specifics.
- **Returns**: The newly created quote’s ID.

### `getQuote(quoteId)`

- **Description**: Retrieves the details of a quote using the quote ID.
- **Parameters**:
  - `quoteId`: The ID of the quote to retrieve.
- **Returns**: The quote data, including service and pricing information.

### `updateQuote(quoteId, updatedData)`

- **Description**: Updates an existing quote with new information.
- **Parameters**:
  - `quoteId`: The ID of the quote to update.
  - `updatedData`: The new data to update in the quote.
- **Returns**: Confirmation that the quote has been updated.

### `deleteQuote(quoteId)`

- **Description**: Deletes a specific quote from the database.
- **Parameters**:
  - `quoteId`: The ID of the quote to delete.
- **Returns**: Confirmation that the quote has been deleted.

---

The **Quote Database** component ensures all quotes generated for services are stored, managed, and retrieved efficiently for both customers and service providers.
