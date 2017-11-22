EXAMPLE:
========

+ Run commands in following order:
  1. creator 5 &
  2. ps
  3. changer 5 100
  4. creator 10 &
  5. ps

+ Result:
  1. first process with pid 5 is in running state
  2. now its priority is changed to 100
  3. now process with pid 10 is in running state
  4. Due to higher priority value process with pid 5 goes to runnable state

COMPARISION:ROUND-ROBIN vs PRIORITY_SCHEDULING:
===============================================

+ It is observed the average waiting time
for Round Robin Algorithm is considerably larger than
for Priority Algorithm. This means that if we use Round
Robin, the processes will need more time to finish
executing compared with Priority. For the examples I
have chosen, can be noticed that the average time for
the first algorithm is nearly twice the time of the other
algorithm. It seems like not a big deal, but in fact it is
since there are only four processes. Imagine what
would happen if there were much more.

+ [REFERENCE](http://www.ijcsi.org/papers/IJCSI-11-3-1-175-181.pdf)
**FOR MORE DETAILS REFER TO README**
