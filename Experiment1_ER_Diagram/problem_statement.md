# ER Diagram Workshop – Submission Template

## Objective
To understand and apply ER modeling concepts by creating ER diagrams for real-world applications.

## Purpose
Gain hands-on experience in designing ER diagrams that represent database structure including entities, relationships, attributes, and constraints.

---

# Scenario A: City Fitness Club Management

**Business Context:**  
FlexiFit Gym wants a database to manage its members, trainers, and fitness programs.

**Requirements:**  
- Members register with name, membership type, and start date.  
- Each member can join multiple programs (Yoga, Zumba, Weight Training).  
- Trainers assigned to programs; a program may have multiple trainers.  
- Members may book personal training sessions with trainers.  
- Attendance recorded for each session.  
- Payments tracked for memberships and sessions.

### ER Diagram:

<img width="1366" height="902" alt="image" src="https://github.com/user-attachments/assets/d832301f-149c-46ba-a7a5-493f9eacdd30" />

### Entities and Attributes

<img width="1142" height="356" alt="image" src="https://github.com/user-attachments/assets/f0faa6b8-3930-47c3-8b0a-d8d71e1076aa" />


### Relationships and Constraints

<img width="1077" height="305" alt="image" src="https://github.com/user-attachments/assets/3dc4cdac-df56-4327-9450-eae5974c01ba" />


### Assumptions
One membership type per member.

A program must have at least one trainer.

Personal training is optional and billed separately.

Attendance is recorded only when members participate.  

---

# Scenario B: City Library Event & Book Lending System

**Business Context:**  
The Central Library wants to manage book lending and cultural events.

**Requirements:**  
- Members borrow books, with loan and return dates tracked.  
- Each book has title, author, and category.  
- Library organizes events; members can register.  
- Each event has one or more speakers/authors.  
- Rooms are booked for events and study.  
- Overdue fines apply for late returns.

### ER Diagram:
<img width="1247" height="891" alt="image" src="https://github.com/user-attachments/assets/10a7b0c9-d584-4bab-80c4-639b735d6be1" />


### Entities and Attributes

<img width="956" height="325" alt="image" src="https://github.com/user-attachments/assets/a5d9607e-8b21-49fe-8f71-ebe3072ca54d" />


### Relationships and Constraints

<img width="759" height="278" alt="image" src="https://github.com/user-attachments/assets/33d05ff1-a84e-41f1-a147-34e20750111f" />


### Assumptions
Each book has only one copy in the database (copies could be modeled separately if needed).

Fines are tracked as part of loan record.

Members may or may not attend events.

Each event takes place in exactly one room.

---

# Scenario C: Restaurant Table Reservation & Ordering

**Business Context:**  
A popular restaurant wants to manage reservations, orders, and billing.

**Requirements:**  
- Customers can reserve tables or walk in.  
- Each reservation includes date, time, and number of guests.  
- Customers place food orders linked to reservations.  
- Each order contains multiple dishes; dishes belong to categories (starter, main, dessert).  
- Bills generated per reservation, including food and service charges.  
- Waiters assigned to serve reservations.

### ER Diagram:
<img width="1201" height="708" alt="image" src="https://github.com/user-attachments/assets/11a36b99-712d-4a34-b4d4-a890e48db4a6" />

### Entities and Attributes

<img width="1089" height="405" alt="image" src="https://github.com/user-attachments/assets/743beae8-426f-462d-9a75-639d49f421d9" />


### Relationships and Constraints

<img width="870" height="315" alt="image" src="https://github.com/user-attachments/assets/1d1ab949-414a-4c62-8b69-a39415a7653f" />


### Assumptions
Walk-in customers treated as reservations without advance booking.

One waiter handles a reservation at a time.

Service charge fixed per bill.

---

## Instructions for Students

1. Complete **all three scenarios** (A, B, C).  
2. Identify entities, relationships, and attributes for each.  
3. Draw ER diagrams using **draw.io / diagrams.net** or hand-drawn & scanned.  
4. Fill in all tables and assumptions for each scenario.  
5. Export the completed Markdown (with diagrams) as **a single PDF**
