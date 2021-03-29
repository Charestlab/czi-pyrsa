### 6. Proposal Summary/Scope of Work (required):

## Provide a short summary of the application (maximum of 500 words)


- what is RSA, benefits in short


Representational Similarity Analysis (RSA) is a versatile analysis technique that is gaining popularity in relating neuroscientific data from different measurement modalities [1–9]. In RSA, a representational dissimilarity matrix (RDM) is computed by comparing patterns of data across every possible pairs of conditions, resulting in a symmetric distance matrix with rows and columns encoding the experimental conditions.  This technique is powerful in that it enables comparison of data from multiple modalities, combining the strengths of each modality in understanding brain function, in a simple, elegant manner. This feat of RSA has been coined the Representational Similarity Trick.  A recent application has shown that the full spatio-temporal dynamics of visual object recognition in brain and behaviour can be characterised by combining magnetoencephalographic (MEG), functional magnetic resonance imaging (fMRI), behavioural data (collected on our behavioural platform Meadows Research ), and artificial neural network (ANN) data using this RSA trick [4,6]. This approach exemplifies the emerging interdisciplinary field of computational cognitive neuroscience, and representational similarity analysis is increasingly popular in disciplines outside of cognitive neuroscience.

complex -> matlab code -> python more popular -> only supports a subset of options -> statistical poverty

from four different labs in three countries when we got together summer of 2019. It was quickly decided that a python package was needed and that it should set example of how to proper. This set off an initial burst of contributions from the workshop participants but since -> as-needed-basis without the needs of the community -> loss of integration

- what is needed: professionalize, technical debt, documentation, UX, inclusiveness, continuous intregration
- pay time of developer, community organization, outreach

My laboratory and several others around the world are at the forefront of the open-source and community driven development of algorithms underlying RSA (see our GitHub repository at http://github.com/rsagroup/pyrsa). With this proposal, we will continue to maintain the pyRSA Python library for representational similarity analysis applied to medical imaging data, behavioural data and computational models, and continue developing novel representational metrics to construct RDMs, and to compare RDMs between imaging modalities, people, species, models etc. Key to the success of this library will be to extend our existing documentation framework (https://rsa3.readthedocs.io/en/latest/), provide additional comprehensive jupyter-notebook tutorials, and provide additional compatibilities with deep learning frameworks including tensorflow and pytorch.   