# SAP RAP Unmanaged Sales Order Management

## Project Overview

This project is an SAP RAP (RESTful Application Programming) based Sales Order Management application developed using ABAP Cloud.

The application follows the RAP Unmanaged Scenario and implements Sales Order Header and Sales Order Item management using CDS Views, Behavior Definitions, Behavior Implementations, EML, and OData services.

## Technologies Used

- SAP ABAP Cloud
- SAP RAP (RESTful Application Programming)
- CDS Views
- Behavior Definition
- Behavior Implementation
- Entity Manipulation Language (EML)
- OData V4
- SAP Fiori Elements
- Eclipse ADT

## Project Architecture

The application consists of the following major components:

### 1. Database Tables

- Sales Order Header
- Sales Order Item

The header and item tables store the sales order information and maintain the relationship between sales order header and item data.

### 2. CDS Views

The project uses CDS views to expose the Sales Order Header and Sales Order Item data.

The CDS layer includes:

- Interface CDS Views
- Consumption CDS Views
- Associations and compositions between Header and Item

### 3. RAP Behavior

The project uses the RAP Unmanaged Scenario.

The behavior layer defines operations and business logic for the Sales Order Header and Item entities.

The implementation includes:

- Create
- Update
- Delete
- Read
- Actions
- Validations
- Determinations

### 4. Behavior Implementation

In the unmanaged RAP scenario, the business logic is implemented manually using behavior pool classes.

The implementation uses EML to perform entity operations and custom logic to process Sales Order Header and Item data.

### 5. Service Layer

The application exposes the RAP business object through:

- Service Definition
- OData V4 Service Binding

This allows the business object to be consumed by a UI or other OData clients.

## Key RAP Concepts Demonstrated

- RAP Unmanaged Scenario
- Root and Child Entities
- Composition
- Associations
- Behavior Definition
- Behavior Implementation
- EML
- Validations
- Determinations
- Actions
- Draft Handling
- OData V4 Service
- Fiori Elements Integration

## Project Structure

text
SAP RAP Sales Order Management
│
├── Database Tables
│   ├── Sales Order Header
│   └── Sales Order Item
│
├── CDS Views
│   ├── Interface Views
│   └── Consumption Views
│
├── Behavior
│   ├── Behavior Definition
│   └── Behavior Implementation
│
├── Utility
│   └── Sales Order Utility Class
│
├── Metadata Extensions
│
└── Service
    ├── Service Definition
    └── Service Binding
