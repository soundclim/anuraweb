---
layout: default
title: AnuraSet
---

# Overview

We present a large-scale multi-species dataset of acoustics recordings of amphibians anuran from passive acoustic recordings. The dataset comprises 27 hours of herpetologist annotations of 42 different species in different regions of Brazil. The classification task is unique and challenging due to the high species diversity, the long-tailed distribution, and frequent overlapping calls. The dataset, including raw recordings, preprocessing code, and baseline code, is made available to promote collaboration between machine learning researchers and ecologists in solving the classification challenges toward understanding the effects of global change on biodiversity. A more thorough description of the dataset is available in our [research paper](https://arxiv.org/abs/2307.06860).

<a href="https://doi.org/10.5281/zenodo.8056090"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.8056090.svg" alt="DOI"></a>
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

# Key Features

**Multilabel Annotation:** The dataset includes multilabel annotations, allowing for the classification of audio samples into multiple categories simultaneously. This feature is particularly useful for tasks involving signal classification in complex multi-species choruses.

**Expert Annotations:** This dataset comprises approximately 27 hours of audio recordings annotated by expert herpetologists. It has weak labels, with the presence and absence of species at a 60 second resolution, and also strong labels with precise location of the signals of the identified species.

**Biomes:** This dataset covers two unique tropical biomes, the Atlantic Forest and the Cerrado, providing a representation of environmental sound across different ecosystems.

**Sites:** It contains audio recordings from four distinct geographical sites, ensuring diversity in the acoustic environments and capturing soundscapes from various locations.

**Species:** The dataset encompasses a rich biodiversity with recordings of 42 different tropical anuran species. Researchers and enthusiasts can explore the acoustic signatures of various fauna, aiding in biodiversity monitoring and conservation efforts.

**Preprocessed Samples:** The dataset also includes 93 thousand preprocessed audio samples. Each sample is fixed at a length of 3 seconds, making it suitable for standard machine learning models. These preprocessed samples have undergone necessary transformations to ensure consistency and compatibility for analysis.

# Preview

Dive into our curated collection of brief audio snippets, extracted from our extensive dataset. These snippets were uploaded to [xeno-canto](https://xeno-canto.org/) to offer a glimpse into the rich variety of sounds encompassed within the larger audio collection.

<iframe src='https://xeno-canto.org/826358/embed' scrolling='no' frameborder='0' width='340' height='220'></iframe>
<iframe src='https://xeno-canto.org/826370/embed' scrolling='no' frameborder='0' width='340' height='220'></iframe>

<iframe src='https://xeno-canto.org/826589/embed' scrolling='no' frameborder='0' width='340' height='220'></iframe>
<iframe src='https://xeno-canto.org/826995/embed' scrolling='no' frameborder='0' width='340' height='220'></iframe>

<iframe src='https://xeno-canto.org/826536/embed' scrolling='no' frameborder='0' width='340' height='220'></iframe>
<iframe src='https://xeno-canto.org/826588/embed' scrolling='no' frameborder='0' width='340' height='220'></iframe>

<iframe src='https://xeno-canto.org/826378/embed' scrolling='no' frameborder='0' width='340' height='220'></iframe>
<iframe src='https://xeno-canto.org/826380/embed' scrolling='no' frameborder='0' width='340' height='220'></iframe>

# Citing this work

If you find the AnuraSet useful for your research, please consider citing it as:

> Cañas, J. S., Toro-Gómez, M. P., Sugai, L. S. M., Restrepo, H. D. B., Rudas, J., Bautista, B. P., ... & Ulloa, J. S. (2023). AnuraSet: A dataset for benchmarking Neotropical anuran calls identification in passive acoustic monitoring. arXiv preprint arXiv:2307.06860.

# Contribute

Participating in this project by identifying and rectifying bugs, as well as addressing open issues, is an invaluable way to make a meaningful impact. Your involvement not only aids in refining the project's functionality but also strengthens the collaborative spirit within the developer community.

When you encounter a bug or notice an issue within the project, don't hesitate to report it on the [AnuraSet's repository](https://github.com/soundclim/anuraset/issues). Be sure to provide a clear and detailed description of the problem, including steps to reproduce the issue if possible. This helps the project maintainers and other contributors understand the problem better.

# More resources

In this session of [BioacousTalks](https://www.birds.cornell.edu/ccb/bioacoustalks/) we present the motivation and details behind AnuraSet.

<iframe width="560" height="315" src="https://www.youtube.com/embed/nP31AXiEl1Q?si=FjC8akLd0TcF2lE-&amp;start=3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Authors
Juan Sebastián Cañas, Maria Paula Toro-Gómez, Larissa Sayuri Moreira Sugai, Hernán Darío Benítez Restrepo, Jorge Rudas, Breyner Posso Bautista, Luís Felipe Toledo, Simone Dena, Adão Henrique Rosa Domingos, Franco Leandro de Souza, Selvino Neckel-Oliveira, Anderson da Rosa , Vítor Carvalho-Rocha, José Luiz Massao Moreira Sugai, José Vinícius Bernardy, Carolina Emília dos Santos, Rogério Pereira Bastos, Diego Llusia, Juan Sebastián Ulloa

# Acknowledgments
The authors acknowledge financial support from the intergovernmental Group on Earth Observations (GEO) and Microsoft, under the GEO-Microsoft Planetary Computer Programme (October 2021); São Paulo Research Foundation (FAPESP #2016/25358-3; #2019/18335-5); the National Council for Scientific and Technological Development (CNPq #302834/2020-6; #312338/2021-0, #307599/2021-3); National Institutes for Science and Technology (INCT) in Ecology, Evolution, and Biodiversity Conservation, supported by MCTIC/CNpq (proc. 465610/2014-5), FAPEG (proc. 201810267000023); CNPQ/MCTI/CONFAP-FAPS/PELD No 21/2020 (FAPESC 2021TR386); Comunidad de Madrid (2020-T1/AMB-20636, Atracción de Talento Investigador, Spain) and research projects funded by the European Commission (EAVESTROP–661408, Global Marie S. Curie fellowship, program H2020, EU); and the Ministerio de Economía, Industria y Competitividad (CGL2017-88764-R, MINECO/AEI/FEDER, Spain).