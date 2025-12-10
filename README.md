<h1><u>Summary</u></h1>

I have  completed API testiong on PetStore. URL: https://petstore.swagger.io/#/

Tasks includes
 - CURD operation (Create,Get,Put,Delete)
 - Api Request
 - Test scripts
 - Creating Environment
   
<h1><u>Instructions</u></h1>

 1. Import the Collection

Follow the steps below to load the API test collection:

Open Postman

Click Import

Select the file:
PetStore_User_Collection.json

 2. Import the Environment

Set up the environment so variables work correctly:

Go to Environments in Postman

Click Import

Select the file:
PetStore_Environment.json

 3. Pre-Request Scripts Used

This project uses several automation scripts to enhance testing:

Generate random user IDs

Auto-update usernames

Auto-generate email & phone values

Pass variables between requests

Set environment variables automatically

 4. Tests Included

Each request contains Postman test scripts to validate:

Status codes (200, 400, 404, etc.)

Response structure

Response body value checks

Field validations

Positive & negative test cases

  
