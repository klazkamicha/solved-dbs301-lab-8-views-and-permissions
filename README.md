Download Link: https://assignmentchef.com/product/solved-dbs301-lab-8-views-and-permissions
<br>
This week’s lab continues using the SELECT command in addition to now incorporating multiple tables and various set operators to produce results.

<h2>Tasks</h2>

<ul>

 <li>Display the names of the employees whose salary is the same as the lowest salaried employee in any department.</li>

</ul>




<ul>

 <li>Display the names of the employee(s) whose salary is the lowest in each department.</li>

</ul>




<ul>

 <li>Give each of the employees in question 2 a $120 bonus.</li>

</ul>




<ul>

 <li>Create a view named <em>vwAllEmps</em> that consists of all employees includes employee_id, last_name, salary, department_id, department_name, city and country (if applicable)</li>

</ul>




<ul>

 <li>Use the <em>vwAllEmps</em> view to:

  <ol>

   <li>Display the employee_id, last_name, salary and city for all employees</li>

   <li>Display the total salary of all employees by city</li>

   <li>Increase the salary of the lowest paid employee(s) in each department by 120</li>

   <li>What happens if you try to insert an employee by providing values for all columns in this view?</li>

   <li>Delete the employee named Vargas. Did it work? Show proof.</li>

  </ol></li>

</ul>




<ul>

 <li>Create a view named <em>vwAllDepts</em> that consists of all departments and includes department_id, department_name, city and country (if applicable)</li>

</ul>




<ul>

 <li>Use the <em>vwAllDepts</em> view to:</li>

</ul>




<ol>

 <li>For all departments display the department_id, name and city</li>

 <li>For each city that has departments located in it display the number of departments by city</li>

</ol>




<ul>

 <li>Create a view called <em>vwAllDeptSumm</em> that consists of all departments and includes for each department: department_id, department_name, number of employees, number of salaried employees, total salary of all employees. Number of Salaried must be different from number of employees. The difference is some get commission.</li>

</ul>




<ul>

 <li>Use the <em>vwAllDeptSumm</em> view to display department name and number of employees for departments that have more than the average number of employees</li>

</ul>




<ul>

 <li>A) Use the GRANT statement to allow another student (Neptune account) to retrieve data for your employees table and to allow them to retrieve, insert and update data in your departments table. Show proofB) Use the REVOKE statement to remove permission for that student to insert and update data in your departments table</li>

</ul>