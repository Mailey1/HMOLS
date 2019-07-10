# HMOLS
(Holey Mutually Orthogonal Latin Squares)

The python notebooks in this repo contain my work on generalizing a construction by Stinson and Dinitz in section 4 of their paper, [MOLS With Holes](https://www.sciencedirect.com/science/article/pii/0012365X83900559). Their construction uses a boolean Hadamard matrix of order 8 to obtain up to 6-HMOLS of type _2<sup>q</sup>_, where _q_ is any prime power congruent 1 mod 4. For information about the generalization refer to sections 3 and 4 of my [paper](498-final-paper.pdf).


## [11-HMOLS(1009)_test.ipynb](11-HMOLS(1009)_test.ipynb)

This notebook contains my work on finding 10-HMOLS(2<sup>1009</sup>), and an unsuccessful attempt at extending to 11-HMOLS. It also includes lots of rough work from initially figuring out the project. [HMOLS(2^1009)_check.ipynb](HMOLS(2^1009)_check.ipynb) just contains some code to do a second verification that the vectors found in 11-HMOLS(1009)_test.ipynb do indeed work.

## Larger Matrices and Alphabet Sizes

In the other two notebooks, [CosetsForBiggerMatrices.ipynb](CosetsForBiggerMatrices.ipynb) and [3-Holes_Coset_Finding.ipynb](3-Holes_Coset_Finding.ipynb), I just used the allowed coset finding algorithm from 11-HMOLS(1009)_test.ipynb on bigger matrices for both alphabet sizes 2 and 3 to see which order of Hadamard matrices would give good cosets. 
