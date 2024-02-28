# Capital API Automation

Please refer to the steps below to import the collection and environment variables into Postman.

### Step 0: Download Postman app to your local machine

If you don't already have it, you can download it [here](https://www.postman.com/downloads/).

### Step 1: Download JSON files for import

Download the following files:
- Postman Collections/scr.json 
- TestEnv.postman_environment.json

### Step 2: Import JSON files to Postman 

1. Open Postman.
2. Select **Import** in the left navigation menu.
3. Click on **Files**.
4. Choose the two previously downloaded JSON files.
5. Make sure that the first one is saved as "Collection" and the second one as "Environment".
6. Click on the **Import** button.

### Step 3: Run the Collection

1. Click on **Capital-com**.
2. Choose **TestEnv** from the Environment dropdown.
3. Click on **Run**.
4. Click on the **Run Capital-com** button.

## Expected Test Results

- All tests under the `Positive E2E Scenarios` folder should pass.
- Two out of three tests in the `Negative Scenarios` folder should fail.
