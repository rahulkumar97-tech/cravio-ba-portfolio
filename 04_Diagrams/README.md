# Cravio – System & Process Diagrams

This folder contains the diagrams created to visually represent the **Cravio – Online Food Delivery Platform** system, data relationships, user interactions, and business processes.

These diagrams support the requirements documentation and help different stakeholders understand the proposed solution.

---

## Diagrams Included

### 1. UML Use Case Diagram

The UML Use Case Diagram represents the major interactions between Cravio and its external actors.

**Actors:**

* Customer
* Restaurant
* Delivery Partner
* Admin
* Payment Gateway

**Purpose:**
To visualize the major system functionalities and the interactions between users/external systems and the Cravio platform.

---

### 2. Entity Relationship Diagram (ERD)

The ERD represents the major entities and their relationships within the Cravio platform.

**Key Entities:**

* Customer
* Restaurant
* Food Item
* Order
* Order Item
* Payment
* Delivery Partner
* Delivery
* Admin

**Purpose:**
To provide a high-level view of the data structure and relationships required to support the platform.

---

### 3. BPMN – Order Fulfillment & Delivery Process

The BPMN diagram represents the business process from order placement through payment, restaurant processing, delivery assignment, and final delivery.

**Major Process Stages:**

```text id="gk3z8j"
Customer Places Order
        ↓
Payment Processing
        ↓
Restaurant Receives Order
        ↓
Restaurant Prepares Order
        ↓
Delivery Partner Assigned
        ↓
Order Picked Up
        ↓
Order Delivered
```

**Purpose:**
To visualize the end-to-end business process and responsibilities of different participants.

---

## Diagram Tools

The diagrams were created using **Draw.io (diagrams.net)** and are maintained as supporting artifacts for the Cravio BA portfolio project.

---

## Relationship with Requirements

The diagrams help translate documented requirements into visual representations:

```text id="v9j5cx"
Requirements
     ↓
UML / ERD / BPMN
     ↓
User Stories
     ↓
Development & Testing
```

This provides a clearer connection between business requirements, system behavior, data structure, and business processes.
