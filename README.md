# TrashNet
CNN-based image classifier for 3 waste categories: Cardboard, Glass, and Plastic

Dataset

TrashNet on Kaggle — ~1,200 training images, 162 test images, balanced classes.

What I did
Explored and cleaned the data
Fixed a stratified split issue with the validation set
Built a custom CNN with augmentation, dropout, and adaptive LR
Ran 3 experiments with different input resolutions
Results
Input Size	Test Accuracy
128 × 128	82.1%
384 × 512	80.9%
175 × 175	82.7% ✅

Best class: Cardboard (F1 = 0.95) — Glass vs Plastic was the hardest boundary.

Stack

TensorFlow · Keras · scikit-learn · NumPy · Matplotlib · Pillow

Run

Open TrashNet_final.ipynb in Google Colab and run all cells.
