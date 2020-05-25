This Drupal 7 Commerce module defines a block for customers to get a shipping quote for their cart based on country.

It works by creating a simple form with a country select list. The list of countries is copied from the address field on shipping customer profiles. 

When the customer selects a country, the form loads the shipping quotes via ajax. 

To set up:

1) Visit /admin/modules and turn on module. 
2) Visit /admin/structure/block. Configure the block as normal ie region and visabilty. Check the shipping checkbox under "Items to estimate through this form".
3) Add something to your cart and test it out.

This module uses a lot of code from https://www.drupal.org/project/commerce_cart_estimate. So big thank you to that developer - Ryan Szrama (rszrama)   ! 
