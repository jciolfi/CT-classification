# Brain CT Image Hemorrhage Segmentation

Our goal with this project is to train various classification
models to determine whether a given brain CT scan contains
evidence of any one of five types of hemorrhages, multiple
different types of hemorrhages, or no hemorrhages. The pro-
vided data set has labeled images of CT scans which we can
use to train and test our models. The scans are formatted
such that a model will receive four image files per CT scan
– each a different rendering type of the same image (dif-
ferent rendering types may show various hemorrhages more
clearly). The model should then return whether the images
show evidence of a hemorrhage (or multiple hemorrhages)
or not. If there is evidence of a hemorrhage (or hemor-
rhages), it should return the type of hemorrhage it believes
exists (or the types, if multiple).
