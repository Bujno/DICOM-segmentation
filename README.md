# DICOM Segmentation

> JupyterNotebook with Anaconda or Visual Studio Code with Jupyter extention are suggested enviroments

### DICOM and HU introduction 

#### DICOM
DICOM is an acronym for Digital Imaging and Communication in Medicine. Files in this format are most likely saved with a ‘dcm’ file extension. DICOM is both a communication protocol and a file format; This means that a patient can store medical information such as ultrasound and MRI images along with their information in a single file.This format not only keeps all the data together, but also ensures that the information is transferred between devices that support the DICOM format.

#### HU
The Hounsfield Unit (HU) is a relative quantitative measurement of the intensity of radio waves used by radiologists for better explanation and understanding of computed tomography (CT) images. The absorption/attenuation coefficient of radiation within a tissue is used during CT reconstruction to produce a grayscale image. Here's a quick list of a few useful ones, sourced from Wikipedia.

| Substance |                        HU                       |
|:---------:|:-----------------------------------------------:|
| Air       | −1000                                           |
| Lung      | −500                                            |
| Fat       | −100 to −50                                     |
| Water     | 0                                               |
| Blood     | +30 to +70                                      |
| Muscle    | +10 to +40                                      |
| Liver     | +40 to +60                                      |
| Bone      | +700 (cancellous bone) to +3000 (cortical bone) |


### Requirements
```
pip install pydicom
conda install plotly
conda install scikit-image
```

### Dataset
https://www.kaggle.com/abhinavvadlamani/lung-cancer-2

### Issues during implementation
- https://stackoverflow.com/questions/68736618/error-loading-preloads-could-not-find-renderer
- https://scikit-image.org/docs/dev/auto_examples/edges/plot_contours.html#sphx-glr-auto-examples-edges-plot-contours-py
