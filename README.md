# **Store Management System with Newman report**
This project demonstrates API testing using Postman, providing a collection of tests to validate various endpoints of the API.
### **Feature**
- Tests for GET, POST, PUT, DELETE requests
- Collection of tests covering different API endpoints
- Environment setup for easy switching between environments
- Pre-request scripts for data setup
- Test scripts for assertions and validations
## API Documentation
### **Technology Used**
- Postman
- Newman
### **Prerequisite**
- Node.js
- Newman
- Newman html Report Library
### **Installation**
1. Postman: If you haven't already, [download and install Postman.](https://www.postman.com/downloads/)
2. Clone the repository:
 ```console 
  git clone https://github.com/aminulislamtutul/Store_Management_System_with_Newman_report.git
```
3. Import the Postman collection:
   - Open Postman.
   - Click on the Import button.
   - Select the file from the repository.
4. Import the Postman environment:
   - In Postman, click on the gear icon in the top right corner.
   - Select **Import** and choose the file.
5. Newman and Report Installation Process:
   - Newman Install Command:
     ```console 
      npm install -g newman
     ```
   - Newman html Report Install Command:
     ```console 
      npm install -g newman-reporter-htmlextra
     ```
### **Usage**
1. Select Environment:
    - In Postman, select the appropriate environment (e.g., Development, Production) from the top-right dropdown.
2. Run Collection:
    - Select the imported collection from the Collections sidebar.
    - Click on the Runner button to open the collection runner.
    - Select the desired environment.
    - Click Start Test to run the collection.
3. View Results:
    - Once the tests are complete, view the results in the Runner tab.
    - Detailed test results can be viewed for each request.
## Run Command: 
- Run Command for Console:
```console
newman run Store_Management_System_Collections.postman_collection.json -e Store_Management_System_Environment.postman_environment.json
```
- Run Command for Report: 
```console
newman run Store_Management_System_Collections.postman_collection.json -e Store_Management_System_Environment.postman_environment.json -r cli,htmlextra
```
## Newman Report Summary:

<img width="829" height="424" alt="Screenshot 2025-09-29 234746" src="https://github.com/user-attachments/assets/46c5a597-b60d-4cc2-8e60-4c6d3e7fd154" />
<img width="831" height="369" alt="Screenshot 2025-09-29 234844" src="https://github.com/user-attachments/assets/a4cebcf4-0e25-44cd-92d4-ebf4da763a26" />
<img width="831" height="205" alt="Screenshot 2025-09-29 234915" src="https://github.com/user-attachments/assets/f2507cb3-8351-460d-bce3-578da9b295c2" />
<img width="830" height="205" alt="Screenshot 2025-09-29 234952" src="https://github.com/user-attachments/assets/4d43e07d-f8ee-458b-ac98-4d188e8fc127" />




   

