# Anomalib-Notebooks2023
A selection of modifed Jupyter Notebooks, and config.yaml files to use with Anomalib.

These files were used with a custom dataset called IHT2 that was loaded into the MVTEC AD Dataset directory as part of a white paper due to be published in fall 2023. They are primarily used to train a modem, for example PADIM, and generate images after running inference on a subset of the IHT2 dataset. These images are used in the white paper. The accompanying config.yaml files are supplied for use in the notebooks. They need manual editing to select the required data directory in the MVTEC Dataset.  Directory names will need to be in the correct case, if used with Linux. 

If you want to use these files, simply replace the original ones in the Anomalib directories with these. There's a config.yaml file associated with each model directory.

The recommended method of getting a good Jupyter Server installation, needed to run the notebooks, is to use the following repo https://github.com/openvinotoolkit/openvino_notebooks inside the Anomalib Python environment.
