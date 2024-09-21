---
id: usage-db-component
title: Usage Database Component
sidebar_label: Usage Database Component
---

# Usage Database Component

*Component Identifier:* `UsageDBComponent`

*Title:* Usage Database

## Properties
- **ServiceUsage**:
  - **Type**: Object
  - **Description**: Logs of service usage by different guests.

## Methods
- **LogServiceUsage()**: Logs the usage of a service by a guest.
- **RetrieveUsageData()**: Provides usage data for the **QuoteGenerationComponent** and **ServiceBackendComponent**.

## Links
- **QuoteGenerationComponent**: Retrieves usage data for generating service quotes.
- **ServiceBackendComponent**: Logs and retrieves usage data as part of backend processes.
