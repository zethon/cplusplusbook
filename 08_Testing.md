## 8.0 What is a Unit Test

Programs are made up of many smaller functions. For example consider a cash register program. In order to calculate the sales tax of a transaction, the program must first add up the prices of all the items to come up with the *total before tax*. Hence the program can be broken into steps:


* define a variable named `subtotal` which stores the total price of all the items being purchased (see **loops** to understand how this would be done)
* define a vairable named `tax` which equals `subtotal` * `tax_rate` (we will assume `tax_rate` is given to us)
* define a variable named `total` which equals `subtoal` + `tax`


