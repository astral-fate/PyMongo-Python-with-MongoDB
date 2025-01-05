# PyMongo-Python-with-MongoDB
Certainly! Below is a `README.md` file that includes all 15 questions with their answers hidden behind a `<details>` tag. This way, the answers are not visible unless you click on the dropdown to reveal them.

```markdown
# MongoDB Quiz Questions and Answers

This document contains 15 MongoDB quiz questions along with their correct answers and explanations. The answers are hidden behind a `<details>` tag, so you can test yourself before revealing the correct answer.

---

### Question 1
**Which of the following statements is represented by the MongoDB filter?**
```json
{$or: [{"day": {$gt: 12, $lt: 15}}, {"hour": 56.5}]}
```
- a) day <= 15 and day >= 12 or hour = 56.5
- b) (day <= 15 and day > 12) or hour = 56.5
- c) day <= 15 or day > 12 or hour = 56.5
- d) None of the above

<details>
<summary>Answer</summary>
<b>Answer: b)</b>  
The correct interpretation of the filter is that it matches documents where the day is greater than 12 and less than or equal to 15, or the hour is exactly 56.5.
</details>

---

### Question 2
**Which of the following is not a valid MongoDB filter?**
```json
{ "dno": {$gte:14,$lte:16} }
```
- a) `{ "dno": {$gte:14,$lte:16} }`
- b) `{ $and:[{"dno":14},{salary:7.5}} ]`
- c) `{ $or:[{"dno":{$gte:14,$lte:16}},{salary:7.5}} ]`
- d) None of the above

<details>
<summary>Answer</summary>
<b>Answer: b)</b>  
The second option is invalid due to incorrect syntax.
</details>

---

### Question 3
**Does the following code represent a JSON document in a standard format?**
```json
{
  "fname": "Justin",
  "lname": "Mark",
  "ssn": "11341102",
  "salary": 4070.00,
  "superssn": "1117600",
  "phone": 12345,
  "phone": 7998710
}
```
- a) Correct
- b) Not correct

<details>
<summary>Answer</summary>
<b>Answer: b)</b>  
The JSON document is not valid because it contains duplicate keys ('phone').
</details>

---

### Question 4
**Which of the following is a valid MongoDB filter?**
```json
{$or: [{"dno": {$gte:14, $lte:16}}, {salary:25000}]}
```
- a) `{$or: [{"dno": {$gte:14, $lte:16}}, {salary:25000}]}`
- b) `{$or: [{"dno": {$gte:14, 16}}, {salary,$lte:25000}]}`
- c) `{$or: [{"dno": {14, $lte:16}}, {$gte:25000}]}`
- d) None of the above

<details>
<summary>Answer</summary>
<b>Answer: a)</b>  
The first option is a valid MongoDB filter.
</details>

---

### Question 5
**Does the following code represent a JSON document in a standard format?**
```json
{
  "fname": "Ali",
  "minit": 'n',
  "lname": "Mohamed",
  "ssn": "1123411102",
  "salary": 56000.00
}
```
- a) Correct
- b) Not correct

<details>
<summary>Answer</summary>
<b>Answer: b)</b>  
The JSON document is not valid because single quotes (') are used instead of double quotes (").
</details>

---

### Question 6
**Which of the following statements is represented by the MongoDB filter?**
```json
{ "day": {$gte:14, $lte:16} }
```
- a) day >14 and day <=16
- b) day >=14 and day <16
- c) day >=14 and day <=16
- d) None of the above

<details>
<summary>Answer</summary>
<b>Answer: c)</b>  
The filter matches documents where the day is greater than or equal to 14 and less than or equal to 16.
</details>

---

### Question 7
**Does the following code represent a JSON document in a standard format?**
```json
{
  "ssn": "112341102",
  "bdate": DATE("1968-01-12"),
  "address": "2342 May","Atlanta","GA",
  "salary": 46500.00,
  "superssn": "11541100"
}
```
- a) Correct
- b) Not correct

<details>
<summary>Answer</summary>
<b>Answer: b)</b>  
The JSON document is not valid because the DATE function is not valid in JSON.
</details>

---

### Question 8
**Which of the following is not a valid MongoDB filter?**
```json
{ "dno": {$gte:14,$lte:16} }
```
- a) `{ "dno": {$gte:14,$lte:16} }`
- b) `{ $and:[{"dno":14},{salary:7.5}} ]`
- c) `{ $or:[{"dno":{$gte:14,$lte:16}},{salary:7.5}} ]`
- d) None of the above

<details>
<summary>Answer</summary>
<b>Answer: b)</b>  
The second option is invalid due to incorrect syntax.
</details>

---

### Question 9
**Does the following code represent a JSON document in a standard format?**
```json
{
  "fname": "Justin",
  "lname": "Mark",
  "ssn": "111111102",
  "salary": 40000.00,
  "superssn": "111111100",
  "phone": 12345,
  "is a manager": TRUE
}
```
- a) Correct
- b) Not correct

<details>
<summary>Answer</summary>
<b>Answer: b)</b>  
The JSON document is not valid because TRUE should be written in lowercase as true.
</details>

---

### Question 10
**Which of the following is a valid MongoDB filter?**
```json
{$or: [{"dno": {$gte:14, $lte:16}}, {salary:25000}]}
```
- a) `{$or: [{"dno": {$gte:14, $lte:16}}, {salary:25000}]}`
- b) `{$or: [{"dno": {$gte:14, 16}}, {salary,$lte:25000}]}`
- c) `{$or: [{"dno": {14, $lte:16}}, {$gte:25000}]}`
- d) None of the above

<details>
<summary>Answer</summary>
<b>Answer: a)</b>  
The first option is a valid MongoDB filter.
</details>

---

### Question 11
**Does the following code represent a JSON document in a standard format?**
```json
{
  "fname": "Justin",
  "lname": "Mark",
  "ssn": "11341102",
  "salary": 4070.00,
  "superssn": "1117600",
  "phone": 12345
}
```
- a) Correct
- b) Not correct

<details>
<summary>Answer</summary>
<b>Answer: a)</b>  
The JSON document is valid.
</details>

---

### Question 12
**Does the following code represent a JSON document in a standard format?**
```json
{
  "ssn": 523,
  "address": "Cairo",
  "Address": "Giza"
}
```
- a) Correct
- b) Not correct

<details>
<summary>Answer</summary>
<b>Answer: b)</b>  
The JSON document is not valid because it contains duplicate keys ('address' and 'Address').
</details>

---

### Question 13
**Does the following code represent a JSON document in a standard format?**
```json
{
  "fname": "Mohamed",
  "lname": "Mahmod",
  "ssn": "11165102",
  "salary": 4600.00,
  "superssn": "761100",
  "dno": NULL,
  "phone": 12345
}
```
- a) Correct
- b) Not correct

<details>
<summary>Answer</summary>
<b>Answer: b)</b>  
The JSON document is not valid because NULL should be written in lowercase as null.
</details>

---

### Question 14
**Does the following code represent a JSON document in a standard format?**
```json
{
  "ssn": "112341102",
  "bdate": "1968-01-12",
  "address": "2342 May, Atlanta, GA",
  "salary": 46500.00,
  "superssn": "11541100"
}
```
- a) Correct
- b) Not correct

<details>
<summary>Answer</summary>
<b>Answer: a)</b>  
The JSON document is valid.
</details>

---

### Question 15
**Does the following code represent a JSON document in a standard format?**
```json
{
  "fname": "Justin",
  "lname": "Mark",
  "ssn": "111111102",
  "salary": 40000.00,
  "superssn": "111111100",
  "phone": 12345
}
```
- a) Correct
- b) Not correct

<details>
<summary>Answer</summary>
<b>Answer: a)</b>  
The JSON document is valid.
</details>
