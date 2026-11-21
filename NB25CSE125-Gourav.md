# Online Canteen Food-Ordering System

**Name:** Gourav
**USN:** NB25CSE125
**Case Study:** 2 – Mobile and Web Applications Engineering

## Introduction

A **mobile application** is installed on a phone from an app store and can use device features such as notifications and the camera. A **web application** runs in a browser and needs no installation. A **Progressive Web Application (PWA)** is a web app that behaves like a mobile app. It can be installed on the home screen, work with poor internet, and send push notifications.

## Problem Analysis

The college wants an online canteen system where students can:
- browse the menu,
- place orders,
- make payments,
- get notified when the order is ready.

Currently, students stand in long queues, orders are taken manually, and mistakes and delays are common. The college needs a solution that works on every student's phone, is cheap to build, and is easy to maintain.

## Proposed Solution

### Comparison of Approaches

| Feature | Mobile App | Web App | PWA |
|---|---|---|---|
| Installation | Required (app store) | Not required | Optional (add to home screen) |
| Works on Android and iOS | Needs separate builds | Yes, any browser | Yes |
| Push notifications | Yes | Limited | Yes |
| Offline support | Yes | No | Yes |
| Development cost | High | Low | Low to medium |
| Updates | User must update | Instant | Instant |

### Selected Choice: Progressive Web Application (PWA)

**Justification:**
1. One codebase works on all phones and laptops, so development is cheaper.
2. Students do not need to download a large app, which suits a college of thousands of users.
3. Push notifications can tell the student when the order is ready.
4. Updates reach everyone instantly, with no app store approval.
5. It still works on a weak campus network.

### Four Major Functionalities
1. **Menu browsing:** view items, prices, and availability.
2. **Order placement:** add items to a cart and confirm the order.
3. **Online payment:** pay through UPI or a payment gateway.
4. **Order-ready notification:** the student gets an alert when the food is ready.

### Application Workflow

```
Student Login
     |
Browse Menu
     |
Add Items to Cart
     |
Place Order
     |
Make Payment
     |
Canteen Staff Receives Order
     |
Food Prepared
     |
"Order Ready" Notification
     |
Student Collects Food
```

## Benefits and Challenges

### Benefits
- No queues, so students save time.
- Fewer order mistakes.
- Digital payment records make accounting easier.

### Three Development Challenges
1. **Payment security:** the system must handle transactions safely using a trusted payment gateway and HTTPS.
2. **Peak-hour load:** many students order during breaks, so the server must handle heavy traffic without crashing.
3. **Notification reliability:** push notifications can be limited on some browsers, especially iOS, so a fallback such as SMS may be needed.

## Conclusion

A Progressive Web App is the most suitable choice for the college canteen system. It combines the wide reach of a web app with the notifications and installability of a mobile app, at a lower cost than building separate mobile apps. With secure payments and a scalable backend, it can make canteen ordering faster and easier for students and staff.
