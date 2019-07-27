This is the program written in C++ for booking seats in the theatre.
Continuous input queries of four types
1.add-screen<Screen-number><Number-of-rows><Number-of-seats-in-each-row><aisle-seats>
this function must add the given screen if not exist return success
else return failure

2.reserved-seat <Screen-Number><Row-Number><Seat numbers>
reserved given seats if possible return success
else return failure

3.get-unreserved-seats<Screen-Number><Row-Number>
must return all unreserved seats in given row.

4.get-contiguous-seats<Screen-Number><Rownumber><Start-point><Number-of-seats>
This case returns if there are continuos seats starting from  start point either to the left or right of give point with no break i.e now aisle seats in between.
If possible return success
else return failure. 

Input:

7

add-screen Screen1 12 10 4 5 8 9 

add-screen Screen1 12 10 4 5 8 9

reserved-seat Screen1 4 3 4 5 7

reserved-seat Screen1 4 3 4 5 6

get-unreserved-seats Screen1 4

get-contiguous-seats Screen1 4 2 2

get-contiguous-seats Screen1 4 3 2

Output:

success

failure

success

failure

1 2 6 8 9 10

success

failure
