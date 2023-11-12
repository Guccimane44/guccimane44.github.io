+++
title = 'From Adjoint Operator to Singular Value Decomposition'
date = 2023-10-18T08:03:50+01:00
draft = false
tags = ['linear algebra']
categories = ['math']
+++
## Isometry
A linear map is isometry if it perserves norms.
#### interesting properties:
* Isometry $\ S$ times its adjoint $S^{* }$  equal identity $I$
$$S^{*}S = I$$
* Orthonormal basis will be staying orthonormal to each others
$$Se_1, ... , Se_n$$

## Unitary Operators
An operator $S \in \mathcal L (V)$ is called _unitary_ if is an invertible isometry
#### interesting properties:
* Isometry $S$ times its adjoint $S^{* }$ equal identity $I $, and it has communitativity
$$S^{* }S = SS^{* } = I $$
* $S$ is invertible and $S^{-1}=S^{*}$
* $S$ is a unitary operator $\iff$ $\ S^{* }$ is a unitary operator
* Suppose $\lambda$ is an eigenvalue of a unitary operator. Then $|\lambda| = 1$
#### An example of being isometric but not unitary:
A projection from $\mathbb{R}$ to $\mathbb{R^{2}}$ is not invertible but it perserves the norms.
$$P: \mathbb{R} \longrightarrow \mathbb{R^{2}}$$
#### The importance of unitary operator:
* $S$ is a unitary operator $\iff$ There is an orthonormal basis of V consisting of eigenvectors of $S$ whose corresponding eigenvalues all have absolute value 1.

## The definition of adjoint operator
Adjoint operator looks really weird at the first glance. I will try to explain why it was defined as such.
#### Reisz representation theorem
Suppose $V$ is finite-dimensional and $\varphi$ is a linear funcitonal on $V$. Then there is a unique vector $v \in V$ such that
$$\varphi(u)=\langle u,v \rangle$$
for every $u\in V$




# Lets sort out these intertwining terminologies
* Math is like any other subjects, it started with intuition. However the deeper you dept, more unintuitive, weird, ugly facts will come out. When you learn enough about those ugly things, you will start to build a intuition around it. Then you will start the next round of digging. I think one probably would agree that a regular matrix is more interesting than a singular matrix, or 0 is more interesting than ... lets say $1729$. Or {A WEIRD LOOKING UNITARY MATRIX} 
* Operators are endomorphic linear mapping.
* Adjoint operator is the generalization of symmetric matrics and hermitian matrics. Because of the arthmitics differences between the real and complex space, hermitian matrics are __"the symmetric matrics we want in complex space"__.
* Now we are becoming more greedy in adjoint matrices. Only symmetry coundnt satisfy us. Our attention has drawn by self-adjoint operators, they are the adjoint operators with co 

# Under Construction...