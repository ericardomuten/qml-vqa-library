<div class="image-wrapper" >
  {% if include.url %}
  <a href="{{ include.url }}" title="{{ include.title }}" target="_blank">
  {% endif %}
      <img src="{{ site.url }}/{{ include.img }}" alt="{{ include.title }}"/>
  {% if include.url %}
  </a>
  {% endif %}
  {% if include.caption %}
      <p class="image-caption">{{ include.caption }}</p>
  {% endif %}
</div>

# QML-VQA Library
A curation of recent textbooks and research papers related to **quantum machine learning**, **variational quantum algorithms**, and **classical machine learning applications in quantum systems**.

<h1 align="center">
 <img src="https://media.springernature.com/lw785/springer-static/image/chp%3A10.1007%2F978-3-030-50433-5_45/MediaObjects/500809_1_En_45_Fig1_HTML.png" />
</h1>

{% include 500809_1_En_45_Fig1_HTML.png img="https://media.springernature.com/lw785/springer-static/image/chp%3A10.1007%2F978-3-030-50433-5_45/MediaObjects" title="Test1" caption="Test2" %}

## Table of Contents
- [Textbooks](https://github.com/eraraya-ricardo/qml-vqa-library#textbooks)
- [Reviews](https://github.com/eraraya-ricardo/qml-vqa-library#reviews)
- [Quantum Neural Networks & Quantum Classifier](https://github.com/eraraya-ricardo/qml-vqa-library#quantum-neural-networks-&-quantum-classifier)
  - [Quantum Neural Networks](https://github.com/eraraya-ricardo/qml-vqa-library#quantum-neural-networks)


### Textbooks
- [Supervised Learning with Quantum Computers](https://www.springer.com/gp/book/9783319964232) (2018)
- [Quantum Machine Learning: What Quantum Computing Means to Data Mining](https://www.sciencedirect.com/book/9780128009536/quantum-machine-learning) (2014)

### Reviews
- [Quantum machine learning in high energy physics](https://iopscience.iop.org/article/10.1088/2632-2153/abc17d) (2021)
- [Quantum machine learning and its supremacy in high energy physics](https://www.worldscientific.com/doi/abs/10.1142/S0217732320300244) (2021)
- [Variational Quantum Algorithms](https://arxiv.org/abs/2012.09265) (2020)
- [A non-review of Quantum Machine Learning: trends and explorations](https://quantum-journal.org/views/qv-2020-03-17-32/) (2020)
- [Quantum Deep Learning Neural Networks](https://link.springer.com/chapter/10.1007/978-3-030-12385-7_24) (2019)
- [Quantum machine learning: a classical perspective](https://doi.org/10.3929/ethz-b-000240892) (2018)
- [Quantum machine learning](https://www.nature.com/articles/nature23474) (2017)

### Quantum Neural Networks & Quantum Classifier
#### Quantum Neural Networks
- [Quantum state discrimination using noisy quantum neural networks](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.3.013063) (2021)
- [Event Classification with Quantum Machine Learning in High-Energy Physics](https://link.springer.com/article/10.1007%2Fs41781-020-00047-7) (2021)
- [Data re-uploading for a universal quantum classifier](https://quantum-journal.org/papers/q-2020-02-06-226/) (2020)
- [Application of Quantum Machine Learning to High Energy Physics Analysis at LHC using IBM Quantum Computer Simulators and IBM Quantum Computer Hardware](https://pos.sissa.it/367/049) (2019)
- [Classification with Quantum Neural Networks on Near Term Processors](https://arxiv.org/abs/1802.06002) (2018)
#### Quantum k-Nearest Neighbors
- [Implementing a distance-based classifier with a quantum interference circuit](https://iopscience.iop.org/article/10.1209/0295-5075/119/60002) (2017)

### Quantum Convolutional Neural Networks
#### Near Term (without QRAM)
- [Methods for accelerating geospatial data processing using quantum computers](https://link.springer.com/article/10.1007/s42484-020-00034-6) (2021)
- [Quantum Convolutional Neural Networks for High Energy Physics Data Analysis](https://arxiv.org/abs/2012.12177) (2020)
- [A Tutorial on Quantum Convolutional Neural Networks (QCNN)](https://arxiv.org/abs/2009.09423) (2020)
- [Explorations in Quantum Neural Networks with Intermediate Measurements](https://www.esann.org/sites/default/files/proceedings/2020/ES2020-197.pdf) (2020)
- [Quanvolutional neural networks: powering image recognition with quantum circuits](https://link.springer.com/article/10.1007/s42484-020-00012-y) (2020)
- [Hybrid Quantum-Classical Convolutional Neural Networks](https://arxiv.org/abs/1911.02998) (2019)
- [Quantum convolutional neural networks](https://www.nature.com/articles/s41567-019-0648-8) (2019)
#### Need QRAM
- [A quantum deep convolutional neural network for image recognition](https://iopscience.iop.org/article/10.1088/2058-9565/ab9f93) (2020)
- [Quantum Algorithms for Deep Convolutional Neural Networks](https://iclr.cc/virtual_2020/poster_Hygab1rKDS.html) (2020)

### Quantum Graph Neural Networks
- [A Tutorial on Quantum Graph Recurrent Neural Network (QGRNN)](https://ieeexplore.ieee.org/document/9333917) (2021)
- [Hybrid Quantum-Classical Graph Convolutional Network](https://arxiv.org/abs/2101.06189) (2021)
- [Performance of Particle Tracking Using a Quantum Graph Neural Network](https://inspirehep.net/literature/1834498) (2020)
- [A Quantum Graph Neural Network Approach to Particle Track Reconstruction](https://inspirehep.net/literature/1806878) (2020)
- [Particle Track Reconstruction with Quantum Algorithms](https://www.epj-conferences.org/articles/epjconf/pdf/2020/21/epjconf_chep2020_09013.pdf) (2019)
- [Quantum Graph Neural Networks](https://arxiv.org/abs/1909.12264) (2019)

### Quantum Generative Models & Quantum GANs
- [Noise Robustness and Experimental Demonstration of a Quantum Generative Adversarial Network for Continuous Distributions](https://onlinelibrary.wiley.com/doi/10.1002/qute.202000069) (2021)
- [Dual-Parameterized Quantum Circuit GAN Model in High Energy Physics](https://arxiv.org/abs/2103.15470) (2021)
- [Quantum Generative Adversarial Networks in a Continuous-Variable Architecture to Simulate High Energy Physics Detectors](https://arxiv.org/abs/2101.11132) (2021)
- [Quantum versus classical generative modelling in finance](https://iopscience.iop.org/article/10.1088/2058-9565/abd3db) (2021)
- [Experimental Quantum Generative Adversarial Networks for Image Generation](https://arxiv.org/abs/2010.06201) (2020)
- [Quantum semi-supervised generative adversarial network for enhanced data classification](https://arxiv.org/abs/2010.13727) (2020)
- [Quantum Generative Adversarial Networks for learning and loading random distributions](https://www.nature.com/articles/s41534-019-0223-2) (2019)
- [Quantum Generative Adversarial Learning](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.121.040502) (2018)
- [Quantum generative adversarial networks](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.98.012324) (2018)

### Variational Quantum Eigensolver
- [Resource-efficient quantum algorithm for protein folding (Application of CVaR-VQE)](https://www.nature.com/articles/s41534-021-00368-4) (2021)
- [Application of Quantum Machine Learning to VLSI Placement](https://dl.acm.org/doi/10.1145/3380446.3430644) (2020)
- [Improving Variational Quantum Optimization using CVaR](https://quantum-journal.org/papers/q-2020-04-20-256/) (2020)
- [The Meta-Variational Quantum Eigensolver (Meta-VQE): Learning energy profiles of parameterized Hamiltonians for quantum simulation](https://arxiv.org/abs/2009.13545) (2020)
- [Variational Quantum Computation of Excited States](https://quantum-journal.org/papers/q-2019-07-01-156/) (2019)
- [A variational eigenvalue solver on a photonic quantum processor](https://www.nature.com/articles/ncomms5213) (2014)

### Quantum Boltzmann Machines
- [Variational quantum Boltzmann machines](https://link.springer.com/article/10.1007%2Fs42484-020-00033-7) (2021)

### Quantum Image Processing
- [Quantum Image Processing and Its Application to Edge Detection: Theory and Experiment](https://journals.aps.org/prx/abstract/10.1103/PhysRevX.7.031041) (2017)

### Training Techniques
- [Avoiding local minima in Variational Quantum Algorithms with Neural Networks](https://arxiv.org/abs/2104.02955) (2021)
- [Layerwise learning for quantum neural networks](https://link.springer.com/article/10.1007%2Fs42484-020-00036-4) (2021)

### Circuit Learning Capability Analysis (Expressivity, Entanglement, etc.)
- [Expressibility of the alternating layered ansatz for quantum computation](https://quantum-journal.org/papers/q-2021-04-19-434/) (2021)
- [Evaluation of parameterized quantum circuits: on the relation between classification accuracy, expressibility, and entangling capability](https://link.springer.com/article/10.1007/s42484-021-00038-w) (2021)
- [Dimensional Expressivity Analysis of Parametric Quantum Circuits](https://quantum-journal.org/papers/q-2021-03-29-422/) (2021)
- [The power of quantum neural networks](https://arxiv.org/abs/2011.00027) (2020)
- [Power of data in quantum machine learning](https://arxiv.org/abs/2011.01938) (2020)
- [Expressibility and Entangling Capability of Parameterized Quantum Circuits for Hybrid Quantum-Classical Algorithms](https://onlinelibrary.wiley.com/doi/abs/10.1002/qute.201900070) (2019)

### Uncategorized (yet)
- [On the Quantum versus Classical Learnability of Discrete Distributions](https://quantum-journal.org/papers/q-2021-03-23-417/) (2021)
