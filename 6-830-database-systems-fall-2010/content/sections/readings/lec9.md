---
course_id: 6-830-database-systems-fall-2010
layout: course_section
menu:
  leftnav:
    identifier: 75e1c741b2989e11b22add3535db6620
    name: Query Optimization
    parent: 607e580d09fdcfa00f08a87ae0de6ad6
    weight: 110
parent_title: Readings
title: 'Lecture 9: Query Optimization'
type: course
uid: 75e1c741b2989e11b22add3535db6620

---

In this lecture, we will discuss the problem of query optimization, focusing on the algorithms proposed in the classic "Selinger" paper.

Read the following papers:

*   Selinger, Patricia, M. Astrahan, D. Chamberlin, Raymond Lorie, and T. Price. "Access Path Selection in a Relational Database Management System." _Proceedings of ACM SIGMOD_ (1979): 23-34.
*   _Optionally_, you may also wish to look at: Mannino, Michael, Paichen Chu, and Thomas Sager. "Statistical Profile Estimation in Database Systems." _ACM Computing Surveys_ 20, no. 3 (1988): 191-221. This paper discusses many of the techniques that used to make query optimization and cost estimation practical in modern database systems. We will cover some of the ideas at a high level in class.

As you read, think about and come to class prepared to answer the following questions:

*   The Selinger paper claims to be 'optimal'. Under what assumptions is this optimality true? Can you think of a situation in which Selinger will definitely be non-optimal?
*   Query optimization is highly dependent on the effectiveness of cost estimation. The cost metrics that Selinger proposes are very simple; how would you make them more sophisticated? What is the impact of more sophisticated cost metrics on the performance of a database system?