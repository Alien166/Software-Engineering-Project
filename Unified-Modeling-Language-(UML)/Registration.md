# Use case modeling

## Use case description

### Use Case: Registration

| Use Case Name  | Registration                                     |
|----------------|---------------------------------------------------|
| Function       | Patient will sign up on the website.              |
| Description    | User will input personal information:             |
| Input          | - First Name<br>- Last Name<br>- Mobile Number<br>- Home Telephone Number<br>- Work Telephone Number<br>- Fax<br>- E-mail (for login and contact purposes)<br>- Password<br>- Date of Birth<br>- Occupation<br>- Nationality<br>- Sex<br>- Home Address<br>- Shipping Address |
| Output         | - If input data is valid, user sees a successful message.<br>- If input data is invalid, user sees an error message indicating the incorrect data entered. |
| Action         | - **Pre-condition:** If the Patient doesn’t have an account already, they enter their phone number, receive a verification code, and then enter a new username and password.<br>- **Post-condition:** Upon valid username and password, the system accepts the process and opens the list of doctors. |
| Additional Notes | - The system utilizes a connected database for user account activation. |
