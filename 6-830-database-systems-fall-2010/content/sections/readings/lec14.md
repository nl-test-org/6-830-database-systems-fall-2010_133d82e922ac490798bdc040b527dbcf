---
course_id: 6-830-database-systems-fall-2010
layout: course_section
menu:
  leftnav:
    identifier: 08e7d76a03d5dddb0d61b0f5d06eecc5
    name: Degrees of Consistency
    parent: 607e580d09fdcfa00f08a87ae0de6ad6
    weight: 160
parent_title: Readings
title: 'Lecture 14: Degrees of Consistency'
type: course
uid: 08e7d76a03d5dddb0d61b0f5d06eecc5

---

Read:

Gray, Jim, et al. "Granularity of Locking and Degrees of Consistency in a Shared Data Base." From _Modeling in Data Base Management Systems_. Edited by G. M. Nijssen. 1976. In the Red Book.

This paper presents two distinct ideas: first, the notion that there is a "hierarchy of locking" — e.g., that databases can lock pages, tables, tuples, or fields, and that there is a tradeoff between these various degrees of locking. Second, the paper presents that idea that there are different degrees of consistency which transactions can require, and those different degrees imply different locking disciplines with different performance characteristics.

As you read the paper, consider the following questions:

1.  What is the tradeoff between coarse granularity (e.g., table-level) and fine granularity (e.g., tuple-level) locks in a database system?
2.  How does hierarchical locking help address the phantom problem (hint: see page 374 and the discussion of index-interval locks.)
3.  What are the performance tradeoffs between the different degrees of locking?
4.  How does degree-0 locking ensure compatibility with all other locking modes?