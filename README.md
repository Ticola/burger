# Eat Da Burger!

### **Overview**

In this assignment, the project consisted of creating a tasty burger app. An app that uses _Node_, _Express_, _Handelbars_, and _MySQL_ to make it dynamic for the user to not only see the burgers available, but also have the ability to add their own burger creation to the list and once their all done deciding...Devour It!!!

- - -

### **How Can I Make My Own Burger?** 

1. The app when deployed will display possible burger options for you to "Devour".

2. User is also prompted to either select a burger that is ready to eat or request a new burger and place an order.

3. Finally, the app will display and update both the burgers you have already eaten and burgers you have created. Enjoy!

### **In-Depth View of How it all Comes Together**

1. `READ`

    * This function will read all the entries from the _MySQL_ database and render them to the _DOM_ with the help of a friend by the name of _Handlebars_.


2. `UPDATE`

    * This function will update a selected(_devoured_) burger which targets a route in _Express_ to change the data in the _MySQL_ database which then re-routes the information back to the index, where the selected burger is now rendered under "Already eaten!"

3. `CREATE`

    * This function creates a new burger using the request form at the bottom of the page, which targets a route in _Express_ to insert a new row in the _MySQL_ database. Secondly, re-routes the information back to the index, where the burger is now rendered under "Read to eat!"

- - -

`Eat Da Burger is made possible with:`
```
HTML
CSS
Bootstrap
Node
MySQL
Express
Handlebars
```

