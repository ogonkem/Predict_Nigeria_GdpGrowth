### Question  
Use the Machine Learning  Workflow to process and  transform Nigeria’ s economic indicators data to  create a prediction model. This  model must use said indicators to predict GDP growth of Nigeria one year ahead with 75%  or greater  accuracy.  
### Data sources  
GDP (current $): https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?view=chart   <br>
Direct Link: http://api.worldbank.org/v2/en/indicator/NY.GDP.MKTP.CD?downloadformat=csv  <br>
 
GDP growth (annual %): https://data.worldbank.org/indicator/NY.GDP.MKTP.KD.ZG?view=chart   <br>
Direct Link: http://api.worldbank.org/v2/en/indicator/NY.GDP.MKTP.KD.ZG?downloadformat=csv  <br>
 
Broad Money (LCU): https://data.worldbank.org/indicator/FM.LBL.BMNY.CN?locations=NG&view=chart  <br> 
Direct Link: http://api.worldbank.org/v2/en/indicator/FM.LBL.BMNY.CN?downloadformat=csv   <br>
  
FDI net (BoP, $): https://data.worldbank.org/indicator/BN.KLT.DINV.CD?view=chart   <br>
Direct Link: http://api.worldbank.org/v2/en/indicator/BN.KLT.DINV.CD?downloadformat=csv   <br>
  
Real Interest Rate (%): https://data.worldbank.org/indicator/FR.INR.RINR?locations=NG&view=chart  <br> 
Direct Link: http://api.worldbank.org/v2/en/indicator/FR.INR.RINR?downloadformat=csv  <br> 
  
Inflation Rate (%): https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG?view=chart   <br>
Direct Link: http://api.worldbank.org/v2/en/indicator/FP.CPI.TOTL.ZG?downloadformat=csv   <br>
  
Economic Freedom Index - efi: https://www.fraserinstitute.org/economic-freedom/dataset?geozone=world&page=dataset&min-year=1970&max-year=2015&filter=1&date-type=range   <br>
Direct Link: https://www.fraserinstitute.org/api/economic-data?start_year=1970&end_year=2015&sub=true&indicator[]=area_1&indicator[]=area_2&indicator[]=area_3&indicator[]=area_4&indicator[]=area_5  <br> 
  
Portfolio Investment (BoP, $): https://data.worldbank.org/indicator/BN.KLT.PTXL.CD?locations=NG&view=chart  <br> 
Direct Link: http://api.worldbank.org/v2/en/indicator/BN.KLT.PTXL.CD?downloadformat=csv   <br>
  
Summary of federal government finances: https://cbn.gov.ng   <br>
Direct Link:https://www.cbn.gov.ng/out/2017/sd/ecopy%20of%202016%20statistical%20bulletin_public%20finance%20statistics_final.xlsx  <br> 
  
Exchange Rate (LCU per $): https://data.worldbank.org/indicator/PA.NUS.FCRF   <br>
Direct Link: http://api.worldbank.org/v2/en/indicator/PA.NUS.FCRF?downloadformat=csv   <br>

Political instabiltiy: https://landportal.org/  <br>

### Assumptions  
All the dependent variables are factors that influence the fluctuation of Gdp  

### Hypothesis  
This  model would use said indicators to predict GDP growth of Nigeria one year ahead with 75%  or greater  accuracy.  

### Result 
Due to the unavailability of enough trainable data the model predicted very low R Squared  
