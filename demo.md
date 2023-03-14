---
layout: default
---

[back](./)
# Application Demo 
Below you will get a walkthrough tutorial of the customer, employee, and user interfaces and can access our interactive react based front end here to try out the different functionalities yourself. 

## Actors 
* The company has the primary responsibility of setting up the instance of the factory contract where most of the services will take place and has the latter responsibility of monitoring and verifying employee submitted hours 
* The customer scans a QR code presented by a service worker to access Servicechain.io, select the according factory, and has access to tipping and rating functions for the employee who served them
* The employee can input their work hours and access the tips and ratings recieved by customers 

## Customer Experience 
Once a customer logs in and choose the business to interact with: 

* Tip the service worker in ethereum that is transferred instantaneously
* Pay the bill which is automatically received by business
* Give the service worker a rating from 1-5 stars

! [Rating](send_rating.PNG)

! [Tipping](send_tip.PNG)

## Employee Experience 
Once an employee logs in they have access to: 

* Logging table where they can enter work hours/day of week
* Performance dashboard with aggregate stats on their average rating and total tips
* All customer names with their ratings and tips 

! [Hours](hr_req.PNG)

! [Stats](emp_stats.PNG)

## Manager Experience 
Once a manager logs in they have access to: 

* The ability to approve hours requested by employees 
* The ability to create a new business/warehouse 
* A performance dashboard axposed to aggregate statistics on the business
> * Total balance
> * # Approvals made
> * Detailed performance of each employee (average star rating, tips)

! [Service](create_service.PNG)

! [Stats](mger_stats.PNG)







