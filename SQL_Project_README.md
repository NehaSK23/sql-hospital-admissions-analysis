# Hospital Admissions SQL Analysis

## Dataset
- hospital_admissions.csv

## Queries you can paste on GitHub:

```
SELECT * FROM hospital_admissions;

SELECT name, city FROM hospital_admissions
WHERE city='Mumbai';

SELECT city, COUNT(*) FROM hospital_admissions
GROUP BY city;

SELECT * FROM hospital_admissions
ORDER BY admission_days DESC;

SELECT * FROM hospital_admissions
WHERE city='Mumbai' AND admission_days > 3;
```
