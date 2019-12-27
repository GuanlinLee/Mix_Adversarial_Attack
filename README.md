# Mix_Adversarial_Attack
A new white-box adversarial attack with mixed loss function and gradients

----
We propose a new white-box attack based on multi loss functions and 
bagging lots of attack methods. Even with the smaller restart times, 
it could achieve better attack performance.

---

Attack Method List:
>
>1.[DAA-BLOB](https://github.com/tianzheng4/Distributionally-Adversarial-Attack)
>
>2.Gradients Mixture
>
>3.Sobel Edge Inner Mask
>
>4.Gradients Sign-Bagging Mixture
>
>5.Sobel Edge Outer Mask
>
>6.Sobel Edge Inner+Outer Mask

---

Loss Function List:
>
>1.[SSIM](https://github.com/tensorflow/tensorflow/blob/r2.0/tensorflow/python/ops/image_ops_impl.py#L3295-L3419) for Feature Maps
>
>2.L2 Loss for Pre-Outputs
>
>3.[Earth Mover's Distance](https://github.com/master/nima) for Probability
>
>4.[Cross-Entropy Loss](https://github.com/MadryLab/cifar10_challenge)
>
>5.[C&W Loss](https://github.com/MadryLab/cifar10_challenge)

---

Trick List:
>
>1.[Channel-Wise Self-Attention](https://github.com/facebookresearch/ImageNet-Adversarial-Training) for Feature Maps
>
>2.[Sobel Edge](https://github.com/tensorflow/tensorflow/blob/r2.0/tensorflow/python/ops/image_ops_impl.py#L3463-L3501) Locating Interesting Area 
>
>3.Better Start and Restart Place
>
>4.Bagging Different Sign of Gradients
>
>5.Boosting Different Gradients
>
>6.Random Size of Step
>
>7.Adversarial Examples Collecting Before Each Restart

