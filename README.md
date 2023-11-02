# Brain-Tumor-Classification
A brain tumor is an abnormal mass or growth of cells in the brain, which can disrupt normal brain function. These tumors can be categorized into primary brain tumors and metastatic brain tumors. Three specific types of primary brain tumors are,

1. Pituitary Tumor:
   - A pituitary tumor is a growth that forms in the pituitary gland, a small, pea-sized gland located at the base of the brain. The pituitary gland plays a crucial role in regulating various hormones that control many bodily functions. Pituitary tumors can be benign (non-cancerous) or, less commonly, malignant (cancerous). Depending on their size and location, they can affect hormone production and cause a range of symptoms, including hormonal imbalances, vision problems, and headaches.

2. Meningioma:
   - A meningioma is a type of primary brain tumor that arises from the meninges, which are the protective layers of tissue that surround the brain and spinal cord. These tumors are usually benign, but they can become quite large and press against the brain, causing symptoms. Meningiomas are generally slow-growing and may not always require immediate treatment. Symptoms can include headaches, seizures, changes in vision, and neurological deficits, depending on the tumor's location and size.

3. Glioma:
   - Gliomas are primary brain tumors that develop from glial cells, which are supportive cells in the brain that surround and nourish nerve cells. Gliomas can be either benign or malignant. The most aggressive type of glioma is glioblastoma multiforme. Gliomas are categorized based on the type of glial cell they originate from, such as astrocytomas, oligodendrogliomas, and ependymomas. Symptoms of gliomas can vary depending on the specific type and location of the tumor but may include headaches, seizures, cognitive changes, and neurological deficits.

<div align="center">
  <img src="https://github.com/costpetrides/Brain-Tumor-Classification/raw/main/readmePic.png" style="max-width:70%;">
</div>

# Model_1 and Model_2
You can find  model_1 and model_2: 
   - [BrainTumor_1.h5](https://github.com/costpetrides/Brain-Tumor-Classification/blob/main/BrainTumor_1.h5) - model_1
   - [BrainTumor_2.h5](https://github.com/costpetrides/Brain-Tumor-Classification/blob/main/BrainTumor_2.h5) - model_2

Warning :)
   If you want to run the entire model from scratch, the first model takes approximately 6 'Friends' episodes to be trained, while the second model takes approximately 8 'Friends' episodes to be trained! 

Feel free run the entire code from scratch and adjust the hyperparameters so can be fit to  your dataset!   

# Differnces between Model_1 and Model_2

1. Model Architecture:

   - "Model 1" uses a specific architecture with multiple convolutional layers and max-pooling layers, along with fully connected layers.
   - "Model 2" also uses convolutional layers, max-pooling layers, and fully connected layers, but with different layer configurations and filter sizes.

2. Model Compilation:

   - "Model 1" is compiled with an Adam optimizer with specific learning rates and beta values.
   - "Model 2" is compiled with an Adam optimizer, but with different learning rates and beta values.

3. Data Augmentation and Preprocessing:

   - "Model 1" applies data augmentation to the training data, including rotation, brightness adjustment, shifting, shear, and flipping.
   - "Model 2" applies a different set of data augmentation techniques to the training data, including rotation, brightness adjustment, shifting, shear, and flipping.

4. Data Loading:

   - "Model 1" loads training and test data using flow_from_directory with specific settings.
   - "Model 2" also loads training and test data using flow_from_directory with similar settings, including a constant seed for reproducibility.

5.Training:

   - Both "Model 1" and "Model 2" are trained for 40 epochs with a specific number of steps per epoch and validation steps.
   - They use different training data generators (train_generator and test_generator), which have different data augmentation settings.


