# Reading List
A list of articles I've read and some thoughts about them

## 2025

| Read | Paper Title    | Thoughts |
| -------- | ------- | ---- |
| :black_square_button: | Looking for new aticles... Suggestions welcome!  | ... |
| :white_check_mark: | [What Goes Around Comes Around... And Around](https://db.cs.cmu.edu/papers/2024/whatgoesaround-sigmodrec2024.pdf)    | Such a great overview of all the different kinds of DBMS and their strengths and weaknesses. Looking forward to the 2044 paper. |
| :white_check_mark: | [Why Files If You Have a DBMS?](https://www.cs.cit.tum.de/fileadmin/w00cfj/dis/papers/blob.pdf)    | A really elegant way to incorportate files into DBMS transactions whilst keeping them accessible outside of the DBMS. |
| :white_check_mark: | [Cloud-Native Database Systems and Unikernels: Reimagining OS Abstractions for Modern Hardware](https://www.cs.cit.tum.de/fileadmin/w00cfj/dis/papers/cumulus.pdf)    | Great idea to take advantage of the relatively recent shift towards cloud. If DBMS providers are freed from their restrictions of supporting all kinds of operating systems, there's a lot of benefit from targeting a specific operating system or operating system architecture. This particular idea seeks to take advantage of the abstraction layer provided for cloud VMs and use this to implement DBMS specific requirements for IO/CPU usage.|
| :white_check_mark:  | [MotherDuck: DuckDB in the cloud and in the client](https://www.cidrdb.org/cidr2024/papers/p46-atwal.pdf)     | Really fascinated with the hybrid query execution model described here and the possibilities for privacy and cost optimization. Scaling by simply upping CPU/Memory is quite a simple and elegant way of solving the scaling problem which is only possible thanks to the archetecture. |
| :white_check_mark:    | [Scalability! But at what COST?](https://www.usenix.org/system/files/conference/hotos15/hotos15-paper-mcsherry.pdf)    | Was a nice reminder that not all problems scale well when their nature makes them less paralisable. Even for problems that are suited, COST appears to be a good thing to keep in mind to determine if a system can overcome the distribution overhead to be faster than a single node.  |
