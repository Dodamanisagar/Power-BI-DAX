# Power-BI-DAX
1. Left Anti Merge = 
// This DAX formula returns all the records from the left table which doesnt have any matching records in right table
// EXCEPT() works only when both tables contains same number of columns
EXCEPT(Append_1,Append_2)
