
Personal Budgeting Project (PBP)
object-oriented programming

identify yourself (user = class, Rudra = object)

Mechanism to enter data
	inputs
		date
		full cost
		who paid
		proportion user (one typing out data) should pay
		description of transaction
		category - (fsa expense maybe)
			some subcategory maybe
		
calculate metrics based on data
	inputted data
	Fixed (planned budgets for example, starting balance) <- user level, stored in a local file
	running historical data (month total, overall balance)


output report
	month table of transactions
	categories total tables (overall planned vs actual visual)
	start/end balance for month
	percent change in savings
	amount saved this month
	percent paycheck saved
	total account balance (fsa, student loan, investment etc.)
	



## steps:

run program 
opens UI
	form for each transaction
	






# TODO
finish [[Readme]]

- figure out which UIs or packages are mentioned in job applications
- select a data platform for our database (to SQL query from)

library(tidyverse)

df_new <- df_old %>%
	arrange(variable)

sort_df <- function()

df_new <- sort_df(df_old, variable)