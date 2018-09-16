# Assignment #1: Service API

## Rationale

  - Identify from informal specification a domain model;
  - Design a business-oriented API according to this domain;
  - Compare several API design styles;
  - Peer-review an API developed by another group.

## Product Vision

Uberoo is a brand new food delivery service, which plans to start a new business in Sophia Antipolis mid-November. It allows restaurant owners to publish food items (single courses or full menus) on a web platform, and customers to order such items. The  items are then delivered by coursiers directly to the customers’ workplace. The originality of Uberoo, opposed to the existing platforms, is that instead of requiring a fixed delivery schedule, the system computes on the fly an Estimated Time of Arrival (ETA) for each delivery. Thus, an important Key Performance Indicator (KPI) for the platform is the TBETOF: “Time Before Eating The Ordered Food”.

## Expected work

For this first lab, the idea is to build an API supporting the Minimal and Viable Product (MVP) associated to the Uberoo platform. This MVP must support the following scenario, from the customer point of view:

  1. As Bob, a hungry student, I browse the food catalogue offered by Uberoo;
  2. I decide to go for an asian meal, ordering a ramen soup;
  3. The system estimates the ETA (e.g., 45 mins) for the food, and I decide to accept it;
  4. The restaurant can consult the list of meals to prepare, and start the cooking process;
  5. A coursier is assigned to my order, and deliver it on the campus

Your role here is to define the MVP, i.e., the minimal and viable service API supporting this scenario. It is your duty to identify the services to expose to support this very scenario only, and to properly implement it in a viable way (e.g., persistent data, automated acceptance scenarios).

After the end of this lab, we will extend the supported features to build a complete platform. do not over-engineer the work to be delivered at this step. The expected delivery is small in terms of business coverage, but it requires a non negligible effort to deliver it properly (e.g., justified API and choices, persistence layer, turn-key containers).

## Full Description:

  - [Uberoo Service API](https://docs.google.com/document/d/1ZBCIf5apypdvwvHjSGXSJnfNy5ymURKSQauvXXtId4Y/edit?usp=sharing)
