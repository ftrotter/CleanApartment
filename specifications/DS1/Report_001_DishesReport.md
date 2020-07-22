---
client: Pfizer
project_key: project_key_here
contract_due_date: 2020-08-18
contract_signed_date: 2020-07-01
data_spec_name: LaundryProject
---
## Report 1: 
### Business Questions
This report shows how many different types of dishes in the kitchen. Using this we can estimate the time it would take to do dishes.

### Source Data
* VRDC Part C Data
* VRDC Part B Insitutional Outpatient
* VRDC Part B Carrier
* NPPES org data

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
