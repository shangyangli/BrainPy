<p align="center">
  	<img alt="Header image of BrainPy - brain dynamics programming in Python." src="https://github.com/brainpy/BrainPy/blob/master/images/logo.png" width=80%>
</p> 



<p align="center">
	<a href="https://pypi.org/project/brainpy/"><img alt="Supported Python Version" src="https://img.shields.io/pypi/pyversions/brainpy"></a>
	<a href="https://github.com/brainpy/BrainPy"><img alt="LICENSE" src="https://anaconda.org/brainpy/brainpy/badges/license.svg"></a>
  	<a href="https://brainpy.readthedocs.io/en/latest/?badge=latest"><img alt="Documentation" src="https://readthedocs.org/projects/brainpy/badge/?version=latest"></a>
  	<a href="https://badge.fury.io/py/brainpy"><img alt="PyPI version" src="https://badge.fury.io/py/brainpy.svg"></a>
    <a href="https://github.com/brainpy/BrainPy/actions/workflows/CI.yml"><img alt="Continuous Integration" src="https://github.com/brainpy/BrainPy/actions/workflows/CI.yml/badge.svg"></a>
    <a href="https://github.com/brainpy/BrainPy/actions/workflows/CI-models.yml"><img alt="Continuous Integration with Models" src="https://github.com/brainpy/BrainPy/actions/workflows/CI-models.yml/badge.svg"></a>
</p>


BrainPy is a flexible, efficient, and extensible framework for computational neuroscience and brain-inspired computation based on the Just-In-Time (JIT) compilation (built on top of [JAX](https://github.com/google/jax), [Numba](https://github.com/numba/numba), and other JIT compilers). It provides an integrative ecosystem for brain dynamics programming, including brain dynamics **building**, **simulation**, **training**, **analysis**, etc. 

- **Website (documentation and APIs)**: https://brainpy.readthedocs.io/en/latest
- **Source**: https://github.com/brainpy/BrainPy
- **Bug reports**: https://github.com/brainpy/BrainPy/issues
- **Source on OpenI**: https://git.openi.org.cn/OpenI/BrainPy



## Installation

BrainPy is based on Python (>=3.8) and can be installed on Linux (Ubuntu 16.04 or later), macOS (10.12 or later), and Windows platforms. Install the latest version of BrainPy:

```bash
$ pip install brainpy brainpylib -U
```

For detailed installation instructions, please refer to the documentation: [Quickstart/Installation](https://brainpy.readthedocs.io/en/latest/quickstart/installation.html)


## Ecosystem

- **[BrainPy](https://github.com/brainpy/BrainPy)**: The solution for the general-purpose brain dynamics programming. 
- **[brainpy-examples](https://github.com/brainpy/examples)**: Comprehensive examples of BrainPy computation. 
- **[brainpy-datasets](https://github.com/brainpy/datasets)**: Neuromorphic and Cognitive Datasets for Brain Dynamics Modeling.

## Citing and Funding

If you are using ``brainpy``, please consider citing [the corresponding papers](https://brainpy.readthedocs.io/en/latest/tutorial_FAQs/citing_and_publication.html). 

BrainPy is developed by a team in Neural Information Processing Lab at Peking University, China. 
Our team is committed to the long-term maintenance and development of the project. 

Moreover, the development of BrainPy is being or has been supported by Science and Technology 
Innovation 2030 - Brain Science and Brain-inspired Intelligence Project (China Brain Project), 
and Beijing Academy of Artificial Intelligence. 


## Ongoing development plans

We highlight the key features and functionalities that are currently under active development. 

We also welcome your contributions 
(see [Contributing to BrainPy](https://brainpy.readthedocs.io/en/latest/tutorial_advanced/contributing.html)). 

- [x] model and data parallelization on multiple devices for dense connection models
- [ ] model parallelization on multiple devices for sparse spiking network models
- [ ] data parallelization on multiple devices for sparse spiking network models
- [ ] pipeline parallelization on multiple devices for sparse spiking network models
- [ ] multi-compartment modeling
- [ ] measurements, analysis, and visualization methods for large-scale spiking data

