# Document your edge case here
- To get marks for this section you will need to explain to your tutor:
1) The edge case you identified

Currently in the web application you are allowed to enter a student to the marks manager with the same course multiple times. This doesn't make sense as one student can only have one grade for a course and not have multiple grades for a single subject.

2) How you have accounted for this in your implementation

This has been accounted for in the my implementation where before creating a student the program first checks if there is already a student in the marks manager that has the same name and has been marked for the same course. If this is true then an error is generated and the student cannot be added. Otherwise add student to the marks manager.