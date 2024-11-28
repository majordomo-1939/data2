# data2
Employee
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Details</title>
</head>
<body>
    <h1>JFCoopEmployee Table</h1>
    <h2>Table Structure</h2>
    <ul>
        <li>Column1 - EmployeeKey</li>
        <li>Column2 - FirstName</li>
      <li>Column3 - LastName</li>
      <li>Column4 - DepartmentName</li>
      <li>Column5 - HireDate</li>
      <li>Column6 - DateOfBirth</li>
      <li>Column7 - EmailAddress</li>
      <li>Column8 - MaritalStatus</li>
      <li>Column9 - Gender</li>
      <li>Column10 - EmployeeStatus</li>
      <li>Column11 - Vacationhours</li>
      <li>Column12 - SickLeave</li>
      <li>Column13 - Salary</li>
      <li>Column14 - TITLE</li>
        <!-- Add all columns -->
    </ul>
    <h2>Example Queries</h2>
    <pre>
    -- Sample query for JFCoopEmployee
    ---Retrieve from table employees in Administration department
SELECT * FROM [dbo].[JFCoopEmployee]
WHERE DepartmentName='Administration'
    </pre>
  <pre>
    --Write SQL query to retrieve transport employees
SELECT * FROM [dbo].[JFCoopEmployee]
WHERE DepartmentName='Transportation'
  </pre>
    <a href="../index.html">Back to main page</a>
</body>
</html>
