# Math Explorer - My Linear Algebra & Optimization Playground

**Built everything from scratch.**

## What I Implemented

**Linear Algebra Toolkit**
- Matrix multiply, transpose, inverse (Gaussian elimination)
- Determinant (recursive)
- Eigenvalues/vectors (Power Iteration + Deflation)  
- SVD (iterative method, NO np.linalg.svd)

**Movie Recommender**
- 5x5 rating matrix with missing values
- Fill predictions using k=2 SVD
- Visualize user/movie latent factors

**Gradient Descent Playground**
- Vanilla, Momentum, Adam optimizers
- 3D function optimization f(x,y) = x² + y² + sin(xy)
- Tiny 2-3-1 neural net + backprop
- Interactive sliders for lr, iterations

**Interactive Toys**
- Eigenvector explorer (2x2 matrices)
- Central Limit Theorem demo
- SVD vs NumPy accuracy check

## Why I Built This
- **No black box libraries** - I see *exactly* how it works
- **Interactive** - tweak params, watch math happen live
- **Visual** - 3D plots, animations, latent space scatter
- **Production quality** - type hints, docstrings, modular

## Key Realizations
✅ SVD = "rotate → scale → rotate back"  
✅ Power iteration finds dominant eigenvector  
✅ Adam = momentum + RMSProp  
✅ Low-rank approx fills missing ratings perfectly  

**Error between my SVD and NumPy: < 1e-6** 🎯

---
