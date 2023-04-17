# TrendyolUIAutomation
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

7)	Add Items to basket and verify numbers are presented
-	Go to https://www.trendyol.com/
-	Hover the Mouse on the Login button 
-	Click on login button
-	Type “mertodtu1234@gmail.com” and “Merdomerdo1994” on username and password respectively.
-	Hover the Mouse on “AYAKKABI & ÇANTA” and click “Spor Ayakkabı” under “Erkek Ayakkabı” coloumn
-	Click on the item named “adidas Argo Trek - Siyah Erkek Outdoor Ayakkabı GB2916” 
-	Click “46” as a size
-	Click “Sepete Ekle” button
-	Verify that “1” appeared next to “Sepetim”
-	Click on “Trendyol” logo in order to navigate to main page
-	Hover the Mouse on “ELEKTRONİK” and click “Cep Telefonu” under “Telefon” coloumn
-	Click on the item named “Apple iPhone 11 128 GB Beyaz Cep Telefonu Aksesuarsız Kutu (Apple Türkiye Garantili)” 
-	Click “Sepete Ekle” button
-	Verify that “2” appeared next to “Sepetim”
-	Click on “Sepetim” button
-	Remove all products listed on basket
-	Verify that no number is written next to “Sepetim”

8)	Brand Name appeared on the list
-	Go to https://www.trendyol.com/
-	Hover the Mouse on the Login button 
-	Click on login button
-	Type “mertodtu1234@gmail.com” and “Merdomerdo1994” on username and password respectively.
-	Click on “Under Armour” square button
-	Verify that every item listed on the page has a description that includes “Under Armour”
-	Verify that number of items listed is matched with number displayed on the page

9)	Add an item to Collection 
-	Go to https://www.trendyol.com/
-	Hover the Mouse on the Login button 
-	Click on login button
-	Type “mertodtu1234@gmail.com” and “Merdomerdo1994” on username and password respectively.
-	Hover the Mouse on “SÜPERMARKET” and click “Kedi Maması” under “Petshop” coloumn
-	Click on the item named “Cool Cat Yetişkin Tavuklu Kedi Maması 15kg COOLCATYETAKEMA” 
-	Click on the “Add to Collection” button
-	Click on “Yeni Koleksiyon Oluştur” button
-	Type “Evcil Hayvan Ürünleri” 
-	Click on “Create a Collection” button
-	Verify that “ÜRÜN KOLEKSİYONA EKLENDİ” is written on the pop-up
-	Click on close button
-	Click on Favorilerim button
-	Click on “Koleksiyonlarım” button
-	Verify that “Evcil Hayvan Ürünleri” is listed

10)	Remove the Collection 
-	Go to https://www.trendyol.com/
-	Hover the Mouse on the Login button 
-	Click on login button
-	Type “mertodtu1234@gmail.com” and “Merdomerdo1994” on username and password respectively.
-	Click on Favorilerim button
-	Click on “Koleksiyonlarım” button
-	Click on “3 dots” button next to “evcil hayvan” collection 
-	Click on “Koleksiyonu sil” button
-	Verify that “evcil hayvan” collection is not listed 
