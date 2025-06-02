# ***Test Plan for Market Mate’s New Features***

1. **Analyze the product.**

Product Name: Market Mate Website

New Features:

- Discounted system for customers
- Order Histtory for registered users
- Real-Time inventory updates
- Enhanced User account management

The new features to make shopping easier and more fun include:

- **Discount System**: Gives discounts based on things like how many items you buy or if you’re a member.
- **Order History**: Lets you see what you’ve ordered before.
- **Real-Time Inventory**: Shows what’s in stock right away, so you know what’s available.
- **Better Account Management**: Makes it easier and safer to log in, sign up, or reset your password.
1. **Design the Test Strategy**

The test strategy will use a combination of functional, non-functional, and integration testing to make sure everything works properly, connects well with other parts of the website, and meets key standards like performance and security.

- **Testing Levels**:
    - *Unit Testing* – tests individual components
    - *Integration Testing* – verifies how components work together
    - *System Testing* – evaluates the complete product
    - *Acceptance Testing* – validates user requirements
- **Test Types**:
    - *Functional Testing* – verifies features work as expected
    - *Regression Testing* – ensures new changes don't affect existing features
    - *Security Testing* – protects the application from threats
    - *Load Testing* – measures system performance under multiple users
    - *Usability Testing* – assesses website user-friendliness
- **Test Execution**:I will use both *manual testing* and *automated testing* based on each test case's requirements.
- **Tools Used**:
    - *Selenium* – for automating UI testing
    - *Postman* – for testing APIs
    - *JMeter* – for performance and load testing
    - *TestRail* – for managing test cases and test plans
1. **Define test objectives.**

The objectives ot this testing phase are to:

- Ensure the the new features function as expected under all conditions
- Validate that the discount system applies accurate discounts based on user input and rules.
- Confirm that order history displays the correct past purchases for registered users.
- Verify that inventory is updated in real-time, and users cannot purchase out-of-stock items.
- Ensure that the user account system handles registration, login, and password resets correctly, with security measures in place.
1. **Define test criteria.**

**Entry criteria:**

- All new features are developed and integrated into the test environment.
- The codebase is stable and ready for testing
- Test environment is set up and ready for testing.

**Exit Criteria:**

- All test cases have been executed.
- All critical and high-priority bugs are fixed.
- All features meet functional requirements and pass testing.
- Documentation is completed.
1. Resources Planning

**Human Resources:**

- Test Manager (1)
- Test Engineers (2)
- Developer Support (1)
- Security Specialist (1)

**Software Tools:**

- Selenium WebDriver for UI automation
- JMeter for load testing
- TestRail for test management
- GitHub for version control and test

**Hardware:**

- Servers for staging and production environments
- User devices for cross-browser and cross-device testing (PC, mobile, tablet)
1. **Plan Test Environment.**

**Test Environment Setup:**

- **Server:** Staging environment matching production
- **Test Data:** Sample products, users, and orders
- **Browsers:** Chrome, Firefox, Safari, Edge (Desktop/Mobile)
- **Security:** SSL/TLS, anti-bot, password hashing
1. **Schedule and Estimation.**

| **Activity** | **Estimated Time** |
| --- | --- |
| Test Plan Creation | 2 days |
| Test Case Design | 3 days |
| Test Environment Setup | 2 days |
| Manual Test Execution | 4 days |
| Automated Test Script Development | 5 days |
| Load Testing | 3 days |
| Regression Testing | 3 days |
| Report Generation and Review | 2 days |

Total Estimated Testing time  = 19 Days

**8. Determine Test Deliverables**

- Test Plan document
- Test Cases document
- Test Execution Reports
- Defect Reports
- Final Test Summary Report
- Test Automation Scripts
