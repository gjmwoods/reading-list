# Reading List
A list of articles I've read and some thoughts about them

## 2025

| Read | Paper Title    | Thoughts |
| -------- | ------- | ---- |
| :black_square_button: | Looking for new aticles... Suggestions welcome!  | ... |
| :black_square_button: | [PolarDB-MP: A Multi-Primary Cloud-Native Database via Disaggregated Shared Memory](https://zhangyingqiang.com/paper/PolarDB_Multi_Primary.pdf)    | ... |
|  :black_square_button: | [VCrypt: Leveraging Vectorized and Compressed Execution for Client-side Encryption](https://www.openproceedings.org/2025/conf/edbt/paper-347.pdf)    | ... |
| :white_check_mark: | [The Cambridge Report on Database Research](https://arxiv.org/abs/2504.11259)    | Sounds like many interesting topics we're discussed. Was great to see dedicated time to "Human-Centric Data Issues".  These should be treated as just as important as the techinical challenges around data management. |
| :white_check_mark: | [Anarchy in the Database: A Survey and Evaluation of Database Management System Extensibility](https://vldb.org/pvldb/vol18/p1962-kim.pdf)    | Feels like an underrated part of DBMSs which they highlight by observing the lack of research around database extensions. The more extensible a database is the more you empower users to solve their niche problems and give opportunities to grow your DBMS with the help of the community.  |
| :white_check_mark: | [What Goes Around Comes Around... And Around](https://db.cs.cmu.edu/papers/2024/whatgoesaround-sigmodrec2024.pdf)    | Such a great overview of all the different kinds of DBMS and their strengths and weaknesses. Looking forward to the 2044 paper. |
| :white_check_mark: | [Why Files If You Have a DBMS?](https://www.cs.cit.tum.de/fileadmin/w00cfj/dis/papers/blob.pdf)    | A really elegant way to incorportate files into DBMS transactions whilst keeping them accessible outside of the DBMS. |
| :white_check_mark: | [Cloud-Native Database Systems and Unikernels: Reimagining OS Abstractions for Modern Hardware](https://www.cs.cit.tum.de/fileadmin/w00cfj/dis/papers/cumulus.pdf)    | Great idea to take advantage of the relatively recent shift towards cloud. If DBMS providers are freed from their restrictions of supporting all kinds of operating systems, there's a lot of benefit from targeting a specific operating system or operating system architecture. This particular idea seeks to take advantage of the abstraction layer provided for cloud VMs and use this to implement DBMS specific requirements for IO/CPU usage.|
| :white_check_mark:  | [MotherDuck: DuckDB in the cloud and in the client](https://www.cidrdb.org/cidr2024/papers/p46-atwal.pdf)     | Really fascinated with the hybrid query execution model described here and the possibilities for privacy and cost optimization. Scaling by simply upping CPU/Memory is quite a simple and elegant way of solving the scaling problem which is only possible thanks to the archetecture. |
| :white_check_mark:    | [Scalability! But at what COST?](https://www.usenix.org/system/files/conference/hotos15/hotos15-paper-mcsherry.pdf)    | Was a nice reminder that not all problems scale well when their nature makes them less paralisable. Even for problems that are suited, COST appears to be a good thing to keep in mind to determine if a system can overcome the distribution overhead to be faster than a single node.  |
