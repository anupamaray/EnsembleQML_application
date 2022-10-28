![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20macOS%20%7C%20Windows-informational)
[![Python](https://img.shields.io/badge/Python-3.7%20%7C%203.8%20%7C%203.9%20%7C%203.10-informational)](https://www.python.org/)
[![Qiskit](https://img.shields.io/badge/Qiskit-%E2%89%A5%200.34.2-6133BD)](https://github.com/Qiskit/qiskit)
[![License](https://img.shields.io/github/license/qiskit-community/quantum-prototype-template?label=License)](https://github.com/qiskit-community/quantum-prototype-template/blob/main/LICENSE.txt)
[![Code style: Black](https://img.shields.io/badge/Code%20style-Black-000.svg)](https://github.com/psf/black)
[![Tests](https://github.com/qiskit-community/quantum-prototype-template/actions/workflows/test_latest_versions.yml/badge.svg)](https://github.com/qiskit-community/quantum-prototype-template/actions/workflows/test_latest_versions.yml)
[![Coverage](https://coveralls.io/repos/github/qiskit-community/quantum-prototype-template/badge.svg?branch=main)](https://coveralls.io/github/qiskit-community/quantum-prototype-template?branch=main)

# Classical Ensemble of Quantum-Classical machine learning models

This repository contains tutorial style notebooks to explain how to create ensembles using quantum and classical machine learning algorithms. These codes are based on the paper [1] and show two-level and three-level stacked ensembles that can be trained and tested on simulator as well as hardware.  The dataset used to reproduce the results in the paper are given in the codes folder and code to run classical Support Vector Machine (SVM), Quantum SVM and Variational Quantum Classifier (VQC) is present as well. Overall the entire script is generic and can be used for any other classification task.

### Table of Contents

##### For Users

1.  [About the Project](docs/project_overview.md)
2.  [Beginner's Guide](docs/beginners_guide.md)
3.  [Installation](INSTALL.md)
4.  [Quickstart Guide](docs/quickstart_guide.md)
5.  [Tutorials](docs/tutorials/example_tutorial.ipynb)
6.  [How-Tos](docs/how_tos/example_how_to.ipynb)
7.  [Prototype Template File Glossary](docs/file-map-and-description.md)
8.  [How to Give Feedback](#how-to-give-feedback)
9.  [Contribution Guidelines](#contribution-guidelines)
10. [References and Acknowledgements](#references-and-acknowledgements)
11. [License](#license)

##### For Developers/Contributors

1. [Contribution Guide](CONTRIBUTING.md)
2. [Technical Docs](docs/technical_docs.md)


----------------------------------------------------------------------------------------------------

### How to Give Feedback

We encourage your feedback! You can share your thoughts with us by:
- [Opening an issue](https://github.com/qiskit-community/quantum-prototype-template/issues) in the repository


----------------------------------------------------------------------------------------------------

### Contribution Guidelines

For information on how to contribute to this project, please take a look at our [contribution guidelines](CONTRIBUTING.md).


----------------------------------------------------------------------------------------------------

## References and Acknowledgements
[1] Diátaxis Technical Documentation Framework \
    https://diataxis.fr/


----------------------------------------------------------------------------------------------------

### License
[Apache License 2.0](LICENSE.txt)
