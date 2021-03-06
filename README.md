# Flexibility-and-welfare
Codes for "Evidence of flexibility and its economic implications on the electricity day-ahead market"

**************************************************************************************
Use codes in file *R preparing data*
**************************************************************************************
1. Download 20189 files [here](https://mega.nz/folder/CZETEI7J#p7oF76dloGqM0qLkbOCd_w) 
2. Run R until end of raw data - line 427  
3. Generate data graphs, lines 430-650
4. Generate panel data for python package pyblp - from start to stop1, lines 653-1262
5. Use file plants.xlsx from file 20189 
6. Download 20190 files [here](https://mega.nz/folder/iBVn1I5J#bxLOJ4xPbtqAsEw83eIsgA)  
7. Generate panel data for python pyblp - from start to stop2, lines 1300-1872 (this code switches between files 20189 and 20190, so add your paths, searching for #add your directory)
8. Generate summary tables and ramping requirements (shown in paper): run lines 1875-1926

**************************************************************************************
Go codes *Python BLP* (or use the files that are already solved, directly in R)
*************************************************************************************
9. Use panel data files generated previously from R: "20189_a.cvs" and "20190_b.cvs" 
10. Running this code generates files per block of hour (off-peak, peak1, peak2 for each period), or the files in the directory can be used directly in R
11. Use the file rest_demand_response.xlsx (last line of code) to generate graphs of results


**************************************************************************************
Return to *R preparing data* to generate graphs of results
**************************************************************************************
12. Download py file [here](https://mega.nz/folder/ORdhHYiZ#QJM1NRunkwZTc2IBExzc-A) (especially rest_demand_response.xlsx)
13. To generate pass through graphs, run R lines 1931-2169 (this code creates plots, so add your paths, searching for #add your directory)
14. To generate welfare graph, run R lines 2180-2605 (this code creates plots, so add your paths, searching for #add your directory)
15. To generate CO2 emissions' graph, run R lines 2608-2792 (this code creates plots, so add your paths, searching for #add your directory)



***
*The file add_raw contains the matched data of stations used to obtain hourly temperatures [here](https://mega.nz/folder/eNURDIbb#9C0H39zSt4d4cbYtII3pLg)  
***
