# Online College Canteen Food Ordering System

## Student Details
- Name: B JOEL BABU
- USN:NB25CSE073
- Assigned Question: Question 2 – Mobile and Web Applications Engineering

## 1. Introduction

Mobile and web applications are software applications that allow users to access services through smartphones, computers, and other devices.

A mobile application is installed on a smartphone. A web application runs through a web browser without requiring installation.

A Progressive Web Application (PWA) combines the features of mobile and web applications and provides an app-like experience.

For the proposed college canteen system, students need an easy way to view food items, place orders, make payments, and receive notifications.

## 2. Comparison of Mobile, Web, and PWA Applications

| Feature | Mobile Application | Web Application | PWA |
|---|---|---|---|
| Installation | Required | Not required | Optional |
| Accessibility | Mainly smartphones | Browser-based devices | Mobile and computers |
| Internet | Depends on app features | Usually required | Some features can work offline |
| Notifications | Supported | Browser-dependent | Supported on compatible browsers |
| Development | Platform-specific development may be needed | Web-based development | Web-based development |

## 3. Selection of Suitable Application

For the college canteen food-ordering system, a Progressive Web Application (PWA) is the most suitable choice.

### Reasons:
1. Students can access it through a web browser.
2. It does not require downloading from the Play Store.
3. It works on smartphones, tablets, and computers.
4. It supports notifications on compatible devices.
5. It can reduce development and maintenance costs.

Therefore, a PWA provides a convenient solution for the college canteen.

## 4. Major Functionalities

### 4.1 Food Menu Display
- Displays available food items.
- Shows food names, images, and prices.
- Displays food availability.

### 4.2 Online Food Ordering
- Students can select food items.
- Add items to the cart.
- Select quantity and confirm orders.

### 4.3 Online Payment
- Supports digital payment methods.
- Displays payment status.
- Generates order confirmation after successful payment.

### 4.4 Order Status Notifications
- Notifies students when an order is accepted.
- Updates students about food preparation.
- Sends a notification when food is ready.

## 5. Development Challenges

### 5.1 Internet Connectivity
Poor internet connectivity can affect menu loading, ordering, and payment processing.

### 5.2 Payment Security
Online payments require secure payment processing to protect students' financial information.

### 5.3 Browser and Device Compatibility
The application must work properly on different smartphones, operating systems, and web browsers.

## 6. Application Workflow Diagram

```text
        START
          |
          v
    Open PWA Application
          |
          v
      View Food Menu
          |
          v
    Select Food Items
          |
          v
       Add to Cart
          |
          v
      Place Order
          |
          v
      Make Payment
          |
          v
   Payment Successful?
       /       \
     No         Yes
     |            |
     v            v
 Retry Payment  Order Confirmed
                  |
                  v
             Prepare Food
                  |
                  v
          Send Ready Notification
                  |
                  v
          Student Collects Food
                  |
                  v
                 END
```

## 7. Conclusion

The Progressive Web Application is a suitable solution for the college canteen food-ordering system. It allows students to browse menus, place orders, make online payments, and receive notifications conveniently.

Although internet connectivity, payment security, and device compatibility are important challenges, they can be addressed through proper development and testing.

Thus, a PWA can make the college canteen ordering process faster, easier, and more efficient.
