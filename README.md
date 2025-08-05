# OOP‑based Simple E‑Commerce (Java)

A small, object‑oriented Java demo illustrating core e‑commerce components—Products (Physical and Digital), Customer, ShoppingCart, Order, Payment, Inventory—with OOP principles: abstraction, inheritance, polymorphism, encapsulation.

---

## ​ Project Overview

This project models a basic e‑commerce platform using Java:

- **Product hierarchy**: `Product` superclass with `PhysicalProduct` and `DigitalProduct`
- **Inventory**: tracks stock quantities
- **Cart & Order**: `ShoppingCart` holds items; `Order` encapsulates checkout flow and payment
- **Payment methods**: abstract `Payment`, with `CreditCardPayment`, `PayPalPayment` implementations
- Core design emphasizes OOP principles, allowing easy extension (e.g. adding Subscription products or new payment types) :contentReference[oaicite:1]{index=1}

---

## ​ Getting Started

### Prerequisites

- JDK 8+ (Java 11 recommended)  
- Maven (if using build tools)  
- IDE: IntelliJ IDEA, Eclipse, or similar

### Installation & Build

```bash
git clone <repo‑url>
cd ecommerce‑oop-demo
mvn compile
