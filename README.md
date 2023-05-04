Download Link: https://assignmentchef.com/product/solved-csci203-assignment-2-properties-of-queues-and-their-management
<br>
Your task for this assignment is to investigate some of the properties of queues and their management.

You should write a program which simulates the queuing and service of airline passengers.

Your program should first read in a file name from standard input and then open this file and read data from the named file.

The input file will contain the following data:

<ul>

 <li>The number of first/business class servers in the system</li>

 <li>The number of tourist class servers in the system</li>

 <li>A set of passengers, each consisting of an arrival time, a class and a service time.</li>

</ul>

o Class is an integer where 0 indicates a tourist class passenger and 1 indicates a first/business class passenger.

<ul>

 <li>This set is terminated by a dummy record with arrival time and service times all equal to 0.</li>

 <li>Note: the arrival times are sorted in ascending order.</li>

</ul>

The simulation is to be of an airline check in system with two sets of servers, first/business class and tourist class, with a single queue associated with each set. Customers arrive in the system and are served by a server of the appropriate class. If all servers of a particular type are busy, the customer will enter either the first/business or tourist class queue as appropriate.

The simulation should be run until the last customer has left the system.

The simulation will run twice, in the first run each server will only serve passengers of the appropriate class. In the second run the first/business class servers will be able to serve passengers in the tourist class queue if no first/business class customers are waiting.

Output, to standard output will consist of the following data for each run:

<ul>

 <li>Number of people served.</li>

 <li>Time last service request is completed.</li>

 <li>Average total service time (this includes time spent in a queue).</li>

 <li>Average total time in queue(s). Both overall and separate.</li>

 <li>Average length of queue. For each queue and overall.</li>

 <li>Maximum Length of queue. For each queue and overall.</li>

 <li>Total idle time for each server.</li>

</ul>

<strong>Notes:</strong> Do not use classes – structs are ok but no function pointers in them.

Do not use the STL

There will be no more than twenty servers of each type (40 total)

Each of the two queues will never have more than 500 people in them

The simulation should be <strong>discrete</strong>, i.e. event driven. There should not be a fixed length ‘tick’.

Programs may be written in any of C, C++, Java and Python. Programs which do not compile and run will receive no marks.

Programs should be appropriately documented with comments.

Programs should be submitted via moodle as ass2.ext where <em>ext</em> is one of c, cpp, java or py.


