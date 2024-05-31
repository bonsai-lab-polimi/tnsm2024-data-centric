# tnsm2024-data-centric
Dataset repository for the paper "Machine Learning for Failure Management in Microwave Networks: a Data-Centric Approach", IEEE Transactions on Network and Service Management, 2024

## Description

The dataset is composed of 1669 entries (rows) with labels (0, 1, 2, and 3) corresponding to the microwave hardware failure cause, and a total of 164 columns of features (i.e., alarm signals). Each observation (row) corresponds to a 15-minute observation window during which the occurrence of a hardware failure was recorded. Each feature is an integer between 0 and 900, representing the total number of seconds in which an alarm signal was active during the 15-minute measurement window.

The hardware failure types are encoded as follows:
- 0: Indoor Unit (IDU) failure, 515 observations
- 1: Outdoor Unit (ODU), 611 observations
- 2: Cable failure, 207 observations
- 3: Power failure: 336 observations

If you find this dataset useful for your research, please consider citing the following paper: https://ieeexplore.ieee.org/document/10543089 
Thank you very much!

