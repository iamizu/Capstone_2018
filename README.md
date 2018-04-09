# PREDICTING MEDICARE COST

## Repository Contents

   * datasets
        
      * A_new10.csv
        
      * A_neww3.csv
        
      * A_neww4.csv
        
      * A_train3.csv
        
      * children_in_poverty.csv
        
      * ddf.csv
        
      * df.csv
        
      * df_x.csv
        
      * dff_2.csv
        
      * dfff.csv
        
      * dfof.csv
        
      * Education.xls
        
      * median-household.csv
        
      * medicare-bene-state.csv
        
      * PopulationEstimates.xls
        
      * PovertyEstimates.xls
        
      * poverty-rate-state.csv
        
      * smoking-State.csv
        
      * st2.csv
        
      * st3.csv
        
      * trainX.csv
        
      * Medicare Hospital Spending per Patient - Hospital.csv

      * Medicare Hospital Spending by Claim.csv
        
      * Medicare_hospital_spending_per_patient__Medicare_Spending_per_Beneficiary____Additional_Decimal_Places.csv
        
      * Structural-Measures-Hospital.csv
        
   * codes
       
      * Capstone-data-collecting-and-cleaning.ipynb
       
      * Capstone-exploratory-data-analysis-and-Modeling.ipynb
       
         
         
    * Datasets
   
         Initial datasets were gotten from Medicare.gov, datausa.oi, healthdata.gov and found in the datasets directory.
         
         * hospi-group: Is concerned with inpatient prospective payment system provider sumarry for the top diagnosis related groups, st2 datset was generated from it. 
            
         * Medicare_Hospital_Spending_by_Claim: has to do with the periods, claim type and spending averages in relative to them, st3dataset was generated from it.
            
         * Structural_Measures_-_Hospital: deals with hospitals and the availability of structural measures at each hospital, A_newdataset was generated from it.
            
         * Medicare_Hospital_Spending_Per_Patient_-_Hospital: deals with hospital spending per patient which measures wether medicare spends more or about the same per medicare patient treatment, df_Anew dataset was generated and merged with df_Anew1 generated from    Medicare_hospital_spending_per_patient__Medicare_Spending_per_Beneficiary____Additional_Decimal_Places to a new dataset A_train3.
            
         * Generated datasets used for model fitting and testing are found in the same directory named datasets and datasets used for EDA   are st2, st3, df4 and df_xx which was generated from df_x dataset.
        
        
        * Code
             * Project code is broken into two jupyter notebooks that can be found in the code directory. The dataset used exist in the datasets directory and do not need to be regenerated.
             
             * Capstone-data-collecting-and-cleaning.ipynb
             
             * Capstone-exploratory-data-analysis-and-Modeling.ipynb
             
             
    * Deliverables
         
         The deliverables contains the technical report and the presentation slide
              
        * Capstone-techinical_writting.ipynb
