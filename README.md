# Sapientnitro Exercise

TECHNOLOGIES:
=========

1: Html5/css3 <br />
2: jQuery <br />
3: node.js <br />
4: mongodb <br />
5: mongoose <br />
6: Template Engine: Jade <br />
7: Framework: express

LOGIC:
=========

The application saves the items from Cart.json to mongodb database and loads from the database.

Once the user removes all the cart items. The application again fetched items from Cart.json and saves to mongodb.


Install packages
=========

Start the node server by default it is running on port: 3000.

Install npm packages. I have all the dependencies in package.json

<code> npm install </code>


<br/>

RUNNING APP
-----

npm start <br />
OR
node ./bin/www <br />
OR
nodemon ./bin/www <br />
OR
forever start ./bin/www <br />

Thats all.


SOME SAMPLE COUPON CODES
===========

['DS1', 'JF5', 'JF10', 'PROMO20'] <br />

DS1: 1% <br />
JF5: 5% <br />
JF10: 10% <br />
PROMO20: 20% <br />

DISCOUNT LOGIC
===========

3 items in cart - 5% discount on subtotal amount <br />
3-6 items in cart - 10% discount on subtotal amount <br />
>6 – 25% discount on subtotal amount <br />

JS DESIGN PATTERN
===========

Prototype


SOME SNAPSHOTS:
==========


![alt tag](http://s30.postimg.org/6h9c80xup/image.png)
![alt tag](http://s23.postimg.org/p5ygeg32z/image.png)
![alt tag](http://s27.postimg.org/i3msg4u2r/image.png)