# CIND-820-Project Big Data Analytics Project

#Probelm
The main problem is that the sales team within Olist recieves more leads than it can contact with equal attention. The project will look at whether leads can be ranked using the information given when they arrive via origin, landing_page_id, first_contact_date
This was working the top of the ranked list captures a disproportiante share of conversions

# Data(4 Olist CSV Files)

olist_marketing_qualified_leads_dataset.csv - Marketing Funnel by Olist
olist_closed_deals_dataset.csv - Marketing Funnel by Olist
olist_order_items_dataset.csv - Brazilian E-Commerce Public Dataset by Olist
olist_orders_dataset.csv - Brazilian E-Commerce Public Dataset by Olist

Marketing Funnel by Olist: https://www.kaggle.com/datasets/olistbr/marketing-funnel-olist 
Brazilian E-Commerce Public Dataset by Olist: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce 

The license fr these are under CC BY-NC--SA 4.0

# Repo Structure

4 Olist CSV files - contains the 4 source CSV files
Notebook - contains the colab notebook with loading the files, integrating it, profiling and analysis
EDA - EDA report generated with YData Profiling

# How to run

1. Open the "Notebook" file, and load it into a google colab file with the 4 CSV files loaded in to the library
2. Select Run all


# Planned Approach: The planned approach is to join the leads file to the closed deals file using mql_id using a pandas left join, and do the analysi solely based off of teh leads with the first_contact_date of December 217 and onwards.  

# Notebook: CIND_820_Milestone_2_notebook_for_Section_3_and_EDA_report_work.ipynb
# EDA Report: eda_report-2.html
