The repository associated with the paper "Robust and Provable Guarantees for Sparse Random Embeddings".

The results improve upon the guarantees for sparse random embeddings. Specifically, our bounds are explicit (as opposed to the asymptotic guarantees provided previously), and (b) our bounds are guaranteed to be sharper across all parameters, including the dimensionality, sparsity and dispersion of the data. 

The experiments empirically demonstrate that our bounds significantly outperform prior works on a wide range of real-world datasets, such as collections of images, text documents represented as bags-of-words, and text sequences vectorized by neural embeddings.

## Experiments

Many real-world datasets are employed in the experiments. Some datasets have a small number of features, which is to demonstrate that the new bounds give good results also when dimensionality is small. The following table summarizes the analyzed datasets:

| Dataset | Type | Comments |
|---------|----------|---------|
| NIPS | text | 13.000 words |
| W2V/Wiki | text | 5M lines |
| News20 | text | 20k documents |
| MNIST | images | 60k images 28x28|
| CIFAR100 | images | 60k images 32x32 |
| SVHN | images | 600k images 32x32 |
| Caltech | images | 9k images 300x200 |
| Cars | images | 16k images 500x500 |
| Goodwin | fliud dyn | 18k columns x 18k rows |
| Mycieliskian | graph | 98k colums x 98k rows |




## Implementation

See the [notebook](./SparseRandomProjections_NIPS21.ipynb) for details.
