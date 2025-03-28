# TestCase_assignment
Verifies that users can log in with valid credentials and are redirected to the dashboard. Issue: Login is successful, but there is a delay of approximately 30 seconds before the dashboard appears, which may indicate a backend performance issue.
Test Case 1: Successful Login with Valid Credentials
Verifies that the user can log in with valid credentials and be redirected to the dashboard. However, there’s a slight delay of about 30 seconds before the dashboard loads.

Test Case 2: Unsuccessful Login with Incorrect Password
Checks that the system shows an error message when an incorrect password is entered. The system shows a generic "Invalid credentials" error instead of "Incorrect password."

Test Case 3: Blank Fields Login
Tests the behavior when both email and password fields are left blank. No validation message is displayed, and the login is attempted with empty fields.

Test Case 4: Verify Menu Navigation
Ensures that all navigation menu links direct the user to the correct page. Navigation works fine with no issues.

Test Case 5: UI Responsiveness on Different Devices
Tests the UI’s adaptability on mobile and tablet devices. The mobile view shows overlapping or misaligned UI elements, causing layout issues.

Test Case 6: Input Valid Data in Forms
Ensures that valid data is submitted correctly in forms. The form works as expected, and valid data is saved successfully.

Test Case 7: Input Invalid Data in Forms
Tests how the system handles invalid data. Special characters in the text fields are accepted and submitted, even though they should be rejected.

Test Case 8: Generate Reports
Checks the report generation functionality. Reports are generated, but some data points are missing or incorrect.

Test Case 9: Enter Incorrect Data for Error Handling
Verifies that invalid data triggers an error message. The system correctly shows an error when invalid data is entered.

