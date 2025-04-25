# Parking-Lot-Management
Course: Data Structures and Algorithms
Course Code: COP 3530- CRN 14032
Name of the Student: Cheleyson Dorvilien
Instructor Name: Dr. Deepa Devasenapathy


Project Title: Parking Lot Management  


Title page

Project title:  Parking Lot Management 
Student name: Cheleyson Dorvilien, Thuan van, Lujens Pierre
Course: Data Structures and Algorithms (COP 3530- CRN 14032)
Date: 04/18/2025
Instructor: Dr. Deepa Devasenapathy



Introduction & Problem Statement:

Our inspiration for this project came from the new parking system we have at FGCU. We really liked how there’s a display to show how many spots are available in real time before we go in and find them all to be occupied.

 We then combine this with what we have learned in class, such as stack and queue to make a simple parking lot management system.





Objective & Scope:

Objective: 
Create a simple parking lot management system using stack and queue
Automatically assigns a parking spots with a first come, first served order using a queue
Reuse freed parking spots using a stack
Display the number of occupied and available spots in real time
An easy and clear interactive menu for users to interact



Scope:
There are 100 parking spots in total
1 vehicle per spot


Data Structures & Algorithms Used

Queue (First in, first out; FIFO) - This is used to assign parking spots in order of first come, first served, where spots are assigned according to the next available space in the queue.

Stack (Last in, first out; LIFO) - This is used to store the freed parking spot when a car leaves, so we can reassign the most recently freed spot to the next car




Implementation Highlights: 

We are just going to do a demonstration of the code

Results & Analysis: done

Innovation & Problem Solving: Some of the problems we faced and fixed was the problem of linear car removal by using a map , which is implemented as a binary search tree. This system assigns an ID to each vehicle and allows them to leave in any order.Handle the case when someone wants to park when the lot is full by checking for available and freed spaces and showing a message when there are no spaces available. Handle the case when the user wants to remove an invalid ID by checking if the ID exists and showing an error message if the ID is not found.
 
Conclusion and future work: For the future we could try to implement timed parking and reserved parking and spots.







