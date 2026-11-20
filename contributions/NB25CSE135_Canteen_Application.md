# Mobile and Web Applications Engineering
## Case Study: Online Canteen Food Ordering System

**Student Name:** HARI PRASAD K  
**USN:** NB25CSE135  
**Department:** Computer Science and Engineering  
**Topic:** Mobile and Web Applications Engineering

---

## 1. Introduction

Mobile and web applications are software applications designed to provide services to users through smartphones, tablets and computers.

A college canteen usually handles food orders manually, which can lead to long queues, delays and confusion during busy hours.

To solve this problem, the college plans to develop an Online Canteen Food Ordering System. This system allows students to view food items, place orders, make online payments and receive notifications when their orders are ready.

A suitable application can make the ordering process faster, easier and more convenient.

## 2. Problem Analysis

The traditional canteen ordering process has several problems:

- Students have to stand in long queues to place orders.
- Students may not know which food items are available.
- Manual order management can lead to mistakes.
- Managing payments manually takes additional time.
- Students may have to wait near the counter to know whether their orders are ready.

Therefore, a digital food ordering system is required to improve the canteen's efficiency.

## 3. Comparison of Mobile, Web and Progressive Web Applications

### A. Mobile Application

A mobile application is software developed specifically for smartphones and installed through platforms such as Google Play Store or Apple App Store.

**Advantages:**
- Can provide push notifications.
- Can use mobile device features.
- Offers a convenient mobile experience.

**Limitations:**
- Requires installation.
- Development and maintenance may be required for multiple platforms.
- App updates may require additional effort.

### B. Web Application

A web application is accessed through a web browser using an internet connection. Users do not need to install it.

**Advantages:**
- Accessible from different devices.
- No installation is required.
- Easy to update and maintain.

**Limitations:**
- Some features may depend on browser support.
- Internet connectivity is generally required.
- Browser-based notifications may have limitations.

### C. Progressive Web Application (PWA)

A Progressive Web Application combines features of websites and mobile applications. It runs through a web browser but can also be installed on supported devices.

**Advantages:**
- Can be accessed through a web browser.
- Can be installed on supported devices.
- Supports push notifications on supported browsers and platforms.
- Can provide limited offline functionality.
- A single application can serve mobile and desktop users.

**Limitations:**
- Some device features are restricted compared with native applications.
- Certain features differ between browsers and operating systems.
- Offline functionality requires proper implementation.

### Comparison Table

| Feature | Mobile App | Web App | PWA |
|---|---|---|---|
| Installation | Required | Not required | Optional |
| Accessibility | Mobile devices | Browser-based devices | Mobile and desktop browsers |
| Notifications | Supported | Browser-dependent | Supported on compatible platforms |
| Offline support | Can be implemented | Limited | Can be implemented |
| Maintenance | Platform-dependent | Centralized | Centralized |
| Development cost | Can be higher | Moderate | Moderate |

## 4. Proposed Solution

For the college canteen, a **Progressive Web Application (PWA)** is the most suitable choice.

A PWA provides the convenience of a website along with selected features of a mobile application.

Students can open the application using a browser or install it on supported devices. They can browse the food menu, select items, place orders, make payments and receive notifications.

The canteen staff can manage food availability and update order statuses through an administrative dashboard.

### Reasons for Selecting PWA

1. Students do not need to download an application from an app store.
2. It works across supported mobile and desktop browsers.
3. It can provide notifications about order status.
4. It can reduce development and maintenance effort through a shared application.
5. It provides a simple and convenient user experience.

## 5. Major Functionalities

The proposed canteen ordering application includes the following functionalities:

### 1. Food Menu Display

- Displays available food items.
- Shows food names, images and prices.
- Allows students to check food availability.
- Organizes food items into different categories.

### 2. Online Food Ordering

- Allows students to select food items.
- Provides an option to add items to a cart.
- Displays the total order amount.
- Allows students to confirm their orders.

### 3. Online Payment

- Supports digital payment methods through a payment gateway.
- Displays payment confirmation.
- Maintains transaction details.
- Provides an order receipt.

### 4. Order Tracking and Notifications

- Displays the current order status.
- Notifies students when an order is accepted.
- Updates students when food preparation is completed.
- Notifies students when their order is ready for collection.

## 6. Application Workflow Diagram

The following diagram explains how the proposed canteen ordering application works.

                    [START]
                       |
                       v
              [Open Canteen PWA]
                       |
                       v
                [View Food Menu]
                       |
                       v
              [Select Food Items]
                       |
                       v
             [Add Items to Cart]
                       |
                       v
                [Confirm Order]
                       |
                       v
             [Make Online Payment]
                       |
                       v
             [Payment Successful?]
                  /          \
                No            Yes
                |              |
                v              v
          [Retry Payment]  [Order Sent to
                |           Canteen]
                |              |
                +----->        v
                       [Food Preparation]
                              |
                              v
                     [Update Order Status]
                              |
                              v
                     [Send Notification]
                              |
                              v
                    [Student Collects Order]
                              |
                              v
                            [END]

## Challenges Faced During Development

### 1. Internet Connectivity
**Challenge:** Students may experience poor internet connectivity while placing orders.

**Solution:** The PWA can cache important information, such as the food menu, so students can access it even with limited connectivity.

### 2. Online Payment Security
**Challenge:** Online payments must be handled securely to protect student information.

**Solution:** Use a secure payment gateway and encrypted communication to protect payment details.

### 3. Real-Time Order Management
**Challenge:** Updating order status quickly can be difficult during busy hours.

**Solution:** Provide real-time order status updates and notifications so students know when their food is ready.


## 7. Development Challenges

The development of the canteen ordering application may involve the following challenges:

### 1. Internet Connectivity

Students may experience poor internet connectivity while placing orders or making payments.

**Solution:** Provide clear error messages, retry options and suitable offline support for non-payment features.

### 2. Payment Security

Online payments involve sensitive transaction information. Improper payment handling may cause security problems.

**Solution:** Use a trusted payment gateway, secure HTTPS communication and proper payment verification.

### 3. Real-Time Order Management

During peak hours, the canteen may receive many orders simultaneously. Updating order status accurately can become difficult.

**Solution:** Use a centralized database and real-time status updates to manage orders efficiently.

## 8. Benefits of the Proposed System

- Reduces long queues in the college canteen.
- Saves time for students and canteen staff.
- Makes food ordering convenient.
- Reduces manual errors.
- Provides transparent order status updates.
- Improves overall canteen management.

## 9. Conclusion

The Online Canteen Food Ordering System can improve the traditional food ordering process in a college.

Among mobile applications, web applications and Progressive Web Applications, a PWA is a suitable solution because it provides browser accessibility, optional installation and supported notification features.

By implementing this system, students can conveniently order food, make digital payments and receive updates about their orders. It also helps canteen staff manage orders more efficiently.

Thus, a Progressive Web Application can provide a simple, accessible and effective solution for modern college canteens.

---

**End of Assignment**
