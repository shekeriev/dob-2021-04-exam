# dob-2021-04-exam
A simple project to be used for the final practice exam for the DevOps Basics (2021.04) course at SoftUni. 

It is a set of three Docker containers, each with a dedicated role. Together they form a simple web application.

For successful completion of the challenge, you will have to implement the following steps:
 - (re)build the images;
 - (re)run the containers;
 - ensure the containers are part of the same network.

Please note that:
 - each container should be named after the following rule - **dob-role**, where *role* is either *producer*, *storage*, or *consumer*;
 - database password is expected to be **Exam-2021**;
 - web content is delivered by the *consumer* on port **5000**;
 - there is no particular order to follow when starting the containers.

*More details could be found in the downloadable **Practice Exam** document available in the **Regular Exam** section of the course.*