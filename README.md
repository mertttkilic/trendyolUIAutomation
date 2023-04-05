# trendyolUIAutomation
Trendyol UI Automation with Playwright (Javascript)
Test Scenarios

1)	Invalid Login – Wrong username 
-	Go to https://www.trendyol.com/
-	Hover the Mouse on the Login button 
-	Click on login button
-	Type “mertodtu1234*@gmail.com” and “Merdomerdo1994” on username and password respectively.
-	Verify the error message is displayed 

2)	Invalid Login – Wrong password
-	Go to https://www.trendyol.com/
-	Hover the Mouse on the Login button 
-	Click on login button
-	Type “mertodtu1234@gmail.com” and “Merdomerdo1994*” on username and password respectively.
-	Verify the error message is displayed 

3)	Valid Login 
-	Go to https://www.trendyol.com/
-	Hover the Mouse on the Login button 
-	Click on login button
-	Type “mertodtu1234@gmail.com” and “Merdomerdo1994” on username and password respectively.
-	Verify that main page is successfully opened 
-	Hover the Mouse on “Hesabım” button and verify the e-mail address

4)	 Add product to Favorites
-	Go to https://www.trendyol.com/
-	Hover the Mouse on the Login button 
-	Click on login button
-	Type “mertodtu1234@gmail.com” and “Merdomerdo1994” on username and password respectively.
-	Hover the Mouse on “ANNE & ÇOCUK” and click “sweatshirt” under “Kız çocuk” coloumn
-	Add 2 products to the favorites
-	Click on “Favorilerim” button 
-	Verify that number of items listed is 2 and verify that names of the products added to favorites matches with the items listed in “Favorilerim” 

5)	Remove product from Favorites in Favorites tab
-	Go to https://www.trendyol.com/
-	Hover the Mouse on the Login button 
-	Click on login button
-	Type “mertodtu1234@gmail.com” and “Merdomerdo1994” on username and password respectively.
-	Hover the Mouse on “EV & MOBİLYA” and click “Yatak Odası” under “Ev Tekstili” coloumn
-	Add 2 products to the favorites
-	Click on “Favorilerim” button 
-	Verify that number of items listed is 4 (2 was already in favorites because of the last scenario) and verify that names of the products added to favorites matches with the items listed in “Favorilerim” 
-	Remove one product from favorites 
-	Verify that number of items listed on the favorites is 3. Verify that names are matching

6)	Remove product from Favorites in item page
-	Go to https://www.trendyol.com/
-	Hover the Mouse on the Login button 
-	Click on login button
-	Type “mertodtu1234@gmail.com” and “Merdomerdo1994” on username and password respectively.
-	Click on “Favorilerim” button 
-	Click on the item that are listed in Favorites tab.
-	Verify that the “heart button” placed next to the “Add to Basket” button is fullfilled.
-	Click on the “heart button”
-	Verify that “heart button” is empty.
-	Click on “Favorilerim” button 
-	Verify that the product is removed from favorites
