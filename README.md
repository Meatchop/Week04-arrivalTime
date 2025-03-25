# Week04-arrivalTime
compile:
gcc printDepartureTime.c calculateDepartureTime.c calculateTravelTime.c main.c -o main


decription:
Write a computer program that computes the time one must leave in order to reach a certain
destination by a designated time.
You need to deal only with arrivals occurring later in the same day as the departure.
The user needs to provide
- the desired arrival time in terms of the hour and minute of arrival,
- the distance to the destination in kilometers, and
- the average travel speed (jn km/hr)
Your need to write modular program where a function takes the input provided bby the user
and the function should retrun the departure time on a 24-hour clock. For example, if the
departure time is (8:30 p.m, the function should return 2030. However, your main program
should display: “The departure time is 8:30 PM”.
