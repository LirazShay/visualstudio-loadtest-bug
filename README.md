# visualstudio-loadtest-bug
For Microsoft only  
Steps to reproduce the bug:
1.	I have vs2019 + vs 2017 installed, both with Web and Performance Tests
2.	In vs2019 + vs 2017 I logged in and license is valid 
3.	I have created a new project of Web and Performance Tests
4.	Created new unit test (empty test)
5.	I created loadtest, added the unit test to the loadtest
6.	Defined test duration of 20 seconds
7.	I use the default test settings (local) in the next executions
8.	Run the test from VS2017 – OK
9.	Run the test from VS2019 – OK
10.	Run the test from script using mstest of version 2017 - OK
11.	Run the test from script using mstest of version 2019 – Error: “Visual Studio Enterprise is required to execute the test.”
