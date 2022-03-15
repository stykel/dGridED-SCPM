# dGridED-SCPM

<br>

Real-World Data Sets<br>
-------
The real dataset is located in the [Real Data Sets] folder, which contains the **Kunming POI.csv** dataset. (Number of features: 23, number of instances: 298851)
<br>

The data features of the **Kunming POI** is: { instance feature, instance id, x-coordinate, y-coordinate }
<br>

**Note that** availability is limited for the remaining two real datasets, which were used under licence for the current study, and so are not publicly available. However, if you need this data please contact us with your reasonable request.

<br>
Synthetic Data Sets<br>
-------

The synthetic datasets is located in the [Synthetic Data Sets] folder.

* **Dataset for clumpy experiments**<br>
  clumpy=1 ：[clumpy_1.data] <br>
  clumpy=2 ：[clumpy_2.data] <br>
  clumpy=3 ：[clumpy_3.data] <br>
  clumpy=4 ：[clumpy_4.data] <br>
  clumpy=5 ：[clumpy_5.data] <br>

* **Dataset for Number of Instances Experiments**<br>
  Num_ins=50,000  ：[instances_50000.data] <br>
  Num_ins=100,000 ：[instances_100000.data] <br>
  Num_ins=150,000 ：[instances_150000.data] <br>
  Num_ins=200,000 ：[instances_200000.data] <br>
  Num_ins=250,000 ：[instances_250000.data] <br>

* **Dataset for Number of Features Experiments**<br>
  Num_fea=10 ：[features_10.data] <br>
  Num_fea=20 ：[features_20.data] <br>
  Num_fea=30 ：[features_30.data] <br>
  Num_fea=40 ：[features_40.data] <br>
  Num_fea=50 ：[features_50.data] <br>

* **Dataset for Number of Core Co-location Experiments**<br>
  Num_coloc=10 ：[co_loc_10.data] <br>
  Num_coloc=15 ：[co_loc_15.data] <br>
  Num_coloc=20 ：[co_loc_20.data] <br>
  Num_coloc=25 ：[co_loc_25.data] <br>
  Num_coloc=30 ：[co_loc_30.data] <br>
  
The data features of all synthetic datasets are: { instance features, instance id, x-coordinate, y-coordinate}

**Note that** in the experiments on synthetic datasets, for each value of each variable (such as clumpy=1), we generat ten datasets with the same parameters and perform ten repeated experiments. The results in the paper are the average of these ten results. Since the total amount of all synthetic dataset files is too large, we only upload 1/10 of the files. Please contact us if you need all data files.
