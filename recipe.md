As a coach
So I can get to know all students
I want to see a list of students' names.

As a coach
So I can get to know all students
I want to see a list of cohorts' names.

As a coach
So I can get to know all students
I want to see a list of cohorts' starting dates.

As a coach
So I can get to know all students
I want to see a list of students' cohorts.

# extract nouns

student names, cohort names, cohort starting dates, student cohorts

# table name and columns

| Record                | Properties         |
| --------------------- | ------------------ |
| student               | name, cohort_id    |
| cohort                | name, start_date   |

# column types

Table: students
id: SERIAL
name: text
cohort_id: int

Table: cohorts
id: SERIAL
name: text
start_date: date