# Testing

## Test Plan
TODO: Describe any manual and automated (unit) tests. Uniquely identify each test case. Include prerequisites and test data.
Test Case 1: Find All Car Parks Description: Verify that the application displays a list of all designated car parks upon opening. Steps:

Open the web application.
Observe the displayed content. Expected Result: A list of car park names is displayed.
Test Case 2: Search by Valid Location Description: Test that the application retrieves and displays car parks matching a valid location search term. Steps:

Enter a valid location (e.g., street name) in the search bar.
Click the search button.
Observe the displayed results. Expected Result: A list of car parks matching the location is displayed.
Test Case 3: Search by Invalid Location Description: Verify that the application handles an invalid location search term gracefully. Steps:

Enter an invalid location (e.g., random characters) in the search bar.
Click the search button.
Observe the displayed results. Expected Result: An appropriate message indicating no results are found is displayed.
Test Case 4: Search by Valid Car Park Type Description: Test that the application retrieves and displays car parks matching a selected car park type. Steps:

Select a valid car park type (e.g., on-street) from the filter options.
Click the search button.
Observe the displayed results. Expected Result: A list of car parks matching the selected type is displayed.
Test Case 5: Search by Invalid Car Park Type Description: Verify that the application handles an invalid car park type selection gracefully. Steps:

Select an invalid car park type (e.g., nonsensical value) from the filter options.
Click the search button.
Observe the displayed results. Expected Result: An appropriate message indicating an invalid selection is displayed.
Test Case 6: View Car Park Details Description: Test that the application displays detailed information for a selected car park (if the API provides this functionality). Steps:

Perform a search (by location, type, or all car parks).
Click on a specific car park name in the search results list.
Observe the displayed information. Expected Result: A detailed view of the selected car park is displayed, including additional information like address and type (if available).

Test Runs
TODO: For each test described above, indicate the current status. 
Create a requirements traceability matrix to validate the completeness of the product.

| Use-Case ID | Requirement ID | Test Case | Status |
| ----------- | -------------- | --------- | ------ |

TODO: Add rows for each test, current status is eg. pass/fail
