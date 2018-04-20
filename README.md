# LoanPrediction
Pingan competition

## none process（不需要处理）
1. member_id
2. loan_amnt
3. funded_amnt
4. funded_amnt_inv
5. int_rate
6. installment
7. collection_recovery_fee
8. dti
9. total_pymnt
10. total_pymnt_inv
11. recoveries
12. revol_bal
13. total_rec_prncp
### date（日期型）
1. earliest_cr_line
2. issue_d

## dummies（多类别型）
1. home_ownership, 
2. verification_status, 
3. loan_status,
4. purpose


## binary（二值）
4. pymnt_plan,
5. term
6. application_type, 
7. initial_list_status

## fill null（需要补充缺失值）
1. emp_length
2. revol_util
3. annual_inc
4. total_acc
5. collections_12_mths_ex_med
26. tot_cur_bal
7. tot_coll_amt
8. total_rev_hi_lim
9. revol_util
10. pub_rec(补0就行了)
11. total_rec_prncp
12. total_rec_late_fee
13. total_rec_int
14. total_pymnt
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
26. policy_code
26. emp_title
26. desc
26. title
26. zip_code
26. dti_joint
26. annual_inc_joint
26. varification_status_joint
26. il_uti
26. mths_since_last_record   
26. mths_since_last_major_derog    
26. grade
26. addr_state
26. *payment_plan*
27. *application_type*
28. *sint_rate*