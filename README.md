# Image-expression-recognition


**Contirbuiters: Mariia Padalko and Dror Rosentraub.**



Identifying emotions and expression of people, using images.
This dataset has 7 emotions.

A link to the original dataset - 
https://www.kaggle.com/deadskull7/fer2013/notebooks

**process -** 
1) Data Augmentation & Preprocessing
2) EDA and ML modeling
3) Neural Network modeling



**Data Augmentation & Preprocessing**

We created a more balanced dataset that for every emotion we have ~5000 images except for the 1-2 minority classes that have 1000-2000 images. 

In the fer_'preprocess_augment_balance.ipynb' you can find the code that we used to create the dataset.



**EDA and ML modeling

We visualized the data using non-linear dimensionality techniques, such as Isomap and t-SNE, and we tested various ML models.

In 'Exploration_ml.ipynb' and 'MP_fer_basic_ml.ipynb' you can find the  EDA and the ML models we used to test the data.



**Neural Network Modeling**
We built CNN models and we also tested VGG-16 on our data. We also saved the best model(h5) and saved it here. 

In 'mp_fer_nns.ipynb' you can find the NN models we used.
