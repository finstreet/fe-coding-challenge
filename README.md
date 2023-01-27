# Finstreet Burger Challenge

## Task
We are working at a burger place and have to create a UI for our customers to order their burgers. The burger place offers three different burgers with the following prices:

- hamburger --> 5.0
- cheesseburger --> 6.0
- chilli cheeseburger --> 8.0

which all come in three different sizes that modify the price by a factor:

- small (s) --> * 0.7
- medium (m) --> * 1.0 
- large (l) --> * 1.3

The customer wants to add multiple burgers to his order and select a different size for each burger. Since the customer does not want to rely on his own math skills we should provide him with the display to see all burgers he ordered with the actual price of the burger.

To stay competitive with other burger restaurants we offer several ways to our customer to save money. There are different promotion codes that will offer two specific burgers to the price of one burger to the customer. Additionally, we want to offer the customer discount codes which deduct a percentage amount of the whole order price. Our manager wants the customer to add exactly one promotion code and one discount code to his order. The checkout display should show the price reduction from the promotion and discount code. 

After confirming the order we want to redirect the customer to a success page and show him that his order was successful, and he will receive his order soon.

## Libraries
We have some libraries that we are using in most of our finstreet projects and would like to use them in this project as well:

### ChakraUI
If you already have experience with using ChakraUI feel free to use it here as well, but you can also use the default html components to not waste too much time on learning ChakraUI. 

### react-hook-form / react-final-form
You can choose one of the two form libraries. Even though you might not have any experience with it, you should get up to speed quite fast since both of these libraries are easy to use.

### zod
There are several ways to add validations to your form. Zod is the one that integrates best with TypeScript, but you can use any other library or write your custom validations also.

## UI
![burger challenge ui](./ui.svg)

The UI should roughly look like the image above as a guideline. You can freely decide how to arrange the input fields inside the order part. The order summary should display all ordered burgers with their size and price. Below we want to show the customer how much he saves with the promotion code and how much is deducted with his discount code. Clicking on the checkout button at the bottom should display an alert to the customer that his order was successful and the amount he paid.

## Advanced

### TypeScript
We are using TypeScript in all of our projects and want to make use of it as much as possible. It is fine to use `any` in this coding challenge, but you can show off your TypeScript skills by using types throughout the application and having type safety where possible

### Downshift
ChakraUI does not style the options of a `Select` and uses the default browser implementation. You can improve this by using a library like downshift to build a custom select component which still fulfills all accessibility criteria. 





