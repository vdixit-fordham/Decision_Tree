# Decision_Tree
This project explains the decision tree concept and Entropy. 

Decision Tree <br />
Table 1 below contains a small training set. Each line includes an individual's educa-tion, occupation choice, years of experience, and an indication of salary. Your task is
to create a complete decision tree including the number of low's & high's , entropy at each step and the information gain for each feature examined at each node in the tree.<br />
<br />
Instance, Education Level, Career, Years of Experience, Salary <br />
1,High School,Management,Less than 3,Low <br />
2 ,High School,Management,3 to 10,Low <br />
3,College,Management,Less than 3,High <br />
4,College,Service,More than 10,Low <br />
5,High School,Service,3 to 10,Low <br />
6,College,Service,3 to 10,High <br />
7,College,Management,More than 10,High <br />
8,College,Service,Less than 3,Low <br />
9,High School,Management,More than 10,High <br />
10,High School,Service,More than 10,Low <br />
<br />
Now, Prune the tree we obtained using the validation data given in Table 2. <br />
Instance, Education Level, Career, Years of Experience, Salary <br />
1,High School,Management,More than 10,High <br />
2,College,Management,Less than 3,Low <br />
3,College,Service,3 to 10,Low <br />
