# Database Schema

## Courses

| Field | Type |
|---------|---------|
| course_code | String |
| course_name | String |
| credits | Integer |
| basket | String |
| semester_offered | Integer |

---

## Semesters

| Field | Type |
|---------|---------|
| semester_number | Integer |
| total_credits | Integer |

---

## PlannedCourses

| Field | Type |
|---------|---------|
| semester_number | Integer |
| course_code | String |

---

## GraduationRequirements

| Field | Type |
|---------|---------|
| minimum_credits | Integer |
| basket_requirement | String |
