# JetEngine Query Builder – Property Queries

## Overview

This example demonstrates how JetEngine Query Builder can be used to create advanced queries for a dynamic Property Listing system.

It continues from the Property Custom Post Type and Listing Grid created in Examples 01 and 02.

Instead of displaying all properties, Query Builder allows specific properties to be retrieved based on custom field values and other conditions.

## Data Source

**Post Type:** Properties

The query uses the custom fields created in Example 01:

| Field | Meta Key |
|---|---|
| Property Price | `property_price` |
| Location | `property_location` |
| Property Type | `property_type` |
| Bedrooms | `bedrooms` |
| Bathrooms | `bathrooms` |
| Property Size | `property_size` |

## Example Query

A property query could return properties matching conditions such as:

- Property type equals `house`
- Bedrooms greater than or equal to `3`
- Property price less than or equal to `500000`

## Query Logic

The conditions can be combined using an **AND** relation:

`property_type = house`

AND

`bedrooms >= 3`

AND

`property_price <= 500000`

This allows the Listing Grid to display only properties that match the required criteria.

## Integration with Listing Grid

The custom query can be connected to the JetEngine Listing Grid created in Example 02.

This separates the data retrieval logic from the visual listing design and makes the property system easier to maintain and extend.

## Tools Used

- WordPress
- Crocoblock
- JetEngine
- JetEngine Query Builder
- JetEngine Listing Grid
- Elementor Pro

## Purpose

The purpose of this example is to demonstrate how structured WordPress data can be queried dynamically using JetEngine Query Builder to create more advanced and scalable property listing functionality.
