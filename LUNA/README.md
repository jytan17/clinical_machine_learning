This folder contains the code for:
- preprocessing the "LUNA16" dataset where each instance of the dataset is a CT scan of a subject's lung.
- training a model that consumes a CT scan, segments the CT scans based on nodules that the model deemed "interesting"
- training a model that consumes the selected nodules one by one and classify them based on the probability that the model thinks the nodule is benign (<0.5) or malignant (>= 0.5)
- some visualization tools for the CT scans
