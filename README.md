# QA-test-project
SELECT tbl1_EmployeeDetails.FullName, tbl2_EmployeeSalary.Salary
FROM tbl1_EmployeeDetails INNER JOIN tbl2_EmployeeSalary
on tbl1_EmployeeDetails.EmpID = tbl2_EmployeeSalary.EmpID
WHERE tbl2_EmployeeSalary.Salary Between 5000 AND 10000;
