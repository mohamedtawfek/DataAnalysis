![image](https://github.com/mohamedtawfek/DataAnalysis/assets/41310168/5ba3c14c-9ff3-4a46-a965-6547fc4146e2)# DataAnalysis
Data Analysis tasks

1-Python and SQL: Prepare a shell/python script and SQL analytical functions to read and validate the file data of “Configuration_File_Validation_Task_Data.xlsx” to get validate the data correctness
Sample issues to be validated:
- Duplicated Configuration Record with the same Tier_Amount_Start Found.
- Duplicated Configuration Record with the same Tier_Amount_end Found.
- Tier_Amount_Start less than or equal to the previous tier Tier_Amount_end.
- Tier_Amount_Start Greater than or Equal to the next tier Tier_Amount_Start.
- Tier_Amount_Start Equal the Tier_Amount_end where Tier_Percentage_Fee>0.
- The Commission is high (Tier_Min_commission>100EGP)
- Tier_Min_commission Amount Greater than Tier_Max_commission Amount.
- Tier_Percentage_Fee>0 or Tier_Fixed_Fee_Amount>0 but tier_max_commission=0
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2-Data Analytics Task using SQL: All Merchants have daily actions/events in the system to track their balance and record all actions done on their accounts.
The merchant is in a red zone when the balance is below the balance <500 EGP, and in a brown zone when his balance is between 500 and 1000. Else will be in a green zone when balance >1000
Use the attached data “Merchants_Actions _Task_Data.xlsx” to get the Merchants zone start time and end time across the whole sample data
