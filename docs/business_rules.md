# Business Rules & Core Logic

This document defines the non-negotiable business rules governing attribution, revenue sharing, commissions, and operational logic in the MVP.

These rules are considered system-level constraints and must be enforced consistently across the platform.

---

## 1. Customer Attribution Rules

### 1.1 Initial Attribution
- When a customer registers or makes their first purchase using an Ambassador referral link or code, that customer is permanently attributed to that Ambassador.
- Attribution occurs at the time of first successful order placement or account creation (whichever happens first).

---

### 1.2 Lifetime Ownership
- Customer-to-Ambassador attribution is lifetime-based.
- Attribution does not expire.
- Attribution cannot be reassigned, transferred, or overridden manually, except by Platform Admin in exceptional cases (fraud or system error).

---

### 1.3 Direct Traffic Handling
- If a customer returns directly (without a referral link), attribution remains unchanged.
- All future purchases by the customer continue to generate earnings for the originally assigned Ambassador.

---

## 2. Revenue & Margin Model

### 2.1 Pricing Structure
- Products are sourced at wholesale cost from manufacturing partners.
- Products are sold at a platform-defined retail price.
- The difference between retail price and wholesale cost defines the **gross margin**.

---

### 2.2 Margin Ownership
- Gross margin is owned by the platform.
- Ambassador earnings are derived from a predefined share of this margin.
- Manufacturers do not receive commissions or revenue shares beyond the wholesale price.

---

## 3. Commission Logic (Ambassador Earnings)

### 3.1 Commission Basis
- Ambassador earnings are calculated per order line item.
- Earnings are based on a fixed or percentage-based share of the gross margin.
- Commission rules are defined at the product level by Platform Admin.

---

### 3.2 Lifetime Commission
- Ambassadors earn commissions on every qualifying purchase made by their attributed customers.
- This applies regardless of how the customer returns to the platform (direct, organic, or referral).

---

### 3.3 Eligibility Conditions
- Only completed and paid orders are commission-eligible.
- Cancelled, refunded, or failed orders generate no commissions.
- Commission eligibility is determined at order finalization.

---

## 4. Commission Records & Adjustments

### 4.1 Record Creation
- A commission record is generated automatically for every eligible order.
- Each record links:
  - Ambassador
  - Customer
  - Order
  - Product
  - Commission amount

---

### 4.2 Manual Adjustments
- Platform Admin may manually adjust commission records in exceptional cases.
- All adjustments must be logged with a reason.

---

## 5. Taxation & Compliance (MVP Scope)

### 5.1 Platform Responsibility
- The platform is responsible for its own tax obliga
