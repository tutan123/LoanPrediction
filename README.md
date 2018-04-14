# LoanPrediction
Pingan competition
## problem
- title(15818个unique）
- emp_title(70000 uniques)
- zip_code（我觉得可以删）

## none process（不需要处理）
1. member_id
2. loan_amnt
3. funded_amnt
4. funded_amnt_inv
5. int_rate
6. installment
7. 
8. dti
### date（日期型）
1. earliest_cr_line
2. issue_d

## dummies（多类别型）
1. home_ownership, 
2. verification_status, 
3. loan_status,
4. purpose


## binary（二值）
1. pymnt_plan,
2. term

## fill null（需要补充缺失值）
1. emp_length
2. revol_util
3. annual_inc
4. total_acc
5. 

## map（特殊处理）
1. emp
2. sub_grade

## delete
1. inq_last_12m 
2. total_cu_tl
2. open_acc_6m','
3. open_il_12m',
4. 'open_il_24m','
5. open_il_6m','
6. total_bal_il','
7. open_rv_12m','
8. open_rv_24m','
9. max_bal_bc','
10. all_util','
11. inq_fi','
13. policy_code
14. emp_title
15. desc
16. title
17. zip_code
18. dti_joint
19. annual_inc_joint
20. varification_status_joint
21. il_uti
22. mths_since_last_record   
23. mths_since_last_major_derog    
24. grade