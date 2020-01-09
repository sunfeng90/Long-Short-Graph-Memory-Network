# Long-Short-Graph-Memory-Network
Long-Short Graph Memory Network for Skeleton-based Action Recognition（WACV2020）

Here we provide an implementation of the LSGM + GTSC model, 
and we provide a reduced version of the SUSY data set for everyone to test the model easily. 
If you want to run this model on the complete SYSU dataset,
you just need to make a few changes in process_sysu_initial.py (we already mentioned in the .py file)
Because the SYSU data set is small and our current model version algorithm is not stable enough,
it may take several more trainings to achieve the desired effect.

# Install
To run this demo, you should install these dependencies:
```
tensorflow 1.12.0
keras 2.2.4
python-lmdb 0.94
python 3.6.8
```

# Run Demo
```
python process_sysu_initial.py
python train.py
```
