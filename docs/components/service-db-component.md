---
id: service-db-component
title: Service Database Component
sidebar_label: Service Database Component
---

# Service Database Component

*Component Identifier:* `ServiceDBComponent`

*Title:* Service Database

## Properties
- **Services**:
  - **Type**: Array
  - **Description**: The list of all services available, stored in the service database.

## Methods
- **FetchServices()**: Retrieves the list of services for the **CatalogBrowsingComponent** or **ServiceFilteringComponent**.
- **FetchPricingInfo()**: Provides pricing information for the selected service.

## Links
- **CatalogBrowsingComponent**: Fetches the list of available services.
- **ServiceFilteringComponent**: Applies filters and retrieves filtered services.
- **QuoteCalculationComponent**: Retrieves pricing data for quote generation.
