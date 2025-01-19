# OpenCart Manual Testing

This repository contains the manual testing documentation and test cases for the **OpenCart** e-commerce platform. The goal is to ensure the functionality, usability, and security of the OpenCart system by performing comprehensive manual tests on its features and functionalities.

## Features Tested

- **User Account Management**: Register, login, and user profile management.
- **Product Management**: Adding, editing, and deleting products.
- **Shopping Cart**: Adding/removing items from the shopping cart, viewing cart, and checkout process.
- **Order Management**: Placing, viewing, and managing orders.
- **Payment Integration**: Testing payment gateways (e.g., PayPal, credit card).
- **Shipping & Tax Calculations**: Verifying correct shipping and tax rates during checkout.
- **Admin Panel**: Managing settings, users, products, and more.
- **Security Testing**: Validating security features like SSL encryption, login/logout processes, and data protection.
- **Theme & Customization**: Testing theme settings and customization features.

## Testing Process

1. **Test Environment Setup**: OpenCart version [version number] installed in [environment details, e.g., local, staging server].
2. **Browsers Tested**: Chrome, Firefox, Safari, Edge.
3. **Test Scenarios**: Each feature was tested across multiple test scenarios to ensure robustness and stability.
4. **Bug Reporting**: All issues found during testing were documented and reported in the GitHub Issues section.

## Test Cases

Test cases are categorized based on the functionality they test, and each test case includes:

- **Test Case ID**
- **Description**
- **Preconditions**
- **Test Steps**
- **Expected Results**
- **Actual Results** (filled after testing)
- **Status** (Pass/Fail)

You can find all the test cases in the `/test-cases` folder.

## Running the Tests

Manual testing doesn't require a test runner, but you can follow the testing steps as described in the test cases document. All tests should be executed in the OpenCart admin panel, front end, and across various browsers.

## Contributing

If you'd like to contribute, feel free to fork the repository, create a branch, and submit a pull request with improvements or additional test cases. Please ensure your contributions adhere to the project's testing standards.

