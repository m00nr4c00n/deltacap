# deltacap
Track income and expenses with python + sqlite3

Trying to learn python and database insertions and extractions for various reasons.
Keeping track of expences and income will have to serve as test data, cause why not. 
I want to learn while at the same time makeing something of actual use.
I have a hunch of what I'm doing, I can only pray it is somewhat correct. 
I'm Selftaught and a certified moron. GL HF

This REDME.md is retarded (or is it me?) stop auto formating my shit!


TODO - Alfa 0.0.1: 

Storage database
-> sqlite3 
"Module" for:

(input)
store reciept -> "date" "Store name" "total price" 
-> add individual products, too much work right now lets settle for the price total in the begining

monthly bill -> "date" "company name" "total price" 
-> add name of company who sent the bill, price of bill and date.

random costs -> "date" "name of cost" "total price" 
-> add name of random cost, total price and date.

month income -> "date" "income source" "amount" 
-> add the incomes generated for the month, where it came from and date.

(output)
display total costs and income 
-> query database for grand total of costs and income and difference between them, + or -

display selections total (ie only costs, only income, between date x to date y total, ect.) 
-> query database with specific names, dates, inflow or outflow, ie "all income from /employer/" 
"total bills from /Ecorp/" "total amount spent at /store name/ between date1 and date2" 
