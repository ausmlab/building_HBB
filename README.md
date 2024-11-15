## Original README.md
Plaese refer to [README_mmdet.md](https://github.com/ausmlab/building_HBB/blob/main/README_mmdet.md).

## Installation

Please refer to [Installation](https://mmdetection.readthedocs.io/en/latest/get_started.html) for installation instructions.

## Preparing Data
Please make sure that data files sturcture should be the following.
```
[DATA_ROOT]
    |--annotations
    | 	 |--instances_tran.json
    |	 |--instances_val.json
    |	 |--instances_test.json
    |--train
    |    |--XXX.png
    |--val
    |    |--YYY.png
    |--test
         |--ZZZ.png
```

## Training/Testing
There are config files that I used in the './configs/building'
You have to change 'DATA_ROOT'to your own path
You can use each file to train and test the model.
Please refer to detailed option at [get_started.md](https://github.com/ausmlab/building_HBB/blob/main/docs/en/get_started.md)
