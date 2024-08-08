# Fleet_Tracking_System

There are 3 main significant outputs (Insights of truck conditions, Alert email of repairing truck that sends to drivers, fleet tracking operations) in the system. Personal contirbution focused on fleet tracking.

Step 1:
login to "https://992382524623.signin.aws.amazon.com/console" using:

Username: User1
&
Password: HanChung123

Step 2: 
Search S3 and find the "fleettracking" bucket to open index.html and simulator.html individually. 

You're now good to use it! It basically monitors how four trucks run on the map along with its coordinates (you can open up your developer tools to monitor trucks' operations on both html files).


*Files in the "lambda" folder were configured in AWS Lambda function, they are used to test and run with four other functions that work alongside with the whole system. 
