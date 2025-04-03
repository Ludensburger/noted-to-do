# TrashIT: Garbage Collector Scheduling App

## Overview
TrashIT is an application designed to streamline garbage collection scheduling, allowing users to book and manage waste pickups efficiently. The app provides a user-friendly interface for residents to schedule pickups, reschedule if needed, and make payments. Additionally, garbage collectors can view assigned pickups through a dedicated dashboard.

This repository focuses on automating test cases for TrashIT to ensure a smooth and reliable user experience. The automation is integrated with CircleCI to enable continuous testing and validation of the application.

## Features
- **User Registration & Login**: Secure authentication for users and collectors.
- **Waste Pickup Scheduling**: Allows users to schedule and reschedule garbage pickups.
- **Collector Dashboard**: Enables garbage collectors to view and manage assigned pickups.
- **Payment System**: Supports payments for waste pickup services.
- **Security Measures**: Implements password hashing for enhanced security.

## Test Automation Scope
The test automation covers the following scenarios:
- User **Signup** functionality
- User **Login** functionality
- **Garbage Pickup Scheduling**
- **Rescheduling** of pickups
- **Collector Dashboard**: Viewing assigned pickups
- **System Security**: Password hashing verification
- **Payment System** validation
- **CI/CD Integration**: Automated testing using CircleCI

## Test Cases
### Test Case 1: User Signup Functionality
- **Test Case ID**: TC_001
- **Test Scenario**: User attempts to sign up with valid credentials.

### Test Case 2: User Login Functionality
- **Test Case ID**: TC_002
- **Test Scenario**: User attempts to log in with valid credentials.

### Test Case 3: Waste Pickup Scheduling
- **Test Case ID**: TC_003
- **Test Scenario**: User schedules a garbage pickup.

### Test Case 4: Booking System - Rescheduling
- **Test Case ID**: TC_004
- **Test Scenario**: User reschedules a garbage pickup.

### Test Case 5: Collector Dashboard - View Assigned Pickups
- **Test Case ID**: TC_005
- **Test Scenario**: Collector views assigned pickups.
  
### Test Case 6: Payment System
- **Test Case ID**: TC_007
- **Test Scenario**: Verify payment processing functionality.

## Continuous Integration
- Integrated with **CircleCI** for continuous testing and validation.
- Ensures consistent and reliable software testing throughout development.
- Can be expanded for additional features and improvements.

## Future Enhancements
- Adding more security tests for user authentication.
- Expanding test cases to cover payment gateway edge cases.
- Enhancing collector-side features for better workflow management.

## Authors
- Ryu R. Mendoza
- Philip James Olbedencia

## Contributing
Contributions are welcome! Please follow the repository guidelines for submitting pull requests and reporting issues.

---
**Developed for efficient and seamless waste management.**

