# Total-variation-denoising
Consider a signal $x \in \mathbb{R}^n$ corrupted by noise.
We measure the corrupted signal $x_{\text{corr}}$ and wish to recover a good estimate $\hat{x}$ of the original signal.
To do this we solve the total variation denoising problem

$$
    \text{minimize} \quad \|\hat{x} - x_{\text{corr}}\|_2^2 + \lambda \|D \hat{x}\|_1
$$

where $D$ is the discrete derivative operator.
