# HepsiburadaTestCase

## Test Case

1) Adding a product to the cart by logging in

- The user visits Hepsiburada.com site.
- User login is done.
- After the redirect, it is verified that the user login is done on the homepage
- The user will search for the product he wants to buy here.
- The user selects a product from the list of products displayed as a result of the Search (or a single result may also be returned).
- The product is selected from 2 different vendors for the selected product and added to the cart.
- It should be verified on the 'My Cart' page that the selected product has been added correctly.

2) Adding the specified product to the cart without user login

- The user visits Hepsiburada.com site.
- The user selects a product from the list of products displayed as a result of the Search (or a single result may also be returned).
- For the selected product, products from 2 different vendors are selected and added to the cart.
- It should be verified on the 'My Cart' page that the selected product has been added correctly.



## Used Technologies
- Java
- TestNG
- Selenium
- Page Object Model
- Maven
- Log4j

## Author - [tugbaltun](https://github.com/tugbaltun)