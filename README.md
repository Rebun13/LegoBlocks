# LegoBlocks

## Description

You have an infinite number of 4 types of lego blocks of sizes given as (depth x height x width):
```
d	h	w
1	1	1
1	1	2
1	1	3
1	1	4
```
Using these blocks, you want to make a wall of height _n_ and width_m_. Features of the wall are:
- The wall should not have any holes in it.
- The wall you build should be one solid structure, so there should not be a straight vertical break across all rows of bricks.
- The bricks must be laid horizontally.
How many ways can the wall be built?

## Returns

- The first line contains the number of test cases _t_.
- Each of the next _t_ lines contains two space-separated integers _n_ and _m_. 

## Input

- int: the number of valid wall formations modulo $(10^9 + 7)$
