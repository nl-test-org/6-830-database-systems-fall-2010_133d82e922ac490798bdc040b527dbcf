---
course_id: 6-830-database-systems-fall-2010
layout: course_section
menu:
  leftnav:
    identifier: ff78b687f1a3e5e058c2ac171ff64a6d
    name: Optimistic Concurrency Control
    parent: 607e580d09fdcfa00f08a87ae0de6ad6
    weight: 130
parent_title: Readings
title: 'Lecture 11: Optimistic Concurrency Control'
type: course
uid: ff78b687f1a3e5e058c2ac171ff64a6d

---

In this lecture, we will continue our discussion of concurrency control and study another approach for isolating transactions called "Optimistic Concurrency Control." Read:

Kung, H. T., and John T. Robinson. "On Optimistic Methods for Concurrency Control." _ACM Transactions on Database Systems_ 6, no. 2 (1981): 213-226. In the Red Book.

As you read, note any terms you are unfamiliar with and come to class prepared to answer the following questions:

*   When would you expect that optimistic concurrency control would outperform locking-based concurrency control?
*   Can optimistic concurrency control result in deadlock?
*   How would you implement optimistic concurrency control in SimpleDB?