# JetSmartFilters – Property Filtering

## Overview

This example demonstrates how JetSmartFilters can be used to filter a dynamic Property Listing Grid in WordPress.

It continues from the Property Custom Post Type, Listing Grid and Query Builder created in Examples 01, 02 and 03.

The goal is to allow visitors to narrow property results based on custom field values without reloading the page.

## Data Source

**Post Type:** Properties

The filters use the custom fields created in Example 01:

| Filter | Meta Key | Suggested Filter Type |
|---|---|---|
| Property Type | `property_type` | Select |
| Location | `property_location` | Select / Search |
| Bedrooms | `bedrooms` | Checkboxes / Range |
| Bathrooms | `bathrooms` | Checkboxes / Range |
| Property Price | `property_price` | Range |
| Property Size | `property_size` | Range |

## Example Filter Setup

A user could filter the property results by:

- Property type: House
- Location: London
- Minimum bedrooms: 3
- Maximum price: 500000

The Listing Grid would then display only properties matching the selected criteria.

## Filter Flow

`JetSmartFilters`

↓

`JetEngine Query / Listing Grid`

↓

`Filtered Property Results`

The filters can update results dynamically using AJAX, giving users a faster browsing experience without full-page reloads.

## Tools Used

- WordPress
- Crocoblock
- JetEngine
- JetSmartFilters
- JetEngine Listing Grid
- Elementor Pro

## Purpose

The purpose of this example is to demonstrate how JetSmartFilters can be connected to structured JetEngine data to create interactive and user-friendly filtering for dynamic WordPress websites.
