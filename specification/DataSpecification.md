---
client: Pfizer
project_key: project_key_here
contract_due_date: 2020-08-18
contract_signed_date: 2020-07-01
---
# Client: Acme Cleaning Corp
Acme is a family owned cleaning company based in Houston, TX. 

# Project Use Case
This is a data specification for me to provide about how disorganized and cluttered my kitchen is

# Reports

## Report 1: 
### Business Questions
This report shows how many different types of dishes in the kitchen.

### Source Data
* VRDC Part C Data
* VRDC Part B Insitutional Outpatient
* VRDC Part B Carrier

### Codes: defined at the project level
### Refresh Rate: Quarterly
### Geography: All US Markets
### Methodolody
Count the plates first, then assume that there is a place setting for each plate.
Then count the glasses and assume that there are half as many coffee mugs. 

### Data Fields
#### Primary Key
1. Dish Type
2. Dish Color
#### Calculated Fields
3. Dish Count



