# Software Testing Project: OrangeHRM Login Testing

## Project Overview
This project is dedicated to manual testing of the login functionality for the OrangeHRM website. The aim is to verify the correct operation of the login process, including handling valid and invalid credentials, as well as assessing the security and reliability of the module.

### Project Details
- **Project Name**: OrangeHRM Login Testing
- **Website Link**: [OrangeHRM Demo](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)
- **Module**: Login Page
- **Test Type**: Manual Testing
- **Test Tools**: Jira (for bug tracking)
- **Team Roles**:
  - **Scrum Master/Team Lead**: 
  - **Tester**: Siddhant Jain
  - **Designer/Developer**: 

### Test Documentation
- **Documents Provided**:
  - Software Requirement Specifications (SRS)
  - Business Requirement Specifications (BRS)
  - Functional Requirement Specifications (FRS)

### Decision Table
- **Total Number of Test Cases**: 9

### Test Scenarios
| SR No | Test Scenario ID | Test Scenario Title        | Reference | Total No of Test Cases |
|-------|------------------|----------------------------|-----------|------------------------|
| 1     | TS001             | Valid and Invalid Login Scenarios | SRS001    | 9                      |

### Test Case Details
| SR No | Test Case ID | Test Scenario ID | Test Case Title           | Pre-condition  | Test Steps | Test Data | Expected Result | Actual Result | Status |
|-------|--------------|------------------|---------------------------|----------------|------------|-----------|----------------|----------------|--------|
| 1     | TC001         | TS001            | Test valid login credentials | User at login page | 1. Enter valid credentials<br>2. Click 'Login' | Valid username/password | User successfully logs in | As expected | Pass |

### Setup Instructions
1. Navigate to the [OrangeHRM Demo Website](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login).
2. Review the test cases documented in the provided SRS, BRS, and FRS files.
3. Use the test scenarios and test cases as guidelines to manually test the login functionality.
4. Record the outcomes and any bugs discovered in your preferred tracking tool (e.g., Jira).

### Test Coverage
- **Covered Scenarios**:
  - Valid login attempts with correct credentials.
  - Invalid login attempts with incorrect or empty credentials.
  - UI validation for error messages on failed logins.
  - Security checks for login field restrictions.

### Acknowledgements
Special thanks to the team and resources provided, including the guidelines laid out in the Software Requirement Specifications (SRS), Business Requirement Specifications (BRS), and Functional Requirement Specifications (FRS).

