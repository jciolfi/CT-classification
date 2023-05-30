# Brain CT Image Hemorrhage Segmentation

Please See "XN Final Paper.pdf" for the context, rationale, and findings of this project.

# Abstract

Our goal with this project is to train various classification models to determine whether a given brain CT scan contains evidence of any one of five types of hemorrhages, multiple different types of hemorrhages, or no hemorrhages. The provided data set has labeled images of CT scans which we can use to train and test our models. The scans are formatted such that a model will receive four image files per CT scan – each a different rendering type of the same image (different rendering types may show various hemorrhages more clearly). The model should then return whether the images show evidence of a hemorrhage (or multiple hemorrhages) or not. If there is evidence of a hemorrhage (or hemorrhages), it should return the type of hemorrhage it believes exists (or the types, if multiple).
