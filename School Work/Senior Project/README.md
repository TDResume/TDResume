This folder is a small extract from my Senior Design project.
After segmenting cells by hand on a dozen of images, we are using a maskRCNN to create an instance segmentation algorithm.

We are creating an application, capable of handling complex images (multi-channel tiff files). Once the user load its image and selects a region of interest, she/he will be able to detect the cells in the tissue. The user will then be able to extract the cells' information as a csv.

The current training script is still work in progress. Our first approach with only 10 images of training data gave us some first results. They are however pretty porr, we currently creating more training data, based on multiple sources, our results should be much more precise with 50 - 100 training images
