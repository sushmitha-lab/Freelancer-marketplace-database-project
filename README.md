# Freelancer Marketplace Database Management System

## 📌 Overview
This project implements a **relational database system** for a freelancer marketplace platform (similar to Upwork or Fiverr).  
The database is designed to manage users, job postings, applications, bids, skills, and reviews while supporting analytical SQL queries for business insights.

The project demonstrates strong foundations in **database design, normalization, and SQL querying** using a real-world business scenario.

## 🧩 Business Problem
Freelancer platforms must efficiently manage:
- Multiple users (clients and freelancers)
- Job postings with budgets and deadlines
- Applications and competitive bidding
- Skill-based matching
- Reviews and performance tracking

Without a well-structured database, tracking job activity, freelancer performance, and platform analytics becomes inefficient and error-prone.

## 🏗️ Database Design
The database follows **normalized relational design principles** with clearly defined primary and foreign keys.

### Core Entities
- **Users** (Clients & Freelancers)
- **Jobs**
- **Applications**
- **Bids**
- **Skills**
- **JobSkills** (many-to-many relationship)
- **Reviews**

Relationships are enforced using foreign key constraints to ensure data integrity.

## ⚙️ Key Features
- Clients can post jobs with budgets and deadlines  
- Freelancers can apply or place bids on jobs  
- Jobs can receive multiple bids from different freelancers  
- Skills are mapped to jobs using a many-to-many relationship  
- Reviews and ratings are stored after job completion  
- Analytical SQL queries provide platform-level insights  

---

## 📊 SQL Capabilities Demonstrated
- Multi-table **JOINs**
- **GROUP BY** and aggregation functions (COUNT, AVG, MIN)
- Filtering and conditional queries
- Many-to-many relationship handling
- Analytical queries for reporting and insights


## 📈 Sample Analytical Queries
- Total number of bids per job  
- Jobs with the **lowest bid** and corresponding freelancer  
- Average rating of freelancers  
- Job application status tracking  
- Review and rating analysis  


## 🛠️ Tools & Technologies
- **SQL**
- **SQLite**
- **DB Browser for SQLite**
- **Relational Database Design**
- **Git & GitHub**


## 🚀 Learning Outcomes
- Designed a real-world relational database from scratch  
- Applied normalization and schema design best practices  
- Wrote complex SQL queries for analytics and reporting  
- Gained hands-on experience with database management tools  


## 📌 Use Cases
- SQL portfolio project
- Database design demonstration
- Interview-ready relational database example
- Analytics-focused SQL project


## 👤 Author
**Sushmitha Katherine Jayaraj**  
Graduate Student – Analytics  
Aspiring Data Scientist / Analytics Engineer



