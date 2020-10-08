# magicpotion

For the Magic Potion website I used the Python framework, Django, as the main stack for this web applicaiton. I also used HTML, CSS, and Javascript throughout this project. 

For the data schema in this project I used 5 Models that are found in the models.py file.

1. User- This is a built-in Django model that allows us to register each customer. This contains username, first name, last name and email, 

2. Customer - This contains the user, name and email.

3. Product - This contains the name, the price and the image of the product -- which in this case would be the Magic Potion. (More products can be added)

4. Order - This model shows the order that has been placed. It includes the customer, date ordered and transaction identification code.

5. OrderItem- This represents the item that is ordered. Contains the product, quantity and date ordered.

6. ShippingAddress- This contains the shipping information. Contains customer, order, address, city, state, zipcode and date. 

While this project was meant to represent just one product, this site is built to add many more which means it could scale very well. Through the admin panel, products can be easily added and put on the website just by filling in the name, price and image!

The front end architecture is a very simple one, but has the ability to be scaled up, which is why I choose it. I also tried to match Curology's color-scheme to the page just to give an idea. Normally, I would match Curology's design scheme to this for a real launch! And for this site, Javascript was used to send data from the front-end to the back-end. 

The API architecture is set up in way that javascript is used to send data to the back-end. However, if the customer is not a logged in user, it uses the cookies to send the data. 

If I were to do this again, I would attempt it in React and Laravel. I would try to use the stacks that Curology uses to see if I can add and improve on the functionality of the site. 

To improve on this, I would focus more time on the design aspect of the project, it takes a bit longer when doing the full-stack, but I would focus on implementing the styles and designs from Curology's actual site. 

