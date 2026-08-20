# JetEngine Relations – Properties & Agents

## Overview

This example demonstrates how JetEngine Relations can be used to connect different content types in WordPress.

The example extends the Property Listing system by introducing an **Agents** Custom Post Type and creating a relationship between properties and agents.

## Content Types

### Properties

The existing Properties Custom Post Type contains property information such as:

- Property title
- Property price
- Location
- Property type
- Bedrooms
- Bathrooms
- Property size

### Agents

A separate Agents Custom Post Type can contain:

- Agent name
- Profile image
- Email address
- Phone number
- Agency name
- Biography

## Relation Structure

A JetEngine relation connects the two post types:

`Agent`

↓

`Properties`

The relationship can be configured as:

**One to Many**

This means one agent can manage multiple properties, while each property is assigned to one agent.

## Example Relationship

`Agent: John Smith`

↓

- Property A
- Property B
- Property C

The relationship is stored and managed using JetEngine Relations rather than manually duplicating agent information inside every property.

## Dynamic Display

On an individual property page, related agent information can be displayed dynamically, including:

- Agent name
- Agent photo
- Phone number
- Email address
- Agency name

An agent profile page can also dynamically display all properties assigned to that agent.

## Benefits

Using relations helps:

- Avoid duplicate data
- Keep property and agent information separate
- Create reusable content structures
- Display related content dynamically
- Build scalable WordPress data models

## Tools Used

- WordPress
- Crocoblock
- JetEngine
- JetEngine Relations
- Elementor Pro
- JetEngine Listing Grid

## Purpose

The purpose of this example is to demonstrate how JetEngine Relations can connect different WordPress content types and create structured relationships between dynamic data.
