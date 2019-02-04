# CIGAR

This is a anonymous repository for review only. Tensorflow (1.12) is required, but GPUs are not necessary. More information and cleaner code will be released after the review period.     


## Demo

The repo includes the `Yelp` dataset. Our model can be trained by: 

```
python main.py --dataset=yelp --C_dim=64 --C_lam=0.1 --C_m=8 --F_m=8 --F_hr=0.5 --F_model=BPR --F_dim=50 --F_lam=0.1 --F_nc=200
```