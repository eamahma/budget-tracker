# Online/Offline Budget Trackers

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Mock-Up

The following images show the web application's appearance and functionality:

Setting Service Workers to offline simulation no Internet connection.
![Setting Service Workers to offline simulation no Internet connection.](./assets/img/Heroku-Service-Workers-Offline.jpg)

Entering deposits and expenses in offline mode will be stored in IndexedDB under BudgetDB.
![Entering deposits and expenses in offline mode will be stored in IndexedDB under BudgetDB.](./assets/img/Heroku-IndexedDB-Offline.jpg)

As soon as network connection restored data will be pushed to online database and IndexedDB will be cleared.
![As soon as network connection restored data will be pushed to online database and IndexedDB will be cleared.](./assets/img/Heroku-Service-Workers-Online.jpg)

Data entered in offline mode updated into Mongodb after Internet connection restored.
![Data entered in offline mode updated into Mongodb after Internet connection restored..](./assets/img/MongodB-transaction.jpg)

## Link to live Heroku web page
The app deployed on Heroku and reachable at following link: 
* [Budget tracker deployed on Heroku](https://powerful-taiga-92657.herokuapp.com/)

## Link to Github repository
The code on Github can be found at following link: 
* [Budget tracker code on GitHub](https://github.com/eamahma/budget-tracker)

## Questions

* You can check my work on [GitHub](https://github.com/eamahma).

* You can reach me by [email](eamahma@gmail.com).