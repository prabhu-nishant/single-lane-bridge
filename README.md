This is a Java implementation of a one lane bridge. Cars coming from the north and the south arrive at a one lane bridge and only one car in the same direction can pass through.

 Start with Southbound: 4 cars and Northbound: 3 cars
 
Rules:
1. Cars >=3 or the direction with higher number of cars lined up has priority to cross the bridge.
2. If car numbers are equal on both directions, the priority switches to opposite side.
3. Each side wll have a car added every 3 seconds.
4. After entering the bridge a simulated car should leave it after 1 second.
5. Program can break if queue on either side becomes zero.

Output:
southbound > northbound : Priority southbound
3 southbound cars remain, 3 northbound cars
northbound = southbound : Priority is northbound
2 northbound cars remain, 3 southbound cars
1 northbound cars remain, 3 southbound cars
3 seconds done. One car added to each direction
Total southbound:4 & northbound:2
southbound > northbound. Priority changes to southbound
2 southbound car remain, 2 northbound cars
northbound = southbound: Priority is northbound
..
..
..


Note:
Java concurrency APIs cannot be used in the solution.
