# Working Flow

#0601
1. Generate many tables: all czone, top100 czone, top60 czone, top100 BC


#0531
1. Using imterpolate F1 to run the regressions: test whether the coefficients are close or not. 
2. Run the regressions and insert into draft. 


#0527
1. Try to map industrial code: naics6 with sic4(sic87dd). (file: 0526_crosswalk.do)
Using David Dorn C1 and C2 to crosswalk. 
However, it is a m:m merging task which might take few days to complete. (Pause to disaggregate #2) 
2. David Dorn F1 employment data (1988, 1991, 1999, 2007, 2011 by czone level) interpolate into annual one. 

#0526 
1. Read ADH(2016): Import competition and the great US employment sag of the 2000s. (how to build up F1 employment data)
2. Download county employment data from county business patterns. (1986-2020)
3. Apply F1 employment data (by czone by industry, only few year) with D1 import data (by czone by industry, nominal one from 1991-2014). 

#0525
1. Try to use 1990 SIC QCEW employment data to check whether match the ADH data "variable: d_tradeusch_pw". 
Using 10 counties include in czone 32000(Houston). Not match!
2. writing

#0524
1. writing



