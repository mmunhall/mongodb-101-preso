##  Consistency, Availability, Partition Tolerance

*Pick Two*

<img src="images/cap_venn.png" height="50%" width="50%">

note:
    * Consistency: A read is guaranteed to return the most recent write for a given client.
    * Availability: A non-failing node will return a reasonable response within a reasonable amount of time (no error or timeout).
    * Partition Tolerance: The system will continue to function when network partitions occur.
