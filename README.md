# AV-Hackathon-Feb-2022

1.Used Concatenated features of ['gender','profession','age','followers']
2.Used categorical columns like ['gender', 'profession', 'age','user_id','followers','views'] as well as features created in step 1 and created statistical features like mean, std, min, max engagement scores based on these features
3.Encoded categorical features gender and profession(All other features were highly discrete which would lead to data sparsity)
4. Found best parameters after tuning using optuna package
5. Ran model with all the features and ran the model with the most important features alone to arrive at the final output
