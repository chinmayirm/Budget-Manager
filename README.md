# BUDGET MANAGER

Since the classic method of writing down transactions can be time consuming and hectic, using a lightweight python-based application will help the user monitor their personal finance transactions in a much more efficient and quick manner.



## AIM
Basic python program to create a finance and budget manager to stimulate money management.



## INPUT
- Creating a log-in ID.
- Creating a database based on the following inputs.

  - Source of Revenue
    1. Income
    2. Side Hustles
    3. Additional
    
  - Expenditure
      1. Household Bills
        - Rent/Mortgage + Maintenance
        - Insurance – House , Car , Health
        - Bills – Phone , Internet , Water , Gas
        - Car – Fuel , Maintenance , Loan
        - Domestic Help
        - Additional
      2. Living  Costs
        - Groceries + eating out
        - Laundry
        - Clothes/shoes
        - Heath + toiletries
        - Medicines
        - Healthcare
        - Additional
      3. Bank
        - Loans
        - Credit card down payment
        - Additional
      4. Children & Pets
      5. Indulgents and Leisure Spending
  - Savings and goals
  
  


## OUTPUT
- Pie chart breakdown of Total Expenditure into Household Bills, Living Costs, Bank, Children & Pets and Leisure Spending.
- Clear analysis of areas that contributed to most of the expenditure.
- Percentage analysis of how close the user was in acheiving their saving goal of the month.




## MODULES USED
- MySQL: used in order to store the data in an organised manner in the form of a database and is connected to Python for the user to interact with.
- CustomTkinter by user:TomSchimansky and Tkinter : used to make the overall look more attractive and colourful. The personalised monthly report also uses different colours to mark the different areas of expenditure.
- matplotlib, pandas, NumPy: used to generate pie chart to analyze expenditure breakdown.
- Any new transaction made can be conveniently entered using the "Additional" column and it gets stored in the MySQL database. Calculations are carried out internally to present the final report
