# Bugs

Below are some Bug Report samples that I wrote while working on previous projects.

---------------------

**Description:**
A photo via Twitter should be displayed on the “Photo wall” page.

**Steps to reproduce:**
1.Go to https://juice-shop.herokuapp.com/#/search ;
2.Select “Photo wall” from the principal Menu.

**Expected results:**
The first photo from the page should be displayed.

**Actual results:**
The first photo is not displayed.


---------------------

**Description:**
The customer can login only with his account name, the password field doesn’t exist.

**Steps to reproduce:**
1.Go to https://www.globalsqa.com/angularJs-protractor/BankingProject/#/customer  ;
2.Select username “75675464 64564564“;
3.Click to “Login“ button.

**Expected results:**
The customer should receive an error message with the text “Invalid username or password”.

**Actual results:**
TThe customer can login without any password.

**Test data:**
Username: 75675464 64564564



---------------------




**Description:**
The customer can place the order without having any product in the cart.

**Steps to reproduce:**
1.Go to https://www.demoblaze.com/index.html;
2.Navigate to cart - > Place Order;
3.Fill the Name and Credit card fields;
4.Press the “Purchase“ button.

**Expected results:**
The customer should receive an error message with the text “No products in the cart”/ The customer should not be able to navigate to the place order fields( an error with the text “No products in the cart” should be displayed).

**Actual results:**
The customer can place an order without having any product in the cart. No any error message is shown.


---------------------

**Description:**
Word “clouds” from “lang” parameter (RO - language) is not translated.

**Steps to reproduce:**
1.Go to https://api.openweathermap.org/data/2.5/weather?q=London&appid=548b07b01e5be002c64cf1a3e90e7454&lang=ro ;
2.Change the current API key with your API Key;
3.Select “ro: from “lang” parameter;
4.Press enter and see the results.

**Expected results:**
All results should be translated in Romanian language after selecting RO from “lang” parameter. 

**Actual results:**
Word “clouds” from weather result is still in English and is not translated to Romanian language.

---------------------


**Description:**
The customer can place the order without having any product in the cart.

**Steps to reproduce:**
1.Go to https://www.demoblaze.com/index.html;
2.Navigate to cart - > Place Order;
3.Fill the Name and Credit card fields;
4.Press the “Purchase“ button.

**Expected results:**
The customer should receive an error message with the text “No products in the cart”/ The customer should not be able to navigate to the place order fields( an error with the text “No products in the cart” should be displayed).

**Actual results:**
The customer can place an order without having any product in the cart. No any error message is shown.


---------------------

**Description:**
Credit card, Month and Year fields from “place order“ allow letters.

**Steps to reproduce:**
1.Go to https://www.demoblaze.com/index.html ;
2.Add a product in your cart;
3.Navigate to cart - > Place Order;
4.Fill the Credit card, Month and Year fields with letters;
5.Press the “Purchase“ button.

**Expected results:**
The customer should receive an error message with the text “Invalid data. The field allows only numbers”.

**Actual results:**
The customer can purchase the product without receiving any error.

