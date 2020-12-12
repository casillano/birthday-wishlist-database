# Amazon Wishlist Database for Birthdays (and other special occasions)
A useful web app to help you find the right gifts for your friends. Money is nice, but a JBL Flip 4 Waterproof Portable Bluetooth Speaker
would make such a better gift ;) . 

![wishlist gif](wishlist.gif)

# How to Use

This currently only works on the Canadian and US Amazon sites. The person's Amazon wishlist ID can be found in the url:

```
https://www.amazon.ca/hz/wishlist/ls/1H4NZDNEB37IN
```
In this wishlist url (which links to my personal wishlist), the wishlist ID corresponds to the 13 digits and letters at the 
end of the url. In this case, it's `1H4NZDNEB37IN`

The app communicates with a MySQL database. To set up your own database with this project, go to `src/main/webapp/WEB-INF/crud-servlet.xml`, and change the information on lines 39-41. The sql code used to create the schema for the database can be found under `sql\`.
