---
id: quote-calculation-component
title: Quote Calculation Component
sidebar_label: Quote Calculation Component
---

# Quote Calculation Component

*Component Identifier:* `QuoteCalculationComponent`

*Title:* Quote Calculation

## Properties
- **SelectedService**:
  - **Type**: Object
  - **Description**: The service selected by the client for which the quote is being generated.

## Methods
- **GenerateQuote()**: Generates a quote based on the selected service and pricing information from the **ServiceDBComponent**.

## Links
- **ServiceDBComponent**: Provides pricing information for the selected service.
- **QuoteDBComponent**: Stores the generated quote for future reference.
