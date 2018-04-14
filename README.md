# LoanPrediction
Pingan competition

## none process（不需要处理）
1. member_id
2. loan_amnt
3. funded_amnt
4. funded_amnt_inv
5. int_rate
4. installment
7. collection_recovery_fee
8. dti
9. total_pymnt
10. total_pymnt_inv
11. recoveries
12. revol_bal
13. total_rec_prncp
### date（日期型）
1. earliest_cr_line
15. issue_d

## dummies（多类别型）
1. home_ownership, 
2. verification_status, 
3. loan_status,
4. purpose


## binary（二值）
4. pymnt_plan,
4. term
4. application_type, 
4. initial_list_status

## fill null（需要补充缺失值）
1. emp_length
2. revol_util
3. annual_inc
4. total_acc
5. collections_12_mths_ex_med
6. tot_cur_bal
7. tot_coll_amt
8. total_rev_hi_lim
15. revol_util
15. pub_rec(补0就行了)
15. total_rec_prncp
15. total_rec_late_fee
15. total_rec_int
15. total_pymnt
15. total_pymnt_inv

## map（特殊处理）
1. sub_grade

## delete（删除）
1. inq_last_12m 
2. total_cu_tl
3. open_acc_6m','
4. open_il_12m',
5. 'open_il_24m','
6. open_il_6m','
7. total_bal_il','
8. open_rv_12m','
9. open_rv_24m','
10. max_bal_bc','
11. all_util','
12. inq_fi','
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
25. addr_state