# sql-exam
select a.Employee_id,b.Department,a.max(salary),a.min(salary),a.avg(salary) from Employee a left join department b on  where b.department_id=employee_id group by b.department limit 10

