# PDD_analyses

1. running grouping tool on raw files

generateGroups --path="/home/collinjl/PDD_raw_files/" --phenotypefiles="299_icd9.csv+299.0_icd9.csv+299.1_icd9.csv+299.8_icd9.csv+299.9_icd9.csv+299.00_icd9.csv+299.01_icd9.csv+299.10_icd9.csv+299.11_icd9.csv+299.80_icd9.csv+299.81_icd9.csv+299.90_icd9.csv+299.91_icd9.csv" --groupfile="299_group.csv+299.0_group.csv+299.1_group.csv+299.8_group.csv+299.9_group.csv+299.00_group.csv+299.01_group.csv+299.10_group.csv+299.11_group.csv+299.80_group.csv+299.81_group.csv+299.90_group.csv+299.91_group.csv" --phenotypeout='PDD_icd9.csv" --groupout="PDD_group.csv"

1a. grouping tool outputted two extra cloumns before the id, Event_date, and icd9 columns so I manually deleted them.

