# Linear Algebra - Chapter 1: Vectors

**Date**: October 6, 2025  
**Source**: 3Blue1Brown - Essence of Linear Algebra  
**Status**: 🟢 Completed

---

## Video 1: Vectors - What Even Are They?

### 🎯 Key Concepts

**Three Perspectives on Vectors**:

1. **Physics perspective**: Arrows in space with magnitude and direction
2. **Computer Science**: Ordered lists of numbers `[x, y, z]`
3. **Mathematics**: Anything that can be added and scaled

**The ML/Data Science view**: Vectors are data points in n-dimensional space! (Just points in 2d space)

### 💡 Big Insight

> Vectors aren't just arrows - they represent transformations and positions in space.

### 📊 Visual Understanding

2D Vector:

x-component: 3 (horizontal)

y-component: 2 (vertical)

Starts at origin (0,0)

Points to (3,2)

### 🐍 Python Implementation

v = # Simple list

import numpy as np
v = np.array()

## Video 2: Linear Combinations, Span, and Basis Vectors

### 🎯 Key Concepts

**Basis Vectors** (î and ĵ in 2D):

- î = [1, 0] → unit vector along x-axis
- ĵ = [0, 1] → unit vector along y-axis
- ANY 2D vector can be written as combination of these!

**Example**:

= 3î + 2ĵ
= 3 + 2

**Linear Combination**:

- Taking two vectors, scaling them, and adding
- Formula: `a·v + b·w` where a, b are scalars

**Span**:

- Set of ALL possible vectors you can reach with linear combinations
- Two 2D vectors span entire 2D space (unless collinear!)
- Three vectors in 2D? One is redundant (linearly dependent)

### 💡 Big Insight

> "Span" = all possible destinations you can reach by scaling and adding vectors

### 📊 Visual Understanding

Span of one vector: A LINE
Span of two non-collinear vectors: A PLANE
Span of three 3D vectors: ENTIRE 3D SPACE (if linearly independent)

### 🐍 Python Code to Test

import numpy as np

Basis vectors
i_hat = np.array()
j_hat = np.array()

Any vector as linear combination
v = 3i_hat + 2j_hat
print(f"v = {v}") # Should be

Linear combination example
v1 = np.array()
v2 = np.array()
combination = 2v1 + 3v2 # Scaling and adding
print(f"2v1 + 3v2 = {combination}")

## 🔗 Connection to Machine Learning

**Why This Matters for ML**:

- Data points are vectors in high-dimensional space
- Features = components of vectors
- Dimensionality reduction = finding better basis vectors
- Neural networks = learning transformations of vector spaces

**Example**:
An image = vector with pixels as components (e.g., 784 dimensions for 28×28 image)

---

## ✅ What I Understand Now

- [x] Vectors can be viewed as arrows, lists, or abstract objects
- [x] Basis vectors are building blocks for all vectors
- [x] Linear combinations create new vectors
- [x] Span = all reachable vectors from combinations

## 🔴 What I Need to Practice

- [ ] Calculating span of given vectors
- [ ] Checking linear independence
- [ ] More examples with 3D vectors
- [ ] Implementing matrix operations

---

## 📝 Next Steps

- Watch Chapter 2: Linear transformations and matrices
- Implement vector class with more operations
- Practice Khan Academy linear algebra exercises
- Code visualization of vector addition

---

**Last Updated**: October 6, 2025 10:00 AM
