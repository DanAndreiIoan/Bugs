# Bugs

## Search is not working properly

**Priority and severity**

P2-High

**Description**

When I type letters in the search field they are not displayed.

**Steps to reproduce**

1. Go https://www.fieni.ro/
2. Scroll down to the bottom of the page
3. On the search field start type words

**Expected result**

The user should see the words he writes.

**Actual result**

The user does not see the words he writes.

-----------------------------------------------

## Different product on the page

**Priority and severity**

P3-Normal

**Description**

On the page for laptops there is a product that does not belong to this category ,this being a monitor.

***Steps to reproduce**
1. Go https://www.demoblaze.com//
2. Click on "Laptops" categories
3. Click "Next"

**Expected result**

Only laptops should be found on the laptop page.

**Actual result**

There is also a monitor on the page with laptops.

<img src="https://user-images.githubusercontent.com/68484432/147264090-98221960-6350-441e-bd70-771a6561fd9d.png" width="350" height="350"/>
--------------------------------------

## Button "Previous" does not work properly

**Priority and severity**

P3-Normal

**Description**

When I click on the "Previous" button it takes me to the home page, when it should direct me to the previous page.

**Steps to reproduce**

1. Go https://www.demoblaze.com//
2. Click on "Laptops" categories
3. Click "Next" 4. Click "Previous"

**Expected result**

When I press "Previous" it should direct me to the previous page.

**Actual result** 

When I press "Previous" it directs me to the home page of the site.

-----------------------------------


## Place order problem

**Priority and severity**

P2-High

**Description**

I can place an order even if I don't have any products in the cart.

**Steps to reproduce**
1. Go https://www.demoblaze.com//
2. Click on "Cart"
3. Click "Place Order"

**Expected result**

The application does not let you guard the order, displaying the message "There are no products in the cart".

**Actual result**

You can place the order even if there is no product in the cart.

-------------------------------

## Forgot Password form problem

**Priority and severity**

P2-Critical

**Description**

The fields for "Security Question", "New Password" and "Repeat New Password" cannot be accessed on the "forgot password" page.

**Steps to reproduce**
1. Go to https://www.juice-shop.herokuapp.com// 
2. Click on "Account"
3. Click "Login"
4. Click "Forgot Password"
5. Follow the steps

**Expected result**

The application should let you complete each filed.

**Actual result**

You can only fill the field for email, the other fields being blocked.


------------------------------

## Translation problem

**Priority and severity**

P4-Normal

**Description**

When I change the language to Romanian, not all words are translated.

**Steps to reproduce**
1. Start Postman
2. New Collenction  = "Weather"
3. Creat a "Request"
4. Insert Endpoint "api.openweathermap.org/data/2.5/weather?q=Londra&appid={API key}.
5. Insert Parameter "lang" with value "ro"

**Expected result**

All words must be in Romanian.

**Actual result**

The word "clouds" remains untranslated.

<img src="https://user-images.githubusercontent.com/68484432/147265998-48c80e6b-1891-465f-9674-d14bc8fae60b.png" width="350" height="350"/>
