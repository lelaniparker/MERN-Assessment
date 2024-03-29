# MERN Assessment

## Authors

* **Carlie Hamilton** – [BlueCodeThree](https://github.com/BlueCodeThree)
* **Lelani Parker** – [Lelani82](https://github.com/Lelani82)
* **Tony Huynh** – [t-hnh10](https://github.com/t-hnh10)

## AnalyzeVit

### Purpose

The purpose of AnalyzeVit is to provide a resource for the general public to compare vitamin content of the many products available on the market. The client identified a void in the market, especially in Australia, which has generally seen a multitude of cumbersome websites lacking simplicity and usability.

It is often an incredibly overwhelming experience when comparing multiple vitamins and supplements simultaneously, especially when the products are multivitamins. The labelling, packaging and provision of health information is generally inconsistent that can further add to the confusion. AnalyzeVit aims to solve this confusion by providing information from a large data set to the public in a consistent and usable format.

### Functionality / Features

AnalyzeVit will consist of several features as outlined below.

#### Search Function

A search function will allow the user to seek information regarding a certain vitamin. The website will query the database and return a list of products that contain said vitamin. The results will be presented in an order that will allow the user to determine which products contain a significant amount of the vitamin or other ingredient they are interested in.

#### Blog

The website will contain a blog function to allow trusted health professionals to provide nutritional information and advice. This is aimed at those who are new to the use of vitamins and supplements. It is an important feature in providing a complete experience for users who wish to learn about vitamins, nutrition and health in general.

#### User Dashboard / Wishlist

Once a user has signed up for an account with AnalyzeVit, they will be able to login to a user dashboard. Here, users will be able to change their details or subscribe to the newsletter should they wish to stay updated with the website's new features or offers that may be provided.

An important feature of having a user account will include being able to maintain a wishlist consisting of vitamin and supplement products. The choice of vitamins on the market is astounding and consumers are often inundated with very similar products. Having researched various products on AnalyzeVit, they can directly add items they are interested in directly to the inbuilt wishlist. This will negate the need to maintain notes elsewhere and centralise all of the user's needs in one place.

### Target Audience

AnalyzeVit recognises a market that encompasses two groups of people who benefit from being informed about vitamins and health supplements.

The first group consists of young, urban professionals who are often too busy to place health as a primary concern. This is where the simplicity and usability of AnalyzeVit will benefit this particular group as they often seek sources of information that are as concise and easy to understand as possible. This group also has a tendency to use their mobile devices often and have considerable technical knowledge in navigating more complex features.

The second group consists of fathers and mothers who, often after giving birth, struggle to balance the responsibilities of caring for their child, and ensuring the health and wellbeing of their family members. This group tends to struggle with overly technical features as they consider them complicated. Thus, they appreciate having simple tools and features.

## Tech Stack

![Tech Stack](docs/mern.jpg)

Database: [MongoDB](https://www.mongodb.com/)

MongoDB is a general purpose, document-based, distributed database that stores data in JSON-like documents. As a NoSQL database, it defies the complexity and limitations of traditional, legacy relational databases.

The benefits of using MongoDB include:

* efficient, scale-out architecture;
* the ability to handle high volumes of structured, semi-structured, and unstructured data – particularly useful to data sets that do not confirm to strict standards; and
* being schema-less meaning it works well with today's software development methodologies that involve agile sprints and frequent code pushes.

Backend: [Node.js](https://nodejs.org/en/) & [Express.js](https://expressjs.com/)

Express is a minimal and flexible Node.js web application framework that provides a large set of features for web applications.

The development team decided to use Express due to it having a myriad of HTTP utility methods and middleware. Express also provides a thin layer of fundamental web application features, without obscuring Node.js features.

Frontend: [React](https://reactjs.org/)

React is a JavaScript library for building user interfaces.

One of several important features of React include the ability to create components to quickly and efficiently build user interfaces. React also streamlines how data is stored and handled, using state and props.

## Dataflow Diagram

![Dataflow Diagram](docs/DataflowDiagram.png)

## Application Architecture Diagram

![Application Architecture Diagram](docs/ApplicationArchitecture.png)

## User Stories

![User Stories](docs/UserStories.png)

### User Personas

To assist with the writing of User Stories, User Personas were created in order to allow the team to learn about and focus on the spectrum of goals and needs of our users. 

![User Persona 1](docs/Persona1.png)
![User Persona 2](docs/Persona2.png)

## Wireframes

![Wireframes](docs/Wireframes.png)

## User Flow Diagram

![User Flow Diagram](docs/UserFlowDiagram.png)

## Trello Board Screenshots

Monday 2 Dec 2019
![Trello Day 1](docs/trello_2019-12-02.png)

Tuesday 3 Dec 2019
![Trello Day 2](docs/trello_2019-12-03.jpg)

Wednesday 4 Dec 2019
![Trello Day 3](docs/trello_2019-12-04.jpg)

Monday 9 Dec 2019
![Trello Day 4](docs/trello_2019-12-09.jpg)

Tuesday 10 Dec 2019
![Trello Day 5](docs/trello_2019-12-10.jpg)

Wednesday 11 Dec 2019
![Trello Day 5](docs/trello_2019-12-11.jpg)

## Planning Methodology

The **Kanban methodology** is the framework of choice for this project, allowing us to implement Agile software development while benefitting from planning flexibility, shortened time cycles, fewer bottlenecks and continuous delivery.

For this project, the development team has decided to use [Trello](https://trello.com/). It is a fast and simple way to create a digital Kanban board.

|  | Standard |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Cadence | Continuous flow, no fixed time sprints allowing for flexible time management. |
| Release Methodology | Continuous delivery, deployment will occur regularly as features are completed. |
| Roles | No required roles, development team will work together by pair programming. Members will self-assign tasks from the Kanban board as they are required. |
| Key Metrics | Cycle time team spends working on a particular task. Should a task require more than three days, at least two members will work on that particular task together. |
| Change Philosophy | Change can occur at any time, team members will ensure Kanban board remains current throughout project. |
| Stand-ups | The team is to hold a stand-up each working day of a development cycle. <br>What did I do yesterday? What will I do today? Are there any impediments in my way? |
| Source Control | Feature Branch Workflow. Code changes are made in feature branches instead of the master branch, using a single central repository owned by [Lelani](https://github.com/Lelani82). Once changes are committed to a local repository and pushed to feature branch, the team member responsible will create a pull request on GitHub. At least one other team member will review the changes in the pull request. In the absence of issues, these changes can be merged into the master branch by any team member. |
| Client Communication | The team is communicating with the client through the use of Slack. Correspondence is to occur at a minimum of once a week. |