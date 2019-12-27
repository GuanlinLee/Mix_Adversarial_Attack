# Mix_Adversarial_Attack
A new white-box adversarial attack with mixed loss function and gradients

----
We propose a new white-box attack based on multi loss functions and bagging
lots of attack method with same restart times achieving better attack performance.

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
>1.SSIM for Feature Maps
>
>2.L2 Loss for Pre-Outputs
>
>3.Earth Moved Distance for Probability
>
>4.Cross-Entropy Loss
>
>5.C&W Loss

---

Trick List:
>
>1.Channel-Wise Self-Attention for Feature Maps
>
>2.Sobel Edge Locating Interesting Area 
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

