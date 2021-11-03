TODO: Upload code and notebook

This folder contains the code for:
- preprocessing the "LUNA16" dataset where each instance of the dataset is a CT scan of the subject's lung. Each CT scan is labeled with candidate nodules, where they can either be a "real" nodule or a "fake" one.
- training a model that consumes the selected nodules one by one and classify them based on the probability that the model thinks the nodule is benign (p<0.5) or malignant (p>= 0.5)
- some visualization tools for the CT scans

