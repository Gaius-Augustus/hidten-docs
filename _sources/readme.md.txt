# hidten
A framework for combining hidden Markov- and related models with modern deep learning.

### Targeted features

- "pythonic", clean, extensible, tested
- gradient-based training and inference of models with a linear chain of hidden variables (currently: HMMs, future: CRFs)
- vectorized and differentiable algorithms
- modular emission *scores* (discrete or continuous distributions, future: even non-probabilistic feature functions)
- supports multiple, parallel HMM *heads* with variable architectures
- implements time-parallel variants of all algorithms to support ultra-long sequences
- future (?): swapable machine learning backend (currently only TensorFlow)
- future (?): higher order

### Installation

`git clone https://github.com/Gaius-Augustus/hidten`

For users:

`pip install -e .[tensorflow]`

For developers:

`pip install -e .[tensorflow,test,docs]`

### Documentation

Build the docs:

`cd docs && make html`
