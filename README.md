# FFA-IR
The official start-up code for paper "FFA-IR: Towards an Explainable and Reliable Medical Report Generation Benchmark."
 
The framework is inherited from [R2Gen](https://github.com/cuhksz-nlp/R2Gen).

## Data

Our dataset, including all FFA images and annotation files, is available on [PhysioNet](https://physionet.org/content/ffa-ir-medical-report/1.0.0/).

To extract all the files, please first download all the files in FFAIR, and use the command "cat FAIR.tar.gz.* | 
tar -zxv". Then the name of each directory refers to the case ID, and all the FFA images are provided.

Please put the data and annotation files in 'code/data' directory. Or you can change the code in main.py to fit your own condition.

## Requirements
- torch==1.5.1
- torchvision==0.6.1
- opencv-python==4.4.0.42

## Training

You can directly run our code by the following:

```python
python main.py
```

## Contact

If you are interested in this dataset or have any questions, please connect us: Mingjie.Li@monash.edu.
