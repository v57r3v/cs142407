java c
DATA 201 - Assignment 4 
Total   marks: 20 
Due date: 11:59 p.m., Thursday, September 26, 2024.
Submit code and outputs in a single Jupyter notebook file. Do not expect the marker to rerun your code in order to get the outputs. 
Your task   is to develop   a   machine   learning   model to   predict the   market value of   houses   in   a   European city,   using data   (file data.csv) on various   characteristics   of   each   property.
The data description   is   provided   below.
id:   a   unique   identifier for each   house
zipcode: each   house   is associated with a   zipcode that   corresponds to   its   location
lot-len: the   plot length   in meters where the   house   is   built
lot-width: the   plot width in meters where the   house   is   built
lot-area: the total   plotarea on which the   house   is   built
house-area: the   house's   living area   measured   in square   meters
garden-size: the garden's size   measured   in square   meters
balcony: the total   number of   balconies   in the   housex-coor: the x-coordinate   representing the   house's   locationy-coor: they-coordinate   representing the   house's   locationbuildyear: the year   in which the   house was   built
bathrooms: the total   number of   bathrooms   in the   house
value: the   market value of the   house   (in   Euros)
Requirements: 
●         Use   root   mean square error   (RMSE) as the   evaluation   metric.   [2 marks]
●         Load the dataset, determine the target column,   remove   irrelevant   variables   (if   any),   and   use function   train_test_split   with   random_state=1   to split the data   into two   sets: atraining set   (80%) and a   test   set   (20%).   [3 marks代 写DATA 201 – Assignment 4Python
代做程序编程语言]
●         Explore the training set to gain   insights.   [2 marks]
●       Select   one   machine   learning   model,   train   it,   optimise   it   (e.g.,   add   pre-processing
transformers,   perform   hyper-parameter tuning, etc.), and estimate the   performance of   the   model.   [9 marks]
●       Test the   final   model   on   the   test   set   and   report   the   RMSE   and   at   least   two   other
evaluation   metrics   (e.g.,   mean   absolute   percentage error   (MAPE),   R2-score, etc.).   [3 marks]
●         Include a discussion at the   end   of your   notebook   (about   what   you   have   learned,   difficulties, what   has worked   and   not worked, future   directions, etc.).   [1 mark]
Notes:
-             Write your name and student ID at the   beginning   of your   notebook.   After   completing   your work,   use   menu   item Kernel => Restart  Run All in Jupyter, then   submit your notebook file.
-             You   can   use   any   public   Python   package.
-             The   requirements above   have   no order that   you   have   to   follow.
-             Use your   own   assumptions   and judgement   if you   are   unsure   about   any   information   in   the dataset.   However,   remember to   mention   it   in the discussion.
-             Try to write functions for all   data transformations   you   apply,   try   feature   engineering
(e.g., creating   new features),   and try to automate all the   steps   as   much   as   possible   (e.g.,   using   pipeline and   data transformers,   etc.). You   may   have bonus marks for this; however, your total   mark will   not exceed 20.







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
