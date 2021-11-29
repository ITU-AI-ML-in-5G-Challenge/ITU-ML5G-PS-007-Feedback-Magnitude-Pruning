# ITU-ML5G-PS-007-The-AMC-Team
The A(MC) Team submission to AI for Good: Lightning-Fast Modulation Classification with Hardware-Efficient Neural Networks

## About
This repo is for th submission to **ITU-ML5G-PS-007: Lightning-Fast Modulation Classification with Hardware-Efficient Neural Networks**.
The goal of the competition was to created the fastest* and most efficient* deep learning architecture that could achieve a minimum of 56% classificaiton accuracy on the  DeepSig RadioML 2018 dataset.

In this competition, we highlight pruning methods for network compression. We use Iterative Magnitude Pruning (IMP) and develop a variant called Feedback Magnitude Pruning (FMP). FMP, analgous to a decaying learning rate scheduler, reduces the pruning parameter when the network is unable to achieve a specified criterion (i.e. accuracy). We demonstrate  iterative pruning methods are very effective for network compression, and how adding feedback to the algorithm enables much greater compression and an improved normalized inference. Our final compression ratios and normalized inference costs are in the table below.

|| Baseline | Iterative Magnitude Pruning  | Feedback Magnitude Pruning |
|-|-------------| ------------- | ------------- |
|Compression Ratio| 1  | 9.3  | 813  |
|Inference Cost| 1  | 0.0424  | 0.0268  |



*Speed and efficiency metrics are defined at: https://challenge.aiforgood.itu.int/match/matchitem/34


## Run the code



### Notes
- The code used in this repo stems from the provided repo: https://github.com/Xilinx/brevitas-radioml-challenge-21
- Please find ITU_form.txt to see further details regarding performance, instructions to run the code, etc.
