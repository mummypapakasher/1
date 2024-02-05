Q1. Give the load type and the load weight for Austin's waste collection. 
'''sql 
SELECT load_time, load_weight, load_type  
FROM `bigquery-public-data.austin_waste.waste_and_diversion` 
ORDER BY load_weight desc;
'''
![image](https://github.com/mummypapakasher/1/assets/159010880/d623562e-02a9-413f-8406-62c796d82db6)
