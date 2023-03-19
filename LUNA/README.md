TODO: Upload code and notebook

This folder contains the code for:
- This project was completed under the guidance of the amazing book [Deep Learning with PyTorch]([Deep Learning with Pytorch](https://www.amazon.com/Deep-Learning-PyTorch-Eli-Stevens/dp/1617295264/ref=asc_df_1617295264/?tag=hyprod-20&linkCode=df0&hvadid=459709175715&hvpos=&hvnetw=g&hvrand=10076550352694943681&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9033151&hvtargid=pla-671088923695&psc=1)) (it is also available for free online)
- preprocessing the "LUNA16" dataset where each instance of the dataset is a CT scan of the subject's lung. Each CT scan is labeled with candidate nodules, where they can either be a "real" nodule or a "fake" one.
- training a model that consumes the selected nodules one by one and classify them based on the probability that the model thinks the nodule is benign (p<0.5) or malignant (p>= 0.5)
- some visualization tools for the CT scans

