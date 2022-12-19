# Airplane-Seating

Ruby Program that helps seat audiences in a flight based on the following input and rules.

Rules for seating:
- Always seat passengers starting from the front row to back, starting from the left to the right
- Fill aisle seats first followed by window seats followed by center seats (any order in center seats)

Input to the program will be
- A 2D array that represents the rows and columns (eg - [[3,2], [4,3], [2,3],[3,4])
- Number of passengers waiting in queue.(eg -30)

Output of the program will be
 - [19 25 01] [02 26 27 03] [04 05] [06 28 20]
   [21 29 07] [08 30 XX 09] [10 11] [12 XX 22]
              [13 XX XX 14] [15 16] [17 XX 23]
                                    [18 XX 24]

Prerequisites:-
Ruby version Used- 3.1
Devkit Installer-3.1.3-1-x64
System - Windows 10
