# Flexibility-and-welfare
Codes for "Evidence of flexibility and its economic implications on the electricity day-ahead market"

**************************************************************************************
Using R codes preparing the data
**************************************************************************************
1. Download file 20189 from https:/mega.nz/folder/CZETEI7J#p7oF76dloGqM0qLkbOCd_w
2. Run R until end of raw data - line 427  
3. Generate data graphs lines 430-650
4. Generate panel data for python pypblp - start/stop1 lines 653-1262
5. Use file plants from file 20189 
6. Download file 20190 from https://mega.nz/folder/iBVn1I5J#bxLOJ4xPbtqAsEw83eIsgA
7. Generate panel data for python pypblp - start/stop2 lines 1300-1872 (this code switches between directories 20189 and 20190, so change to your paths, searching for #add your directory)
8. Generate Summary tables and ramping requirements shown in paper: run lines 1875-1926

**************************************************************************************
Go to python (or use the files that are already solved, directly in R)
*************************************************************************************
9. Use panel data file generated previously from R "20189_a.cvs" and "20190_b.cvs" 
10. Running this code generates files per block of hour (off-peak, peak1, peak2 for each period), or the files in the directory can be used directly in R
11. Get file rest_demand_response.xlsx (last line of code) to generate the following result graphs


**************************************************************************************
Return to R to generate result graphs
**************************************************************************************
12. Download file py from https://mega.nz/folder/ORdhHYiZ#QJM1NRunkwZTc2IBExzc-A (especially rest_demand_response.xlsx)
13. Pass through graphs, Run R lines 1931-2169 (this code creates plots, so add your paths, searching for #add your directory)
14. Welfare graph, run R lines 2180-2605 (this code creates plots, so add your paths, searching for #add your directory)
15. CO2 emissions' graph, run R lines 2608-2792 (this code creates plots, so add your paths, searching for #add your directory)



***
*File add_raw contains the data for daily temperatures (https://mega.nz/folder/eNURDIbb#9C0H39zSt4d4cbYtII3pLg)
***
