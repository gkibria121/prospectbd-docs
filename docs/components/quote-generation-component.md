---
id: quote-generation-component
title: Quote Generation Component
sidebar_label: Quote Generation Component
---

# Quote Generation Component

*Component Identifier:* `QuoteGenerationComponent`

*Title:* Quote Generation

## Properties
- **SelectedService**:
  - **Type**: Object
  - **Description**: The service selected by the guest for which the quote is being generated.

## Methods
- **GenerateQuote()**: Generates a quote for the selected service based on usage data from **UsageDBComponent**.

## Links
- **UsageDBComponent**: Provides service usage data.
- **QuoteDBComponent**: Stores the generated quote.
