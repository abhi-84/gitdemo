IoT based Home automation using Raspberry pi

This project uses Raspberry pi, Dropbox and Twitter to create Home Automation System

This project uses python programming and implements multithreading concepts to run 3 parallel threads, each performing specific 
task. 
Thread 1: maintains log status of appliances ; 
Thread 2: Monitor user's Twitter account any incomming requests ; 
Thread 3: Uploads log file on Dropbox cloud

In this project, Raspberry pi would continuously monitors user's Twitter account and updates the current status of applicance 
as log to Dropbox cloud. User can send predefined commands to pi via his Twitter account which would be read by pi and 
it helps to control the appliance.
As per this code, user can ask current status of specific appliance (currently only 2 appliances as per this code) and ask to 
turn off specific appliance via Twitter by sitting in any part of globe. If in future, user wanted to look into the status of 
various appliances on any specific day, he can do so via his Dropbox account (which is linked here) where logfile would also 
be maintained for all activities. Thanks


