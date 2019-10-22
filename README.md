# Cloudify Everything Hackathon
Steps to follow to test the working solution on Azure Ml Studio for Prediction of card approval using Machine learning algorithm.

- Create a new Azure account
-  Go through the given link https://gallery.cortanaintelligence.com/Experiment/Credit-Card-Approval-Team-Geek-Squad


-  or Use the below API to test the service in postman:
Method:POST
url:https://ussouthcentral.services.azureml.net/workspaces/c18e2523b8254de78d7291646a053282/services/6864df8a13af4d1fbd74c9c510890975/execute?api-version=2.0&details=true

   Headers:
Authorization:Bearer Q+BYxmDaiVmoaHxJ6Mn8gwQbxQWIHO1iD0mM+W4Y4joTFzNPYlSZXcxlxJZMCTHE1ZCJdJcdOPYmGMRs4hg1dw==

   Content-Type : application/json
   Body :

    {
  "Inputs": {
    "input1": {
      "ColumnNames": [
        "Male",
        "Age",
        "Debt",
        "Married",
        "BankCustomer",
        "EducationLevel",
        "Ethnicity",
        "YearsEmployed",
        "PriorDefault",
        "Employed",
        "CreditScore",
        "DriversLicense",
        "Citizen",
        "ZipCode",
        "Income"
      ],
      "Values": [
        [
          "b",
          "31.83",
          "0.04",
          "y",
          "p",
          "m",
          "v",
          "0.04",
          "f",
          "f",
          "0",
          "f",
          "g",
          "0",
          "0"
        ]
        
      ]
    }
  },
  "GlobalParameters": {}
}

#Dataset For Testing:

https://drive.google.com/open?id=1iMqLLpx6Lhrr0_nrbZsITOzEd5DeOJwv

