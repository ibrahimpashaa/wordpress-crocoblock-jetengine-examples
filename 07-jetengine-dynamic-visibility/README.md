# JetEngine Dynamic Visibility – Property Listings

## Overview

This example demonstrates how JetEngine Dynamic Visibility can be used to conditionally display content in a dynamic Property Listing system.

Instead of showing every element to every user, content can be displayed or hidden based on property data, field values, user information or other conditions.

## Example Scenario

The existing Property Listing contains fields such as:

- Property price
- Property type
- Location
- Bedrooms
- Bathrooms
- Property size

We can use Dynamic Visibility to control when specific property information appears.

## Example 1 – Featured Property Badge

A property can contain a field:

`featured_property`

Possible values:

- Yes
- No

The **Featured Property** badge is displayed only when:

`featured_property = yes`

## Example 2 – Display Price When Available

The property price element can be displayed only when:

`property_price` is not empty

If no price exists, the element can remain hidden instead of displaying an empty field.

## Example 3 – Property Type Conditional Content

Different information can be displayed depending on the property type.

For example:

`property_type = house`

↓

Display:

- Garden information
- Number of floors
- Parking information

Other property types can display different information.

## Visibility Flow

`Property Data`

↓

`Dynamic Visibility Condition`

↓

`Condition TRUE`

↓

`Display Element`

If the condition is false, the element remains hidden.

## Where Dynamic Visibility Can Be Used

Dynamic Visibility can control:

- Elementor widgets
- Containers
- Dynamic fields
- Property badges
- Buttons
- Forms
- Listing elements
- User-specific content

## Benefits

Dynamic Visibility helps:

- Prevent empty fields from appearing
- Show relevant information only
- Create conditional layouts
- Personalise dynamic content
- Reduce unnecessary interface elements
- Build more flexible WordPress templates

## Tools Used

- WordPress
- Crocoblock
- JetEngine
- Dynamic Visibility
- Elementor Pro
- JetEngine Listing Grid

## Purpose

The purpose of this example is to demonstrate how conditional visibility can make dynamic WordPress templates more intelligent by displaying content only when predefined conditions are satisfied.
