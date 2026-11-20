# Mobile and Web Applications Engineering – Online Canteen Food Ordering System

**Name:** Devangana.A 
**USN:** NB25CSE095 
**Case Study:** Mobile and Web Applications Engineering

## 1. Introduction

Mobile and Web Applications Engineering is the process of designing, developing, testing, and
maintaining applications that allow users to access services through mobile devices and web browsers.

A mobile application is software designed to run on smartphones and tablets. A web application is
accessed through a web browser using the internet without requiring users to install separate software.

A Progressive Web Application (PWA) combines features of both mobile and web applications. It can
be accessed through a browser, installed on a device, and provides features such as offline support and notifications.

In this case study, a college wants to develop an online canteen food-ordering system that allows
students to view food menus, place orders, make online payments, and receive notifications when their orders are ready.

The proposed system will reduce waiting time, improve order management, and make the canteen
service more convenient for students.

## 2. Problem Analysis

Currently, students may have to visit the canteen physically, stand in queues, check food availability, and wait for their orders.

This creates several problems:

- Long waiting times during college breaks.
- Difficulty in checking available food items.
- Manual handling of orders may cause mistakes.
- Cash payments can slow down the ordering process.
- Students may not know when their orders are ready.

To overcome these problems, an online canteen food-ordering application is proposed.

## 3. Comparison of Mobile, Web, and Progressive Web Applications

Three approaches can be considered for developing the canteen application.

### A. Mobile Application

A mobile application is developed specifically for smartphones using technologies such as Android or iOS development frameworks.

**Advantages:**
- Provides a smooth user experience.
- Can access device features such as cameras and notifications.
- Can offer better offline capabilities.

**Disadvantages:**
- Requires installation from an app store or another distribution method.
- Development and maintenance may be more expensive.
- Separate platform support may increase development effort.

### B. Web Application

A web application runs through browsers such as Google Chrome, Firefox, and Microsoft Edge.

**Advantages:**
- No installation is required.
- Can be accessed from different devices.
- Updates can be deployed centrally.
- Easier to maintain a single application.

**Disadvantages:**
- Requires an internet connection for most functionality.
- Some device features may have limited access.
- Browser compatibility must be considered.

### C. Progressive Web Application (PWA)

A Progressive Web Application combines the advantages of mobile and web applications. It runs through a browser but can also be installed on a smartphone like a normal application.

**Advantages:**
- Can be accessed through a web browser.
- Can be installed on supported devices.
- Supports push notifications on supported platforms and browsers.
- Can provide limited offline functionality.
- A single application can support multiple platforms.

**Disadvantages:**
- Some device features may have limited support.
- Push notification support varies across platforms.
- Offline functionality requires additional development.

### Comparison Table

| Feature | Mobile Application | Web Application | PWA |
|---------|--------------------|-----------------|-----|
| Installation | Required | Not required | Optional |
| Accessibility | Mobile devices | Web browsers | Browsers and supported devices |
| Offline Support | Good | Limited | Partial |
| Notifications | Supported | Browser-dependent | Supported on compatible platforms |
| Development Cost | Higher | Moderate | Moderate |
| Updates | App updates | Centralized | Centralized |

## 4. Selection of Suitable Application Type

For the proposed college canteen food-ordering system, a **Progressive Web Application (PWA)** is the most suitable choice.

The reasons for selecting PWA are:

1. **Easy Accessibility:** Students can access the application using a browser without downloading it.
2. **Installation Support:** Students can add the application to their mobile home screen for quick access.
3. **Cost Effective:** A single application can work across different devices and platforms.
4. **Push Notifications:** Students can receive notifications when their food orders are ready.
5. **Offline Support:** Previously loaded menu information can be made available even when the internet connection is temporarily unavailable.
6. **Easy Maintenance:** Developers can update the application centrally without requiring users to manually download updates.

Therefore, PWA provides a good balance between accessibility, cost, performance, and user convenience.

## 5. Major Functionalities of the Proposed System

