Choose ONE of the following tasks.
Please do not invest more than 2-4 hours on this.
Upload your results to a Github repo, for easier sharing and reviewing.

Thank you and good luck!



Code to refactor
=================
1) app/Http/Controllers/BookingController.php
2) app/Repository/BookingRepository.php

Code to write tests
=====================
3) App/Helpers/TeHelper.php method willExpireAt
4) App/Repository/UserRepository.php, method createOrUpdate


----------------------------

What I expect in your repo.

1, A readme with:   Your thoughts about the code. What makes it amazing code. Or what makes it ok code. Or what makes it terrible code. How would you have done it. Thoughts on formatting. Logic.. 

2.  Refactor it if you feel it needs refactoring. The more love you put into it. The easier for us to asses.  

Make two commits. First commit with original code. Second with your refactor so we can easily trace changes. 

NB: you do not need to set up the code on local and make the web app run. It will not run as its not a complete web app. This is purely to assess you thoughts about code, formatting, logic etc


So expected output is a GitHub link with either

1. Readme described above + refactored code 
OR
2. Readme described above + a unit test of the code that we have sent

Thank you!


1. BookingController 
User Roles should be defined in database schema and then assign it to the usel by using role user model instead of storing it to env file.
Booking functions should optimized like: 'distanceFeed()' is very messy and lengthy. it should be simple and in associative array to deal with these type of situations.

2. BookingRepository
User roles and their jobs should be in database then fetch them by relational table like with one to many relation job_type -> jobs
instead of ceil function we should use pagination function. BookingRepository have too much useless code and we can improve it by optimized the data and the way of data expressions.
 


