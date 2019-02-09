## Details

The code is written in Tensorflow==1.8.0

There is CSV file included in data folder and code as well that will allow you to
generate small dataset for this project.

## How to use code

First go to data folder and execute command

```
python produce_colors.py
```

Then you can go to main directory and start training, it has 2 parameters
> restore_checkpoint --> default: None, give file path where you've saved your checkpoint, so that it continues training from saved path
> save_path --> default: model, path where model is saved.

for first time training you can execute:

```
python train.py --restore_checkpoint=None --save_path=Model
```

**Note: Those parameters are default, but I showed you just for exaple.
