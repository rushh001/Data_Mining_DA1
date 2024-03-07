# Data_Mining_DA1
# Goto preview or code of Data_Mining_Code.ipynb to run in google colab
# In preview Click "open in colab" to Open the code in colab
# You Can Also Copy the code and run it in Colab.
# 

# Outputs:

For Naive Bayes Classifier:
Predicted COVID-19 Test outcome for additional entry 1: Positive
Predicted COVID-19 Test outcome for additional entry 2: Negative
Predicted COVID-19 Test outcome for additional entry 3: Positive
Predicted COVID-19 Test outcome for additional entry 4: Negative
Predicted COVID-19 Test outcome for additional entry 5: Positive
Predicted COVID-19 Test outcome for additional entry 6: Negative
Predicted COVID-19 Test outcome for additional entry 7: Positive
Predicted COVID-19 Test outcome for additional entry 8: Negative
Predicted COVID-19 Test outcome for additional entry 9: Negative
Predicted COVID-19 Test outcome for additional entry 10: Positive

For Apriori, Frequent pattern and Frequent Item sets

Frequent Itemsets:
    support                               itemsets
0       0.6                                (cough)
1       0.4                              (fatigue)
2       0.6                                (fever)
3       0.2                        (loss of smell)
4       0.2                        (loss of taste)
5       0.4                          (sore throat)
6       0.2                       (fatigue, cough)
7       0.2                         (fever, cough)
8       0.4                   (sore throat, cough)
9       0.4                       (fever, fatigue)
10      0.2                 (fever, loss of smell)
11      0.2                 (fever, loss of taste)
12      0.2         (loss of smell, loss of taste)
13      0.2                (fever, fatigue, cough)
14      0.2  (fever, loss of smell, loss of taste)

Association Rules:
                       antecedents                     consequents  \
0                    (sore throat)                         (cough)   
1                          (cough)                   (sore throat)   
2                          (fever)                       (fatigue)   
3                        (fatigue)                         (fever)   
4                          (fever)                 (loss of smell)   
5                  (loss of smell)                         (fever)   
6                          (fever)                 (loss of taste)   
7                  (loss of taste)                         (fever)   
8                  (loss of smell)                 (loss of taste)   
9                  (loss of taste)                 (loss of smell)   
10                  (fever, cough)                       (fatigue)   
11                (fatigue, cough)                         (fever)   
12                         (fever)                (fatigue, cough)   
13                       (fatigue)                  (fever, cough)   
14          (fever, loss of smell)                 (loss of taste)   
15          (fever, loss of taste)                 (loss of smell)   
16  (loss of smell, loss of taste)                         (fever)   
17                         (fever)  (loss of smell, loss of taste)   
18                 (loss of smell)          (fever, loss of taste)   
19                 (loss of taste)          (fever, loss of smell)   

    antecedent support  consequent support  support  confidence      lift  \
0                  0.4                 0.6      0.4    1.000000  1.666667   
1                  0.6                 0.4      0.4    0.666667  1.666667   
2                  0.6                 0.4      0.4    0.666667  1.666667   
3                  0.4                 0.6      0.4    1.000000  1.666667   
4                  0.6                 0.2      0.2    0.333333  1.666667   
5                  0.2                 0.6      0.2    1.000000  1.666667   
6                  0.6                 0.2      0.2    0.333333  1.666667   
7                  0.2                 0.6      0.2    1.000000  1.666667   
8                  0.2                 0.2      0.2    1.000000  5.000000   
9                  0.2                 0.2      0.2    1.000000  5.000000   
10                 0.2                 0.4      0.2    1.000000  2.500000   
11                 0.2                 0.6      0.2    1.000000  1.666667   
12                 0.6                 0.2      0.2    0.333333  1.666667   
13                 0.4                 0.2      0.2    0.500000  2.500000   
14                 0.2                 0.2      0.2    1.000000  5.000000   
15                 0.2                 0.2      0.2    1.000000  5.000000   
16                 0.2                 0.6      0.2    1.000000  1.666667   
17                 0.6                 0.2      0.2    0.333333  1.666667   
18                 0.2                 0.2      0.2    1.000000  5.000000   
19                 0.2                 0.2      0.2    1.000000  5.000000   

    leverage  conviction  zhangs_metric  
0       0.16         inf       0.666667  
1       0.16         1.8       1.000000  
2       0.16         1.8       1.000000  
3       0.16         inf       0.666667  
4       0.08         1.2       1.000000  
5       0.08         inf       0.500000  
6       0.08         1.2       1.000000  
7       0.08         inf       0.500000  
8       0.16         inf       1.000000  
9       0.16         inf       1.000000  
10      0.12         inf       0.750000  
11      0.08         inf       0.500000  
12      0.08         1.2       1.000000  
13      0.12         1.6       1.000000  
14      0.16         inf       1.000000  
15      0.16         inf       1.000000  
16      0.08         inf       0.500000  
17      0.08         1.2       1.000000  
18      0.16         inf       1.000000  
19      0.16         inf       1.000000  

Frequent Itemsets:
    support                               itemsets
0       0.6                                (cough)
1       0.4                              (fatigue)
2       0.6                                (fever)
3       0.2                        (loss of smell)
4       0.2                        (loss of taste)
5       0.4                          (sore throat)
6       0.2                       (fatigue, cough)
7       0.2                         (fever, cough)
8       0.4                   (sore throat, cough)
9       0.4                       (fever, fatigue)
10      0.2                 (fever, loss of smell)
11      0.2                 (fever, loss of taste)
12      0.2         (loss of smell, loss of taste)
13      0.2                (fever, fatigue, cough)




