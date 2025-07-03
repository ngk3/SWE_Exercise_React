# SWE_Exercise_React

## To run the application, please follow the following steps:
### 1. Navigate to the "swe-assignment" folder
### 2. Run "npm install" in the terminal to install all necessary dependencies
### 3. Run "npm run dev" in the terminal to start the application
### 4. Run "npm test" in the terminal to run Jest unit tests

## Additional Comments
### In the scope of this assignment, there are a number of aspects that would be improved upon later if more information is gathered about potential features or enhancements:
#### 1. Displaying the list of students as a table that can be sorted and filtered would be useful for user experience
#### 2. Pagination to optimize rendering performance can be useful if there is no need to see all the students at once, especially for a large amount of students
#### 3. Debouncing can be added to the toggle input to prevent unnecessary fetching of information or, if the students information does not change much, cacheing can be involved
#### 4. If this is something to be viewable in offline mode like in a mobile device, SQLite can be utilized for local data storage for non-sensitive information
#### 5. Additional styling can be added to facilitate a better user experience like
##### a. Alternative row highlighting of the table to help with contrast
##### b. Better color contrast to meet WCAG accessibility requirements
##### c. Changing the checkbox to a Toggle Switch instead which is a more modern approach