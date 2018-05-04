# Statistics and File Naming:

This page is for results of the various tests in the BABI set and for explaining the naming conventions that we're trying to stick to. The  table may be incomplete.

#### Babi:
There are 20 tests. One at a time we will try to fill in the results that we achieve in the table below. Also below is a list of filenames. Though one model is meant to complete all the tests with the same saved weights, we willl assume that each test is done seperately. At the end we may include a result for testing on all the categories at once.

* `baseline_dmn` This would be a figure for comparrison that was taken from literature on the subject. It does not reflect work done with this project. It is generally used with heavy supervision. [See here.](https://arxiv.org/pdf/1506.07285.pdf)
* `Mem_NN` This would be a figure for comparrison. [See here.](https://yerevann.github.io/2016/02/05/implementing-dynamic-memory-networks/)
* `babi_ii100a` Since the 'babi_ii.py' file is the most complete model it will be the starting base filename for out tests. This column reflects testing done with 100 hidden units and trainable embeddings. 
* `babi_ii100b` This would reflect 100 hidden units but frozen non-trainable embeddings. Note that this does not mean pre-trained embeddings but rather frozen embeddings with entirely random contents.
* `babi_ii100c` If it is included, this would have trained embeddings and 100 units in the hidden layer.

The table is included here:

 |   | baseline_dmn | Mem_NN | babi_ii100a | babi_ii100b | babi_ii100c | 
|-|-|-|-|-|-|
 | 1 | 1 | 2 | 3 | 0 | 0 |
 | 2 | 1 | 2 | 3 | 0 | 0 |
 | 3 | 0 | 0 | 0 | 0 | 0 |
 | 4 | 0 | 0 | 0 | 0 | 0 |
 | 5 | 0 | 0 | 0 | 0 | 0 |
 | 6 | 0 | 0 | 0 | 0 | 0 |
 | 7 | 0 | 0 | 0 | 0 | 0 |
 | 8 | 0 | 0 | 0 | 0 | 0 |
 | 9 | 0 | 0 | 0 | 0 | 0 |
 | 10 | 0 | 0 | 0 | 0 | 0 |
 | 11 | 0 | 0 | 0 | 0 | 0 |
 | 12 | 0 | 0 | 0 | 0 | 0 |
 | 13 | 0 | 0 | 0 | 0 | 0 |
 | 14 | 0 | 0 | 0 | 0 | 0 |
 | 15 | 0 | 0 | 0 | 0 | 0 |
 | 16 | 0 | 0 | 0 | 0 | 0 |
 | 17 | 0 | 0 | 0 | 0 | 0 |
 | 18 | 0 | 0 | 0 | 0 | 0 |
 | 19 | 0 | 0 | 0 | 0 | 0 |
 | 20 | 0 | 0 | 0 | 0 | 0 |

#### Training and Testing:
All results at this time benefit from weak or no supervision during training.


more after text