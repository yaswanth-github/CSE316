# CSE 316 Assignment
This repository contains my solutions for Simulation-based 
Academic Task of Operating System CSE316 for the Academic Year 2022 (Semester 4).

## Personal Information

Name : Lankadasu Naga Venkata Yaswanth

Registration Number : 12104843

Roll Number : K21CHA10

Section : K21CH

Group : 1

## Question

Q1. There are 3 student processes and 1 teacher process. Students are supposed to do their 
assignments and they need 3 things for that-pen, paper and question paper. The teacher has an 
infinite supply of all the three things. One student has pen, another has paper and another has 
question paper. The teacher places two things on a shared table and the student having the 
third complementary thing makes the assignment and tells the teacher on completion. The 
teacher then places another two things out of the three and again the student having the third 
thing makes the assignment and tells the teacher on completion. This cycle continues. WAP 
to synchronise the teacher and the students.

• Two types of people can enter into a library- students and teachers. After entering the 
library, the visitor searches for the required books and gets them. In order to get 
them issued, he goes to the single CPU which is there to process the issuing of 
books. Two types of queues are there at the counter-one for students and one for 
teachers. A student goes and stands at the tail of the queue for students and 
similarly the teacher goes and stands at the tail of the queue for teachers (FIFO). If 
a student is being serviced and a teacher arrives at the counter, he would be the next 
person to get service (PRIORITY-non preemptive). If two teachers arrive at the 
same time, they will stand in their queue to get service (FIFO). WAP to ensure that 
the system works in a non-chaotic manner.

• If a teacher is being served and during the period when he is being served, another 
teacher comes, then that teacher would get the service next. This process might 
continue leading to increase in waiting time of students. Ensure in your program 
that the waiting time of students is minimized.


## Want to compile manually?
- Compile by firing the following command in the respective TASK directories
```sh
$ gcc filename.c
$ gcc os_sba1.c
```
- Run the executable object file by issuing the following command
```sh
$ ./a.out
```
