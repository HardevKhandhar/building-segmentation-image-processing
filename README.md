## Image Processing

* Image processing is a method to perform some operations on an image, in order to get an enhanced image or to extract some useful information from it. It is a type of signal processing in which input is an image and output may be image or characteristics / features associated with that image.

## Image Segmentation

* Image Segmentation is a pixel level classification of an image. Road area or Building feature extraction can be considered as a segmentation or pixel-level classification problem.

* Neural Networks have already been used in various remote sensing tasks, like damage assessment of washed-away building from pre and post tsunami aerial images. Furthermore, researchers are using Deep Learning to solve the problems of interpretation and understanding of remote sensing data.

## Building Segmentation

* Building Segmentation from Aerial Imagery is a challenging task. Obstruction from nearby trees, shadows of adjacent buildings, varying texture and color of rooftops, varying shapes and dimensions of buildings are among other challenges that hinder present day models in segmenting sharp building boundaries.

* High-quality aerial imagery datasets facilitate comparisons of existing methods and lead to increased interest in aerial imagery applications in the machine learning and computer vision communities.

## Dataset

[Massachusetts Buildings Dataset](https://www.kaggle.com/balraj98/massachusetts-buildings-dataset)

* The Massachusetts Buildings Dataset consists of 151 aerial images of Boston area, with each of the images being 1500 × 1500 pixels for an area of 2.25 square kilometers. Hence, the entire dataset covers roughly 340 square kilometers.

* The data is split into a training set of 137 images, a test set of 10 images and a validation set of 4 images. The target maps were obtained by rasterizing building footprints obtained from the OpenStreetMap project. The data was restricted to regions with an average omission noise level of roughly 5% or less.

* The large amount of high quality building footprint data was possible to collect because the City of Boston contributed building footprints for the entire city to the OpenStreetMap project. The dataset covers mostly urban and suburban areas and buildings of all sizes, including individual houses and garages, are included in the labels.

* The datasets make use of imagery released by the state of Massachusetts. All imagery is rescaled to a resolution of 1 pixel per square meter. The target maps for the dataset were generated using data from the OpenStreetMap project. Target maps for the test and validation portions of the dataset were hand-corrected to make the evaluations more accurate.

## Acknowledgements

* This dataset is derived from [Volodymyr Mnih's](https://www.cs.toronto.edu/~vmnih/) original [Massachusetts Buildings Dataset](https://www.cs.toronto.edu/~vmnih/data/). Massachusetts Roads Dataset & Massachusetts Buildings dataset were introduced in Chapter 6 of his [PhD thesis](https://www.cs.toronto.edu/~vmnih/docs/Mnih_Volodymyr_PhD_Thesis.pdf).

## Final Thoughts

* Given enough training time on GPU, larger datasets can be used for training the network. This can highly improve the accuracy and allow leveraging such image / semantic segmentation techniques in production Enterprise GIS environments. Rapid advances in Image Understanding using Computer Vision techniques have brought us many state-of-the-art deep learning models across various benchmark datasets.

* Deep learning is a machine learning technique that teaches computers to do what comes naturally to humans: learn by example. It is getting lots of attention lately and for good reason. It’s achieving results that were not possible before. These models can achieve state-of-the-art accuracy, sometimes exceeding human-level performance.

---

Thank you!
