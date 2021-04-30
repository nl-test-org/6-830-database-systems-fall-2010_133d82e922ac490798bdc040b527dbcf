---
course_id: 6-830-database-systems-fall-2010
layout: course_section
menu:
  leftnav:
    identifier: 66567cf1bcf66bb733025efcf677f715
    name: Distributed Transactions
    parent: 607e580d09fdcfa00f08a87ae0de6ad6
    weight: 180
parent_title: Readings
title: 'Lecture 16: Distributed Transactions'
type: course
uid: 66567cf1bcf66bb733025efcf677f715

---

We will continue our discussion of parallel and distributed query processing. You should read:

Mohan, C., B. Lindsay, and R. Obermarck. "Transaction Management in the R\* Distributed Database Management Systems." _ACM Transactions on Database Systems_ 11, no. 4 (1986): 378-396. In the Red Book.

This paper discusses distributed transactions, addressing the problem of providing ACID-style semantics in a shared nothing environment.

As you read the paper, consider the following questions:

1.  In the "R\*" paper, how does the two phase commit (2PC) protocol work? What problem does it solve? What are the costs of using it?
2.  What is the significance of the Presumed Abort/Presumed Commit variants of 2PC? How do they reduce the overhead of 2PC? When should you choose one over the other?