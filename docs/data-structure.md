# Data Structure

## Project Title
**Peer Tutoring Booking Platform**

---

# 1. Main Data Entities / Tables

| Entity / Table | Purpose | Example Records |
|----------------|---------|-----------------|
| Tutor | Stores tutor profile information including subjects, availability, and biography. | Tutor **T001** — Aye Aye, Subjects: Calculus, Statistics |
| Booking | Stores booking requests submitted by students. | Booking **B001** — Student: Shwe Yi, Tutor: T001, Status: Pending |
| Student | Stores basic student information used for booking sessions. | Student **S001** — Shwe Yi, Year 2 |

---

# 2. Field Definition

| Entity | Field Name | Data Type | Required | Example Value | Validation Rule | Search / Filter |
|--------|------------|-----------|----------|---------------|-----------------|-----------------|
| Tutor | tutor_id | Text / ID | Yes | T001 | Must be unique | No |
| Tutor | name | Text | Yes | Aye Aye | Cannot be empty | No |
| Tutor | subjects | Text / List | Yes | Calculus, Statistics | At least one subject | Yes |
| Tutor | availability | Text / List | Yes | Mon 14:00–16:00 | At least one available time slot | Yes |
| Tutor | bio | Text | No | Year 3 Math major with tutoring experience | Maximum 300 characters | No |
| Booking | booking_id | Text / ID | Yes | B001 | Must be unique | Yes |
| Booking | student_name | Text | Yes | Shwe Yi | Cannot be empty | No |
| Booking | tutor_id | Text / ID | Yes | T001 | Must exist in Tutor table | No |
| Booking | subject | Text | Yes | Calculus | Must match tutor's subject | Yes |
| Booking | requested_slot | Text / DateTime | Yes | Mon 14:00–16:00 | Must match tutor availability | No |
| Booking | notes | Text | No | Need help with derivatives | Maximum 300 characters | No |
| Booking | status | Text / List | Yes | Pending | Pending, Approved, Completed, Closed | Yes |
| Student | student_id | Text / ID | Yes | S001 | Must be unique | No |
| Student | name | Text | Yes | Shwe Yi | Cannot be empty | No |

---

# 3. Status Values

| Status | Meaning | Updated By |
|--------|---------|------------|
| Pending | Booking request has been submitted and is waiting for confirmation. | Admin |
| Approved | Booking request has been accepted. | Admin |
| Completed | Tutoring session has been completed successfully. | Admin |
| Closed | Booking has been cancelled or expired. | Admin |

---

# 4. Sample Records

Sample customer discovery and evaluation data are stored in:

- `/data/raw_responses.xlsx`
- `/data/nuf_evaluation.xlsx`

Sample prototype data will be added later as JSON or spreadsheet files inside the `/data` folder.

### Tutor Sample

| tutor_id | name | subjects | availability | bio |
|----------|------|----------|--------------|-----|
| T001 | Aye Aye | Calculus, Statistics | Mon 14:00–16:00 | Year 3 Math major |
| T002 | Min Khant | Programming, Java | Tue 10:00–12:00 | Computer Science student |
| T003 | Hnin Ei | English Writing | Fri 13:00–15:00 | English tutor |

### Student Sample

| student_id | name |
|------------|------|
| S001 | Shwe Yi |
| S002 | Su Su |
| S003 | Ko Ko |

### Booking Sample

| booking_id | student_name | tutor_id | subject | requested_slot | status |
|-------------|--------------|----------|----------|----------------|--------|
| B001 | Shwe Yi | T001 | Calculus | Mon 14:00–16:00 | Pending |
| B002 | Su Su | T002 | Java | Tue 10:00–12:00 | Approved |
| B003 | Ko Ko | T003 | English Writing | Fri 13:00–15:00 | Completed |

---

# 5. Entity Relationship

```text
+-----------+           +------------+           +-----------+
|  Student  |           |  Booking   |           |   Tutor   |
+-----------+           +------------+           +-----------+
| student_id|<--------->|student_name|           | tutor_id  |
| name      |           |booking_id  |<--------->| name      |
+-----------+           | tutor_id   |           | subjects  |
                        | subject    |           | availability|
                        | status     |           | bio       |
                        +------------+           +-----------+
```

---

# 6. Data Privacy

This prototype does **not** use real student or tutor personal information.

- All names, IDs, and records are fictional.
- No phone numbers or email addresses are stored.
- Student IDs used in demonstrations are placeholders.
- Only the minimum information required by **FR-15 (Data Privacy)** is displayed.
- Tutor profiles show only academic information such as subjects, availability, and biography.

---

## Summary

- **Entities:** 3
- **Tutor Fields:** 5
- **Booking Fields:** 6
- **Student Fields:** 2
- **Booking Statuses:** Pending, Approved, Completed, Closed
- **Primary Relationship:** One Tutor → Many Bookings, One Student → Many Bookings
