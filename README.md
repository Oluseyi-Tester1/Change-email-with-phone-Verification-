# Oluseyi Taiwo - QA Portfolio

## About Me

Detail-oriented QA Tester with experience in mobile application testing, exploratory testing, and security validation.


## Skills

- Exploratory Testing
- Functional Testing
- Mobile App Testing (Android)
- Bug Reporting
- Test Case Execution
- Security & OTP Validation


## Sample Bug Report

### Title: Account - Phone Verification Stalls in Personal Details When Changing Email


### Environment:
Android 13 - Redmi Note 11S


### Steps to Reproduce:
1. Open the Booking.com mobile app
2. Clip My Account
3. Select Personal Details
4. Click change the email with phone verification
5. Enter a valid phone number
6. Click continue

### Actual Result:

After tapping Continue, the verification process does not proceed. No OTP is received on the entered phone number, no verification screen is displayed, and no confirmation or error message appears. The email change process cannot be completed.

### Expected Result:

The system should initiate phone verification by sending an OTP to the entered phone number.
A verification screen or OTP input prompt should appear, confirming that the code has been sent. The user should be able to enter the received OTP and successfully complete the email update once the code is validated.


### Bug Type:
Functional

### Frequency:
Every time

### priority:
High 

https://github.com/user-attachments/assets/df8dfdc5-698b-4076-b651-df31059ab6d4

https://github.com/user-attachments/assets/cb8caaa8-b377-40a4-be4e-75b007a25260
