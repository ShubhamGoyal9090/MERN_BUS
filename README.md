

A Bus ticket booking application made using MERN Stack (MongoDB, Express js, React js, Node js)

The Bus ticket application is composed of the following Features:

### Front-End

* Sign-In & Sign-Up Pages.

* Uses Token based system, so only registered users can access the website  passport js.

* Password hashing using passport js.

* Has a profile page, which will display all information about the signed in user.

* List of cities for users to choose from (starting city & destination city). 

* Getting list of bus's of different companies with various details.

* Seat selection page has a very user friendly environment, which also generates dynamic forms for storing data's of passengers.

* Has a Confirmation page, which gets a debit card data using react-credit-cards. This version of the application does not include handling the payment process. 

* Final page has a ticket displaying component, it displays all passenger data and also generates a random number as a transaction ID.

### Back-End

* Uses Express js based application for the backend process.

* Uses MongoDB atlas for storing the collections.

* Uses passport js for authenticating user and token based system.

* Uses passport js for hashing the password before sending the data to the cloud.

* This version does not support dynamic seat data being stored from cloud.


This project also demonstrates:
* a typcial React project layout structure

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* Install node modules

   ```bash
   cd MERN-BUS-APP
   cd frontend
   npm install
   npm start
   
  open another terminal

   go current project directory
   
   cd backend
   npm install
   npm start
   ```

```bash if above comands does not work ```

```bash
   cd MERN-BUS-APP
   cd frontend
   npm install
   export NODE_OPTIONS=--openssl-legacy-provider
   npm start

   open another terminal

   go current project directory
   cd backend
   npm uninstall bcrypt;
   npm install bcryptjs;
   npm install bcrypt;
   npm start
   ```

---


