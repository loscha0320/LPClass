# Pytorch LPClass Examples


Please follow the instructions before using this example.

**Environment require：** pytorch > 1.1.0 with Python 3

## Fetching Data

Please make a directory may called *' ./data '* and download your data in it.
You need to perform some pre-processing to extract the data into a 3-dimensional time series.

## Training the Model

A sample (SRNN_Example.py) is provided to you. To run the command line script, please use:
  
```
python SRNN_Example.py --data-dir ./date/your source data/Extracted/ --brick-size 11
```

Please comment out certain code in the source code.

## Transferring the Model

A sample (transfer.py) is provided to you. To run the command line script, please use:
  
```
python transfer.py --data-dir ./data/your target data/Extracted/ --brick-size 11
```

Please comment out certain code in the source code.




