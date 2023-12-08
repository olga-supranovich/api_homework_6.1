# api_homework_6.1

 This repository includes:
 - a Postman collection 'sqlverifier - create task validation' 
 - environment file 'sqlverifier-live-test'
 - data file to run parameterized tests in sub-collection create task - field validation
 
 Follow the steps below to get started.

## Prerequisites
1. **Postman Installed:** Make sure you have [Postman](https://www.postman.com/) installed on your local machine.

## Getting Started

### 1. Clone the Repository
Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/olga-supranovich/api_homework_6.1.git
```

### 2. Import the Postman Collection and environment
Open Postman on your local machine.
Click on the "Import" button in the top-left corner.
Upload the sqlverifier - create task validation.postman_collection.json file located in the postman directory of this repository. Repeat import with file sqlverifier-live-test.postman_environment.json.

### 3. Set Environment Variables

In Postman, go to the "Manage Environments" option.
Select imported 'sqlverifier-live-test' with the necessary variables.

### 4. Run the Collection with data file
Select the sub-folder sqlverifier - create task validation/create task - field validation from the left sidebar.
Click on three-dot menu and select "Run folder".
Choose the desired environment. 
On the right panel 'Choose how to run your collection' under Data section click Select file, upload test_data.csv 
Click on the "Run sqlverifier - create task validation" button.

