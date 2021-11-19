# Buffer-Overflow-Attack-
In this project, we exploited Buffer Overflow vulnerability for learning purpose 


# Buffer Overflow Attack Overview
In this lab we will understand the concept of Buffer overflow, and try to edit the file exploit.py to make the attack successful. Buffer Overflow Attack is defined as the condition when the program tries to fill the data beyond the boundaries of fixed length buffers. This vulnerability can be exploited by a malicious user to handle the flow control of the program, through execute arbitrary pieces of code. This vulnerability comes because the mixing of the storage of data (e.g. buffers) and controls (e.g. return addresses). The overflow of buffers can be affected on the control flow of the program, because the return address is changed .

the figure bellow explain how Boffer Overflow attack done:

<img width="605" alt="Screen Shot 1443-04-14 at 11 57 04 AM" src="https://user-images.githubusercontent.com/52821798/142595432-4c17ac03-ed58-4cf0-af51-29ddebd23b7b.png">

# Dates
this project started in 2020/11/12
updated in 2021/11/16
uploaded on github in 2021/11/19

# Table of contain
1.Shellcode
Before start the attack, we need a shellcode. A shellcode is the code to launch a shell. It has to be loaded into the memory so that we can force the vulnerable program to jump to it. 

2.stack.c
The Vulnerable Program



# References
- Second edition book, computer and internet security a hands-on approach, wenliang
- https://web.ecs.syr.edu/~wedu/seed/Labs_12.04/Software/Buffer_Overflow/
-  Aleph One. Smashing The Stack For Fun And Profit. Phrack 49, Volume 7, Issue 49. Available at http://www.cs.wright.edu/people/faculty/tkprasad/courses/cs781/alephOne.html
