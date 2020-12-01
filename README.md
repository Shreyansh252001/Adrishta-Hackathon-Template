## Team Number 1 - \I VOTED
The participants are required to fork this repository and create a public Github repository under their own username (Single repository per team). *Clone the repo on your local system and build on top of that*

The following created sections in this README.md need to be duly filled, highlighting the denoted points for the solution/implementation. 

**Please feel free to create further sub-sections in this markdown.** The idea is to understand all the particulars of your solution in a singular document.

### Project Overview

A brief description of my solution
I tried to solve the problem of Not being able to securley conduct elections of college council.i prepared various modules for admin voters participants results tab,i ensureed no duplicacy or repetition is there

* What is the proposed solution?

=======
i have created an app with php,mysql,css,js,ajax.project contains a Voter’s login side where a voter can Sign in to vote and Admin Panel where he/she can view total votes, add and list voters, positions, candidates and many more. While logging in from voter’s login, the user should provide Voters ID in order to log in to the system to vote. The voter’s id can be retrieved from the Admin Panel

### Solution Description

Admin has full control of the system, all the functions are to be performed from Admin panel. Here, the user can view total votes with respective voters name, add and list voters, positions, candidates, view ballot positions, edit election title and edit admin’s profile. To vote for an election, you need a voter and to add a voter, the user has to provide first and last name, password and upload a photo. Likewise, to add a position a short description and the maximum vote value should be provided. All the candidates can be views from the admin panel with their respective positions and similarly to add candidates for an election the user should provide a first name and last name, select position, upload a photo and write the platform.

Ballot positions can be maintained for the voters according to the admin’s will and the admin can change the election title easily anytime he/she wants. After all the votings, total votes can be viewed from Votes navigation, which displays Position with candidate and voter name. Before logging in as a voter, the user needs a voter account and a voter id. That can be retrieved from Voters List, the system generates Voters id automatically and the user has to copy it then paste in voter’s login section and provide a password to continue as a voter. A clean and responsive dashboard is provided in the admin panel for the easy management of the voting system. Voting system in PHP helps in easy management of the votes for certain objectives. Design of this project is pretty and responsive so that user won’t find it difficult to understand, use and navigate.

To run this project you must have installed virtual server i.e XAMPP on your pc (for Windows). 
Voter’s Login
Admin Panel
View and reset votes
CRUD Voters
CRUD Position
CRUD Candidates
Ballot Positions
Select Election Titles

#### Architecture Diagram

Affix an image of the flow diagram/architecture diagram of the solution
https://lucid.app/lucidchart/050212f3-bdb2-4943-8343-6c06908d435a/view?page=0_0#?folder_id=home&browser=icon
The free trial got over and line allowance trail was this much only also the time was getting over so i left it.

#### Technical Description

An overview of:
* What technologies/versions were used

* Setup/Installations required to run the solution
install Xampp server and run apache/mysql.vs code required.

* Instructions to run the submitted code
After Starting Apache and MySQL in XAMPP, follow the following steps

1st Step: Extract file

2nd Step: Copy the main project folder

3rd Step: Paste in xampp/htdocs/

Now Connecting Database

4th Step: Open a browser and go to URL “http://localhost/phpmyadmin/”

5th Step: Then, click on databases tab

6th Step: Create database naming “votesystem” and then click on import tab

7th Step: Click on browse file and select “votesystem.sql” file which is inside “database” folder

8th Step: Click on go.

After Creating Database,

9th Step: Open a browser and go to URL “http://localhost/votesystem/”

For Admin Panel

Final Step: Go To URL “http://localhost/votesystem/admin/”

Insert the username and password which is provided inside the “Readme.txt” file or see the file voters/candidates/admin in phpmyadmin local server.

### Screenshots

provided in a folder separately named screen shots
https://drive.google.com/drive/folders/1dfB2o_-FiXRVAfs8t88p2XuAefhyZK5t?usp=sharing

### Team Members
List of team member names and email IDs with their contributions.
|Member Name|Email|Contribution|
|-----------|-----|------------|
|Shreyansh Shukla|Shreyansh252001@gmail.com|Complete|

### References
Affix links to the online tools/repositories/blogs etc., which helped you along the development of the project
searched on youtube for voting system technologies.
https://www.w3schools.com/php/php_ajax_poll.asp
https://www.w3schools.com/sql/sql_foreignkey.asp
https://stackoverflow.com/questions/55273716/creating-a-javascript-voting-system
https://github.com/SoftUni/JavaScript-Applications/blob/master/2.%20Parse.com-Demos/Parse.com-JavaScript-AJAX-Examples/2.%20voting-system.html