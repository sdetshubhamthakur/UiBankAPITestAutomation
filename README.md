# UiBankAPITestAutomation
The API Test Automation suite for UiBank (a practice bank website developed by UiPath Academy) is created using Postman and Javascript.

## Overview
The UiBank website allows new users to create savings or checking accounts, allowing them to transfer funds within their accounts. 
Additionally, users can apply for new loans and retrieve loan details for existing ones.

### API Overview
Overall, my API test automation project involves 2 collections - UiBank and UiBankLoan.

#### 1. UiBank APIs
A total of 5 APIs are part of this collection, where the session authorization is required. A common JWT is used as authorization ID across the 5 APIs.

  a. Login: This API helps create a valid session token, which is utilized by other APIs. The request parameters are username and password.

  b. Get Profile: This API helps retrieve the user profile details, confirming if the right user account is being accessed or not.

  c. Create Account: This API helps users to create new savings or checking accounts, with the desired balance amount.

  d. Get Account: This API helps retrieve the details of all the savings/checking accounts linked with the current session user. 

  e. Transfer fund: This API enables fund transfers across the linked accounts of the user.

-----------

#### UiBank Test Run Demo

You can view a video demonstration of the API test suite here:

[UiBank API Test Run Demo Video (Google Drive)](https://drive.google.com/file/d/1EGKqQxK3jCOhO4qB2RuqP3FUOozC-fry/view?usp=drive_link)

------------


#### 2. UiBankLoan APIs
A total of 2 APIs are part of this collection, where the session authorization is not required.

  a. Apply Loan: This API helps applicants submit basic details like Loan amount, Loan term, Income, Age. It also evaluates whether loan should be approved or denied for the applicant.

  b. Get Loan Details: This API helps retrieve the loan details associated with a given Loan ID.


  -----------

#### UiBankLoan Test Run Demo

You can view a video demonstration of the API test suite here:

[UiBankLoan API Test Run Demo Video (Google Drive)](https://drive.google.com/file/d/1rS59QPLBfXKDQvnnLujiqfHbcOsfaJTY/view?usp=drive_link)

------------
