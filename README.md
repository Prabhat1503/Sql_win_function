# Sql_win_function

This repository contains SQL scripts to demonstrate the use of window functions with a sample `employees` table. The scripts include creating the table, inserting sample data, and applying various window functions.

## Repository Structure

- **`create_employees_table.sql`**: SQL script to create and populate the `employees` table.
- **`window_functions_examples.sql`**: SQL script demonstrating the usage of different window functions.

## Description

The provided SQL scripts perform various operations using window functions. These operations include ranking employees, calculating cumulative sums, and generating moving averages.

### Features $ Output

1. **ROW_NUMBER()**: Assigns a unique sequential number within each department.
   
   ![image](https://github.com/user-attachments/assets/0ab5c079-3f58-4aa8-bac1-d01d985bc722)

2. **RANK()**: Ranks employees within each department by salary.
   
   ![image](https://github.com/user-attachments/assets/f3af4d6c-2b48-45c3-8901-8c8e0e66557a)

3. **DENSE_RANK()**: Similar to `RANK()`, but without gaps in the ranking sequence.

   ![image](https://github.com/user-attachments/assets/b4153e1e-3e41-47ad-a840-d0939183c7bd)
   
4. **NTILE()**: Divides employees into a specified number of buckets based on their salary.

   ![image](https://github.com/user-attachments/assets/da4d84f3-ce74-47f9-a0d4-a297927b1d17)

5. **LAG()**: Shows each employee's hire date and the hire date of the previous employee.

   ![image](https://github.com/user-attachments/assets/e9f58aaa-80f8-438e-916d-80a2a310778a)

6. **LEAD()**: Shows each employee's hire date and the hire date of the next employee.

   ![image](https://github.com/user-attachments/assets/b51599a7-1939-4dbe-94a7-2dd4afe4eb82)

7. **SUM()**: Calculates cumulative sums of salary.

    ![image](https://github.com/user-attachments/assets/d4f84015-a26a-4b1b-a70f-8f56eebdfa84)

8. **AVG()**: Calculates the moving average of salary.

    ![image](https://github.com/user-attachments/assets/57b27594-7a78-4a71-a690-664df02d028b)

9. **FIRST_VALUE()**: Retrieves the first salary value within each department based on hire date.

    ![image](https://github.com/user-attachments/assets/f0ca57d7-dc84-43da-b10b-e5b9e66b21ca)

10. **LAST_VALUE()**: Retrieves the last salary value within each department based on hire date.

    ![image](https://github.com/user-attachments/assets/ebc63f72-ae2f-48c2-9a1b-d51b4b631dcb)

11. **PERCENT_RANK()**: Computes the relative rank of each employee's salary.

    ![image](https://github.com/user-attachments/assets/a5c32b15-6ecb-4a95-aea4-57c7838059ad)

12. **CUME_DIST()**: Calculates the cumulative distribution of salaries.

    ![image](https://github.com/user-attachments/assets/eee3058a-f118-483b-82f6-72b4e4bacc2c)


## Usage

1. **Run `create_employees_table.sql`**:
   - This script creates the `employees` table and populates it with sample data.

2. **Run `window_functions_examples.sql`**:
   - This script demonstrates the usage of various window functions on the `employees` table.

## Example Outputs

The SQL scripts will produce various outputs, such as ranked lists of employees, cumulative salary calculations, and moving averages. Refer to the comments in each SQL script for details on what each query does.

## Additional Notes

- Ensure you have the appropriate SQL environment to run these scripts.
- Modify the table schema or queries to suit specific use cases or data requirements.

---

This project provides a practical demonstration of SQL window functions, offering insights into their application for complex analytical tasks.
