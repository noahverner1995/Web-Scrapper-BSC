# Web-Scrapper-BSC
Here's a simple Python program that takes the current first Top 100 Wallets by BNB balance from BSCSCAN and filters them depending on their Txn Count value, for then exporting them as a dataframe in a csv file.

# Usefulness 
If you are new to web scrapping and Python, this project will give you a good idea of how the data from a website is called, filtered, and then exported as a csv file, all thanks to BeautifulSoup, Requests, and Pandas libraries.

# How to get started
By default, if you just download the project file and click it it will just create a csv file containing a list of the current first Top 100 Wallets by BNB balance filtered by a Txn Count value between 200 and 1000. If you want to set some different Txn Count values, right click on the project file and then left click on "Edit with (your prefered Python editor)..." then locate the `tester` function down below the last comment, and change the current logic parameters for your desired ones, then compile it again. 
