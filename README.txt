       ####################################################
       # CPSC 351 (SPRING 2016) || PROGRAM 1 - 03/18/2016 #
       ####################################################

====================================================================

TEAM MEMBERS
********************************************************************
Angel Jimenez
ajl890889702@csu.fullerton.edu
Section 351-03

Contribution:
	- Jointly implemented/modified the sender and the
	  receiver file with rest of group.
	- Debugging of code.
	- Created DESIGN OF ASSIGNMENT 1
---------------------------
Tyler McConnell
tylerjmcc@csu.fullerton.edu
Section 351-02

Contribution:
	- Jointly implemented/modified the sender and the
	  receiver file with rest of group.
	- Debugging of code.
	- Created README FILE
---------------------------
Miguel Velasquez
Miguelvelazquez@csu.fullerton.edu
Section 351-03

Contribution:
	- Jointly implemented/modified the sender and the
	  receiver file with rest of group.
	- Debugging of code.
	- Created MAKEFILE.

====================================================================

GENERAL USAGE NOTES
********************************************************************
-  The purpose of this program is to synchronously transfer
   files between two different processes.  This is done by
   the use of shared memory and message queues.

-  This program will only run on UNIX/LINUX based operating
   systems.  It will not work on any version of Windows.

-  This program was written in C++.

====================================================================

HOW TO RUN
********************************************************************
-  First, download the .tar file and extract it to your 
   desired location.

-  Navigate to the directory which you extracted the .tar
   file to via the command line.

-  Run the MAKEFILE by typing "make" into the command line.

-  Run the SENDER process by typing in "./sender keyfile.txt"

-  Open up a new terminal, and navigate to the program 
   directory.

-  Run the RECEIVER process by typing in "./recv".

-  Screenshot:  http://s23.postimg.org/8p46gf68r/screenshot.png

====================================================================

RESOURCES
********************************************************************
How to Write a Read Me:
	- http://www.wikihow.com/Write-a-Read-Me

Software Analysis and Design
	- http://www.tutorialspoint.com/software_engineering
	  /software_design_basics.htm
	- http://www.tutorialspoint.com/software_engineering
	  /software_analysis_design_tools

Message Queues:
	- http://www.tutorialspoint.com/software_engineering
	  /software_analysis_design_tools
	- http://linux.die.net/man/2/msgsnd
	- http://linux.die.net/man/2/msgrcv

Shared Memory Segments:
	- http://beej.us/guide/bgipc/output/html/multipage/shm.html

Makefiles:
	- http://mrbook.org/blog/tutorials/make/

====================================================================