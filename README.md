# Excel-automation-for-billing
Practice using functions to automate billing for an imaginary company.

For this automation I used functions such as CONCATENATE, VLOOKUP, IFERROR, SUMIF. For example: "=CONCATENATE(IFERROR(VLOOKUP(A21,clientes,2,FALSE), "No Existe"), " ",(IFERROR(VLOOKUP(A21,clientes,3,FALSE), "No Existe")))" 

I also added some rules and conditional formatting to make the bill look clearer and easy to read, as well as the name manager tool to write functions that had specific table arrays.
