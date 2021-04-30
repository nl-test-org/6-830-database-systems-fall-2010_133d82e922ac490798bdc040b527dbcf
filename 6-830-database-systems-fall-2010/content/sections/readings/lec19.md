---
course_id: 6-830-database-systems-fall-2010
layout: course_section
menu:
  leftnav:
    identifier: 6868c6cc27a21403813cfceeed1d1ca8
    name: NOSQL
    parent: 607e580d09fdcfa00f08a87ae0de6ad6
    weight: 210
parent_title: Readings
title: 'Lecture 19: NOSQL'
type: course
uid: 6868c6cc27a21403813cfceeed1d1ca8

---

Read:

Chang, Fay, et al. "Bigtable: A Distributed Storage System for Structured Data." OSDI, 2006. (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf))

Bigtable is a storage system for structured data; it is essentially a compressed, horizontally partitioned, column-oriented database with some interesting properties that allow it to reach "web scale".

As you read the paper, consider the following questions:

1.  In what ways does Bigtable replicate the behavior of a relational database? How is it different?
2.  Could Google have built Bigtable using a relational system? Would that have been a good idea? Why or why not?
3.  What consistency guarantees does Bigtable provide in the face of failures?
4.  What is a distributed lock service?