# Floor Segmentation
In this experiment, we will train `resnet50dilated-ppm_deepsup` model on ADE20K.


## Training
```
python3 train.py --gpus $GPUS --cfg $CFG
```

## Testing
```
./demo_test.sh
```