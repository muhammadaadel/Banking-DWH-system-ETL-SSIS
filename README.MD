# Banking-DWH-system-ETL-SSIS

## Introduction

The goal of this project is to design a Data Warehouse for a bank to support Bi reporting and analytics.

## Architecture 
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/bca10b8e-3617-43c1-8b4f-fc2321369e0b" />

## OLTP Schema Diagram (source)
<img width="903" height="600" alt="Image" src="https://github.com/user-attachments/assets/622c8f02-c016-4cf9-9d87-bdd0c28f4ca2" />

## OLAP Schema Diagram (destination) 
- We designed a galaxy schema, that serves our use case
<img width="1461" height="823" alt="Image" src="https://github.com/user-attachments/assets/0e1f6b74-3869-420c-9001-b425b63197f8" />

## Mapping
- ATM_transactions_fact
<img width="965" height="238" alt="Image" src="https://github.com/user-attachments/assets/40ab0809-91cc-4256-9bab-6dcf87361d13" />

- Loans_fact
<img width="964" height="261" alt="Image" src="https://github.com/user-attachments/assets/4b39f595-88ca-412a-a410-2f59f83a6c93" />

- Account_Dim
<img width="850" height="263" alt="Image" src="https://github.com/user-attachments/assets/0cce8969-8e1b-40b0-91ed-2420a812db16" />

- ATM_Dim
<img width="833" height="236" alt="Image" src="https://github.com/user-attachments/assets/d9060b11-fe84-408c-a987-7177a8826ad3" />

- Branch_Dim
<img width="634" height="217" alt="Image" src="https://github.com/user-attachments/assets/c3f41495-1966-417e-a85f-211aa81c7ed3" />

- Card_Dim
<img width="842" height="283" alt="Image" src="https://github.com/user-attachments/assets/bc91ebd5-5ef8-4633-993a-dd3ffab9422f" />

- Customer_Dim
<img width="655" height="344" alt="Image" src="https://github.com/user-attachments/assets/92febcd3-49e5-47c6-aeb0-c0858005b9ec" />

- Department_Dim
<img width="847" height="220" alt="Image" src="https://github.com/user-attachments/assets/04ea6c2a-d0eb-4b96-a912-45da661c11d6" />

- Employee_Dim
<img width="889" height="325" alt="Image" src="https://github.com/user-attachments/assets/04b6ce80-8db3-4a8d-b74f-93c685214b9c" />

## Insights
- Here are some insights we derived from our data
<img src="PowerBI/1.png">
<img src="PowerBI/2.png">



## Technology Used
- SQL
- SSMS
- SSIS
- SSAS
- Excel
- Power Bi

