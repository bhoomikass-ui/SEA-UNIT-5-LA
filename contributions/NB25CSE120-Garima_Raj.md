### Mobile and Web Applications Engineering for an Online Canteen Food-Ordering System

## Student Details

**Name:** GARIMA RAJ
**USN:** NB25CSE120
**Assigned Case Study:** Question 2: Mobile and Web Applications Engineering


### 1. Introduction to Mobile and Web Applications

A college plans to develop an online canteen food-ordering system that allows students to browse food menus, place orders, make online payments, and receive notifications when their orders are ready.

Mobile and web applications can be used to develop this system.

* Mobile Application: An application designed specifically for smartphones and tablets. It is installed through platforms like Google Play Store or Apple App Store.

* Web Application: An application accessed through a web browser using the internet. It does not require installation.

* Progressive Web Application (PWA): A web application that provides features similar to mobile applications, such as home-screen installation, offline support, and push notifications.



### 2. Comparison of Mobile, Web, and PWA Approaches

| Features         | Mobile App                              | Web App                         | PWA                               |
| ---------------- | --------------------------------------- | ------------------------------- | --------------------------------- |
| Installation     | Required                                | Not required                    | Optional                          |
| Accessibility    | Through mobile devices                  | Through browsers                | Browser and home screen           |
| Performance      | High                                    | Depends on browser and internet | Good                              |
| Offline Support  | Possible                                | Limited                         | Supported through caching         |
| Notifications    | Supported                               | Limited                         | Supported on compatible platforms |
| Development Cost | High                                    | Moderate                        | Moderate                          |
| Maintenance      | Separate platform updates may be needed | Centralized                     | Centralized                       |



### 3. Selection of Suitable Application Type

Recommended: Progressive Web Application (PWA)

For the college canteen food-ordering system, a Progressive Web Application (PWA) is the most suitable choice.

Justification:

* Easy Accessibility: Students can access the application through a browser without downloading it.

* Installation Option: Students can add the application to their mobile home screen like a normal mobile app.

* Cross-Platform Compatibility: It works on different devices such as smartphones, tablets, and computers.

* Cost-Effective: A single application can serve multiple platforms, reducing development and maintenance costs.

* Push Notifications: Students can receive notifications when their orders are accepted, prepared, or ready for collection.

* Offline Support: Cached menu information and basic application pages can be accessed even with limited internet connectivity.

Therefore, PWA provides a balance between accessibility, performance, cost, and mobile application features.



### 4. Four Major Functionalities

1\. Menu Browsing

* Displays available food items with names, prices, images, and descriptions.

* Allows students to view different food categories.

* Displays item availability and updates the menu regularly.

2\. Order Placement

* Allows students to select food items and add them to the cart.

* Provides options to increase or decrease quantities.

* Calculates the total bill.

* Generates an order confirmation after successful placement.

3\. Online Payment

* Supports digital payment methods such as UPI, debit cards, and net banking.

* Provides secure payment processing through a payment gateway.

* Generates payment confirmation and transaction details.

4\. Order Tracking and Notifications

* Allows students to track their order status.

* Sends notifications when an order is confirmed, being prepared, or ready.

* Helps students collect their orders without unnecessary waiting.



### 5\. Three Major Development Challenges

1\. Security and Payment Integration

* Protecting students' personal and payment information.

* Integrating secure payment gateways.

* Preventing unauthorized access and fraudulent transactions.

2\. Real-Time Order Management

* Updating order status immediately.

* Managing multiple orders during peak hours.

* Avoiding duplicate orders and incorrect order processing.

3\. Cross-Platform Compatibility and Network Issues

* Ensuring the application works properly on different browsers and devices.

* Handling slow or unstable internet connections.

* Providing reliable notifications across supported platforms.



### 6. Simple Application Workflow Diagram

The following diagram represents the working process of the online canteen food-ordering system.

6. Simple Application Workflow Diagram
+-------------------------------------------------------------------+
|                        STUDENT (PWA Client)                       |
+-------------------------------------------------------------------+
                                 |
                                 v
               [1. Open PWA via URL / QR Code & Login]
                                 |
                                 v
            [2. Browse Live Menu & Add Items to Cart]
                                 |
                                 v
                  [3. Review Order & Checkout]
                                 |
                                 v
             [4. Make Digital Payment (UPI / Card)]
                                 |
                 +---------------+---------------+
                 | (Payment Failed)              | (Payment Success)
                 v                               v
     [Show Error / Retry]          [Generate Order ID & Digital Token]
                                                 |
                                                 v
+-------------------------------------------------------------------+
|                   BACKEND SERVER & DATABASE                       |
|        (Verify Payment -> Update Stock -> Route to Kitchen)       |
+-------------------------------------------------------------------+
                                 |
                                 v
+-------------------------------------------------------------------+
|                  CANTEEN KITCHEN DASHBOARD                        |
+-------------------------------------------------------------------+
                                 |
                                 v
           [5. Kitchen Receives Order -> Status: "Preparing"]
                                 |
                                 v
          [6. Food Prepared -> Staff Marks "Ready for Pickup"]
                                 |
                                 v
             [7. Server Triggers Push Notification to Student]
                                 |
                                 v
      [8. Student Shows Digital Token at Counter & Collects Food]
                                 |
                                 v
              [9. Staff Marks Order as "Completed"]



### 7. Conclusion

The Progressive Web Application (PWA) is the most suitable solution for the college canteen food-ordering system. It provides easy accessibility, cross-platform compatibility, installation options, and push notifications at a lower development cost. Its four major functionalities—menu browsing, order placement, online payment, and order tracking—make the food-ordering process convenient and efficient for both students and canteen staff.
