# Tech & Media Club Financial Position Summary Creation Package

## Executive Summary
The package creates an excel file including six sheets and three plots which provide insight into the club's financial position

## Data Requirement
The package requires five input matrices:  
1. The club balance csv file downloaded from Student Treasurer Portal's financial statement page
2. The finance code csv file downloaded from Student Treasurer Portal's financial statement page
3. The transaction csv file downloaded from Student Treasurer Portal's financial statement page
4. The staff roster csv file exported from a MySQL server or simply from an mannually maintained excel file
5. The finance code & associated team member csv file exported from a MySQL server or simply from an mannually maintained excel file

## Example Usage
***
	import tmc_finance
	
	obj = tmc_finance.Analyse('/Users/Chris/Documents/tmc_finance_bal.csv', '/Users/Chris/Documents/tmc_finance_txn.csv', '/Users/Chris/Documents/tmc_finance_fnc.csv', '/Users/Chris/Documents/tmc_finance_ros.csv', '/Users/Chris/Documents/tmc_finance_ros_fnc.csv', 'output/')
	obj.exec()
***
