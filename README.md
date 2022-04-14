# Excel-automation-for-billing
Practice using functions to automate billing for an imaginary company.

For this automation I used functions such as CONCATENATE, VLOOKUP, IFERROR, SUMIF. For example: "=CONCATENATE(IFERROR(VLOOKUP(A21,clientes,2,FALSE), "No Existe"), " ",(IFERROR(VLOOKUP(A21,clientes,3,FALSE), "No Existe")))" 

I also added some rules and conditional formatting to make the bill look clearer and easy to read, as well as the name manager tool to write functions that had specific table arrays.

In the "Final practice" file, I added a sheet with a report where I created some graphs, used functions MAX, MIN, AVERAGE, SUMIF. E.g. "=SUM(SUMIF(A6:A13,{"Mayo","Junio","Julio","Agosto"},B6:B13))". This to see some findings, results and visual representations of the numbers. 

In the last sheet "Tabla_dinamica", I did 2 pivot tables where I added some filters and did sums and average.
