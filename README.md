## Class
Write a class **KioskCalc** that has the following fruitsPriceList object.
this.fruitsPriceList = { "orange": 30, "mango": 15, "avocado": 40 }; 
and takes two parameters (fruit, quantity) when initialized i.e. 
**var** kioskCalc = **new** KioskCalc(“orange”, 2);
Thereafter, it allows one to calculate the total cost of the fruit by accessing the 
getTotalCost( ) method. 
kioskCalc.getTotalCost( )  // returns “2 orange for KES 60” 

## Object

Write a program to calculate purchases from a kiosk. For e.g. given the fruit name 
'orange' the program should fetch its price (30.00) and multiply with the quantity 
requested (2) and return total cost in this printed format (2 Oranges for KES 
60.00). 
calculateFruitCost(fruitName, quantity)
For example, calculateFruitCost('orange', 2) should return "2 Oranges for KES 
60.00"

##Promises on *Mkulima Farm*
Mkulima Platform
Mkulima is new Kenyan business-to-business (B2B) agro-startup focusing on connecting grocery vendors to rural farmers. This is through their online marketplace where farmers can trade vegetables and fruits with grocery vendors. To begin with, farmers have to register on the platform and login. Thereafter, they can upload their products with respective prices. On the other hand, grocery vendors can signup and login to the platform to place their bulk order requests. 

Create a class Mkulima that will keep a list of farms, grocery vendors and products. A single farm record should contain id, farm name, farmer, phone number and address. A single grocery vendor record should contain id, store name and phone number. A product should have id, name and price fields. 

Users of the system should be able to:
 addFarm - params: farmId, name, farmer, phone, address
 removeFarm - params: farmId
 updateFarm - params: farmId, name, farmer, phone, address
 getFarm - params: farmId - returns a farm object
 addProduct - params: productId, name, price
 removeProduct - params: productId
 updateProduct - params: productId, name, price
 getProduct - params: productId - returns a product object
 printProducts - No param, console logs a list of product items with their prices.
calculateOrderCost - params: productId, quantity

class Mkulima {
  
  constructor() {
    this.farms = [];
    this.products = [];
    this.orders = [];
  }

  // ...complete the rest 

}


