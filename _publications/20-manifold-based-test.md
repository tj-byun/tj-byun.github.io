---
title: "Manifold-based Test Generation for Image Classifiers"
collection: publications
permalink: /publication/2/15/20-manifold-based-test
excerpt: 'Neural networks used for image classification tasks in critical applications must be tested with sufficient realistic data to assure their correctness. To effectively test an image classification neural network, one must obtain realistic test data adequate enough to inspire confidence that differences between the implicit requirements and the learned model would be exposed. This raises two challenges: first, an adequate subset of the data points must be carefully chosen to inspire confidence, and second, the implicit requirements must be meaningfully extrapolated to data points beyond those in the explicit training set. This paper proposes a novel framework to address these challenges. Our approach is based on the premise that patterns in a large input data space can be effectively captured in a smaller manifold space, from which similar yet novel test cases---both the input and the label---can be sampled and generated. A variant of Conditional Variational Autoencoder (CVAE) is used for capturing this manifold with a generative function, and a search technique is applied on this manifold space to efficiently find fault-revealing inputs. Experiments show that this approach enables generation of thousands of realistic yet fault-revealing test cases efficiently even for well-trained models.'
date: 2/15/20
venue: 'AITest20'
paperurl: 'https://arxiv.org/pdf/2002.06337.pdf'
citation: '.'
---

<a href='https://arxiv.org/pdf/2002.06337.pdf'>Download paper here</a>

Neural networks used for image classification tasks in critical applications must be tested with sufficient realistic data to assure their correctness. To effectively test an image classification neural network, one must obtain realistic test data adequate enough to inspire confidence that differences between the implicit requirements and the learned model would be exposed. This raises two challenges: first, an adequate subset of the data points must be carefully chosen to inspire confidence, and second, the implicit requirements must be meaningfully extrapolated to data points beyond those in the explicit training set. This paper proposes a novel framework to address these challenges. Our approach is based on the premise that patterns in a large input data space can be effectively captured in a smaller manifold space, from which similar yet novel test cases---both the input and the label---can be sampled and generated. A variant of Conditional Variational Autoencoder (CVAE) is used for capturing this manifold with a generative function, and a search technique is applied on this manifold space to efficiently find fault-revealing inputs. Experiments show that this approach enables generation of thousands of realistic yet fault-revealing test cases efficiently even for well-trained models.

Recommended citation: .