# User Roles Definition

This document defines all user roles in the platform, their responsibilities, permissions, and boundaries.  
Each role is intentionally minimal in the MVP to reduce complexity and risk.

---

## 1. Overview of Roles

The platform supports three primary user roles in the MVP:

1. Ambassador
2. Customer
3. Platform Admin

All users are created under a single user system and differentiated by role.

---

## 2. Ambassador

### 2.1 Role Description
An Ambassador is an individual who promotes products through personal or professional networks and earns income by referring customers to the platform.

Ambassadors do not own inventory, handle payments, or manage logistics.

---

### 2.2 Core Responsibilities
- Select products to promote
- Share referral links or referral codes
- Build trust-based relationships with customers
- Drive repeat purchases through relationship continuity

---

### 2.3 Platform Capabilities
Ambassadors can:
- Register and log in
- Access their unique referral link or code
- View a list of customers they have referred
- View a basic summary of earned commissions (read-only)
- Access product content provided by the platform

---

### 2.4 Explicit Limitations
Ambassadors cannot:
- Set product prices
- Edit product information
- Handle payments or refunds
- Withdraw earnings automatically (manual process in MVP)
- Create sub-accounts or recruit other Ambassadors (no multi-level structure in MVP)

---

## 3. Customer

### 3.1 Role Description
A Customer is an end user who purchases products through the platform, either directly or via an Ambassador referral.

Customers may or may not be associated with an Ambassador.

---

### 3.2 Core Responsibilities
- Browse products
- Place orders
- Complete payments
- Receive products through the defined fulfillment process

---

### 3.3 Platform Capabilities
Customers can:
- Register and log in
- Browse the product catalog
- Place orders and complete checkout
- View their order history

---

### 3.4 Explicit Limitations
Customers cannot:
- Refer other users
- Earn commissions
- Access Ambassador tools or earnings data

---

## 4. Platform Admin

### 4.1 Role Description
The Platform Admin is responsible for operating, monitoring, and controlling the marketplace.

Admins represent the platform and have full system access.

---

### 4.2 Core Responsibilities
- Manage users and roles
- Approve or deactivate Ambassadors
- Create and manage products
- Define pricing and margin structures
- Monitor orders and commissions
- Handle disputes and quality issues

---

### 4.3 Platform Capabilities
Admins can:
- Access the administrative dashboard
- Create, edit, and deactivate products
- View all users, orders, and commission records
- Manually adjust commission records if required
- Export basic operational data

---

## 5. Role Boundaries & Principles

- A single user account has exactly one active role in the MVP.
- Role switching is not supported in the MVP.
- All permissions are role-based and enforced at the system level.
- Any capability not explicitly listed is considered disallowed by default.

---

## 6. Future Roles (Out of MVP Scope)
The following roles are intentionally excluded from the MVP:

- Manufacturer / Supplier accounts
- Logistics partners
- Financial operators
- Team leaders or Ambassador managers
