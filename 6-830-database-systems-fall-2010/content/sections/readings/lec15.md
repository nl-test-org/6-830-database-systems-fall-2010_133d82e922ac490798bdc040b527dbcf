---
course_id: 6-830-database-systems-fall-2010
layout: course_section
menu:
  leftnav:
    identifier: 83255771ee337769c6f31a15aa26beb9
    name: C-Store
    parent: 607e580d09fdcfa00f08a87ae0de6ad6
    weight: 170
parent_title: Readings
title: 'Lecture 15: C-Store'
type: course
uid: 83255771ee337769c6f31a15aa26beb9

---

Read:

Stonebraker, Michael, et al. _C-Store: A Column-oriented DBMS_. Proceedings of the 31st VLDB Conference, 2005. (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF](https://w6113.github.io/files/papers/cstore-vldb05.pdf))

This paper discusses the C-Store system, which is a read-optimized database system with a novel physical arrangement of data on disk, as well as an unusual approach to recovery and query processing

As you read the paper, consider the following questions:

1.  Why does the C-Store idea of arranging data as columns improve query performance?
2.  How does C-Store propose to do recovery? Is there an advantage to this approach?
3.  How does C-Store isolate transactions? Do you think this is a good idea?