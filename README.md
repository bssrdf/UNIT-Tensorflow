# UNIT-Tensorflow
Simple Tensorflow implementation of ["Unsupervised Image to Image Translation Networks"](https://arxiv.org/abs/1703.00848) (NIPS 2017)

## Usage
```bash
├── dataset
   └── YOUR_DATASET_NAME
       ├── trainA
           ├── xxx.jpg (name, format doesn't matter)
           ├── yyy.png
           └── ...
       ├── trainB
           ├── zzz.jpg
           ├── www.png
           └── ...
       ├── testA
           ├── aaa.jpg 
           ├── bbb.png
           └── ...
       └── testB
           ├── ccc.jpg 
           ├── ddd.png
           └── ...
```

```bash
> python main.py --phase train --dataset cat2tiger
```
* See `main.py` for other arguments

## Arichitecture
![architecture](./assests/architecture.png)

## Framework
![framework](./assests/framework.png)

## Model
![compare](./assests/compare.png)

![vae](./assests/vae_model.png)

![gan](./assests/gan_model.png)

![cycle](./assests/cycle.png)

## Training Objective
![objective](./assests/training_objective__.png)

## Result
### Success
![success](./assests/success.png)

### Fail
![fail](./assests/fail.png)

## Reference
* [Pytorch_code](https://github.com/mingyuliutw/UNIT)

## Author
Junho Kim
