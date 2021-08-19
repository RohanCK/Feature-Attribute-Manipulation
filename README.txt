PyTorch Implementation of Plain Autoencoder, VAE123 and VAE345. 
The notebook provided was executed in the Google Collab environment and the dataset 
was mounted onto google drive(along with the execution code) via the original CelebA link.

STEPS:
1. Load the given jupyter notebook into the Google collab envirnoment.

2. Upload the provided "DFC-VAE" folder to the session storage.

3. Run all the cells in the notebooks to view the corresponding outputs which have been 
documented in the report.  

4. You can follow the markdown cells to get to any specific task whether its training, 
plotting, debugging or testing.
 
5. You may tweak the hyper parameters(alphas, betas etc.) provided under the utils module to
view different outcomes, other than the ones mentioned in the project report.

6. The trained models are stored under the directory trained_models(which is also provided
for your reference).

For instance: you may choose to remove sunglasses(instead of adding) from a particular photo
by simply changing the line in the notebook cell corresponding to line 102 in the 
"visualize_facial_attribute_manipulation.py" file:
latent = latent_img + alpha * latent_attr ====> latent = latent_img - alpha * latent_attr

Project Members
----------------
Names 				UID
Mohan Srinidhi Acharya		905627884
Ranjana Vittal			605629219
Tanvi Bhandarkar		705525339
Rohan Chetan Kapoor		305525510

Gratitude
----------------
This project would not be possible without the mentorship of Prof. J. Kao and TAs of course ECE 247: Neural Networks and Deep Learning.
Reference: https://github.com/OmegaMadPenguin/Deep-Feature-Consistent-VAE.git