The online canteen food-ordering system should provide the following major functionalities.

### 1. Food Menu Browsing

- Students can view the available food items.
- Each food item displays its name, price, and description.
- Food items can be organized into categories such as breakfast, lunch, snacks, and beverages.
- Students can check food availability before ordering.

### 2. Online Food Ordering

- Students can select food items from the menu.
- They can add multiple items to their shopping cart.
- They can increase or decrease item quantities.
- The application calculates the total bill automatically.
- Students can confirm and submit their orders.

### 3. Online Payment

- Students can pay through supported online payment methods.
- The system displays the total amount before payment.
- Payment status is recorded after the transaction.
- A payment confirmation is displayed after successful payment.

### 4. Order Tracking and Notifications

- Students can view their order status.
- The system displays statuses such as Pending, Preparing, and Ready.
- Students receive notifications when their orders are ready for collection.
- This reduces unnecessary waiting and crowding at the canteen.

## 6. Development Challenges

While developing the proposed application, developers may face the following challenges.

### 1. Security and Payment Integration

The application handles student information and online payments. Developers must ensure
secure communication, protect user data, and integrate reliable payment gateways.

### 2. Network Connectivity

Students may experience slow or unstable internet connections on campus. Developers must optimize
the application and provide caching for previously loaded information.

### 3. Browser and Device Compatibility

The application must work properly on different smartphones, screen sizes, operating systems, and
browsers. Developers must test the PWA across supported devices and ensure that important features
such as notifications work correctly.

## 7. Simple Application Workflow Diagram

The following diagram represents the working process of the proposed online canteen food-ordering system.

```text
        +----------------------+
        |     Student Opens    |
        |     Canteen PWA      |
        +----------------------+
                   |
                   v
        +----------------------+
        |    View Food Menu    |
        +----------------------+
                   |
                   v
        +----------------------+
        |   Select Food Items  |
        +----------------------+
                   |
                   v
        +----------------------+
        |   Add Items to Cart  |
        +----------------------+
                   |
                   v
        +----------------------+
        |   Confirm the Order  |
        +----------------------+
                   |
                   v
        +----------------------+
        |    Online Payment    |
        +----------------------+
                   |
                   v
        +----------------------+
        |   Order Confirmed    |
        +----------------------+
                   |
                   v
        +----------------------+
        |  Canteen Prepares    |
        |       the Food       |
        +----------------------+
                   |
                   v
        +----------------------+
        |  Notification Sent   |
        |   Order is Ready     |
        +----------------------+
                   |
                   v
        +----------------------+
        | Student Collects    |
        |      the Order      |
        +----------------------+
                   |
                   v
        +----------------------+
        |        End           |
        +----------------------+
```

## 8. Benefits of the Proposed System

The proposed online canteen food-ordering system provides several benefits:

- **Reduced Waiting Time:** Students can place orders before reaching the canteen.
- **Convenience:** Food items and prices can be viewed from anywhere on campus.
- **Improved Order Management:** Digital orders reduce manual errors and confusion.
- **Faster Payments:** Online payments reduce the need for cash transactions.
- **Better Communication:** Notifications inform students when their orders are ready.
- **Easy Accessibility:** PWA allows students to access the system using different devices.

## 9. Conclusion

The online canteen food-ordering system can improve the efficiency of college canteen services by
replacing traditional manual ordering with a digital platform.

After comparing mobile applications, web applications, and Progressive Web Applications, PWA is 
selected as the most suitable solution because it provides easy accessibility, installation support, push
notifications, and cost-effective development.

The proposed system allows students to browse food menus, place orders, make online payments, and
receive notifications when their food is ready.

Thus, implementing a Progressive Web Application can reduce waiting time, improve student
convenience, and make canteen operations more efficient.
The proposed system allows students to browse food menus, place orders, make online payments, and receive notifications when their food is ready.

Thus, implementing a Progressive Web Application can reduce waiting time, improve student convenience, and make canteen operations more efficient.
