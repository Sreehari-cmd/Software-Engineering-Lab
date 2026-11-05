# Online Food Delivery App – Test Case Report

## 1. Project Information

| Field | Details |
|---|---|
| Project Name | Online Food Delivery App |
| Project Type | Software Engineering Lab |
| Repository | [Software-Engineering-Lab](https://github.com/Sreehari-cmd/Software-Engineering-Lab) |
| Purpose | To define test cases for checking the functional requirements of the Online Food Delivery App |

## 2. Modules Identified

1. User Registration and Login
2. Restaurant and Food Search
3. Menu Viewing
4. Shopping Cart
5. Order Placement
6. Payment
7. Order Tracking and Notifications
8. Order History and Rating
9. Restaurant Order Management
10. Delivery Management

## 3. Detailed Test Cases

The following are planned test cases based on the project's functional requirements. They have not been executed yet.

| TC ID | Module | Test Scenario | Preconditions | Test Steps / Test Data | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|---|
| TC01 | Registration | Register using valid user details | Registration page is available | Enter valid name, email, phone number and password; submit the form | A new customer account should be created | Not tested | Not Run |
| TC02 | Login | Login using valid credentials | Customer account exists | Enter the registered email and correct password | User should be logged in successfully | Not tested | Not Run |
| TC03 | Login | Login using an incorrect password | Customer account exists | Enter the registered email and an incorrect password | Login should be rejected and an appropriate error message should appear | Not tested | Not Run |
| TC04 | Restaurant Search | Search for a restaurant | Application is available | Enter a restaurant name in the search field | Matching restaurants should be displayed | Not tested | Not Run |
| TC05 | Food Search / Menu | View food items, prices and availability | A restaurant and its menu are available | Open a restaurant and view its menu | Food items, prices and availability should be displayed | Not tested | Not Run |
| TC06 | Shopping Cart | Add a food item to the cart | Customer is logged in and a menu item is available | Select a food item and choose Add to Cart | Selected item should appear in the cart with the correct quantity and price | Not tested | Not Run |
| TC07 | Shopping Cart | Remove a food item from the cart | Cart contains at least one item | Open the cart and remove an item | Selected item should be removed and the cart total should be updated | Not tested | Not Run |
| TC08 | Order Placement | Place an order with valid delivery details | Customer is logged in and cart contains an item | Proceed to checkout, enter a valid delivery address and confirm the order | Order should be placed and an order confirmation should be shown | Not tested | Not Run |
| TC09 | Payment | Complete payment for an order | Customer has reached the payment step | Select an available payment method and complete the payment process | Payment result should be displayed and the order payment status should be updated | Not tested | Not Run |
| TC10 | Order Tracking | Check the status of an order | An order has been placed | Open the order tracking page for that order | Current order status should be displayed to the customer | Not tested | Not Run |
| TC11 | Order History | View previous orders | Customer is logged in and has previous orders | Open the order history section | Previous orders and their details should be displayed | Not tested | Not Run |
| TC12 | Restaurant Order Management | Restaurant staff update an order status | Restaurant staff are logged in and an order is available | Open an order and update its status | Order status should be updated and reflected in the system | Not tested | Not Run |
| TC13 | Delivery Management | Delivery partner updates delivery status | Delivery partner is logged in and has an assigned delivery | Open the assigned delivery and update its status | Delivery status should be updated and visible to the relevant users | Not tested | Not Run |

## 4. Test Execution Summary

| Metric | Count |
|---|---:|
| Total Test Cases | 13 |
| Executed | 0 |
| Passed | 0 |
| Failed | 0 |
| Not Run | 13 |

**Note:** These test cases are currently documented but have not been executed. The counts should be updated after actual testing.

## 5. Bugs Identified

No bugs have been recorded at this stage because the test cases have not yet been executed. Any defects found during testing should be documented here with their test case ID, description and status.

## 6. Conclusion

The test cases cover the main functional modules of the Online Food Delivery App, including customer activities, restaurant order management and delivery management. Executing these test cases will help verify whether the application behaves according to its specified requirements.
