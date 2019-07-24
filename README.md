Plan for first day:

1)	Introduction 
2)	Hands on Front End Framework (Angular)
3)	Hands on Backend Frameworks (nodejs, Express and Mongo)

Plan for the second day:
       Together we will develop a To-do list app and then the participants can enhance it and doubts will be cleared. 


Prerequisite:
Go through this links:
 https://www.w3schools.com/js/
 https://angular.io/guide/quickstart




Steps to Install nodejs

Link
https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions

1) open terminal and execute this command
     curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -

2) then execute
     install sudo apt-get install -y nodejs

3)then execute
     sudo apt-get install -y build-essential

Verify the versions of node and npm by executing, “node -v”  it should be v6.11.4  and “npm – v” it should be v3.10.10 (make sure the versions are equal or higher to the version mentioned )


Steps to Install MongoDb 

Link:
https://docs.mongodb.com/v3.0/tutorial/install-mongodb-on-ubuntu/

1)open terminal and execute this command 
   sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 7F0CEB10

2) Then execute
         echo "deb http://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.0.list

3)Then execute
sudo apt-get update

4) Then execute
sudo apt-get install -y mongodb-org

5) Then execute
sudo apt-get install -y mongodb-org=3.0.15 mongodb-org-server=3.0.15 mongodb-org-shell=3.0.15 mongodb-org-mongos=3.0.15 mongodb-org-tools=3.0.15

6) Start MongoDB by executing
   sudo service mongod start
