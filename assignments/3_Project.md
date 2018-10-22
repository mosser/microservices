# Assignment #3: Project

## Objectives

  - Build and maintain an ecosystem of microservices;
  - Integrate micro-services using an Event-driven Architecture
  - Manage a-la-carte deployment 


## Deliverables

A public github project (no invitation, should be publicly cloneable). Your project MUST comply to the following installation rules:

  - `~ $ git clone http://url/of/your/repository the_project`
  - `~ $ cd the_project`
  - `the_project $ ./install.sh`
    - Load dependencies, Compile (if necessary)
  - `the_project $ docker-compose up -d`
    - build the local images and then start the system on localhost
  - `the_project $ ./run.sh`
    - Run the acceptance scenarios associated to your API.
  - `the_project $ ./load.sh`
    - Run a load test for your system.  
  - A PDF file describing the architecture and the design choices 




## User Stories

_The P.O. is still working on the backlog. Stay updated, new requirements (stories / personas) will appear each Monday._

### Personas

  - Gail, a student who lives in Sophia and often order (junk) food from food trucks;
  - Erin, a software developer working in a major company;
  - Jordan, restaurant chef;
  - Jamie, a coursier;

### Week 41: Initial Story set

  - As Gail or Erin, I can order my lunch from a restaurant so that the food is delivered to my place;
  - As Gail, I can browse the food catalogue by categories so that I can immediately identify my favorite junk food;
  - As Erin, I want to know before ordering the estimated time of delivery of the meal so that I can schedule my work around it, and be ready when it arrives.
  - As Erin, I can pay directly by credit card on the platform, so that I only have to retrieve my food when delivered;
  - As Jordan, I want to access to the order list, so that I can prepare the meal efficiently.
  - As Jamie, I want to know the orders that will have to be delivered around me, so that I can choose one and go to the restaurant to begin the course.
  - As Jamie, I want to notify that the order has been delivered, so that my account can be credited and the restaurant can be informed.

### Week 43: First evolution

New personna: Terry, restaurant owner.

  - As Jordan, I want the customers to be able to review the meals so that I can improve them according to their feedback;
  - As a customer (Gail, Brook, Erin), I want to track the geolocation of the coursier in real time, so that I can anticipate when I will eat.
  - As Terry, I want to get some statistics (speed, cost) about global delivery time and delivery per coursier.






