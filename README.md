
# Open Computational Neuroscience Resources

Computational neuroscience means one of two things: 1. analysis of
neuroscientific data, whether it be fMRI imaging data, electrode recordings
from a mouse running in a maze, statistical modeling of that data, or something
else, and 2. simulation of neural systems, including modeling many compartments
of a single neuron, or large networks of model neurons with simple individual
behavior. These endeavors require expensive data from wet-lab experiments, but
much of the work can be accomplished using everyday, consumer-grade laptop and
desktop computers! Indeed, the biggest barrier to entry is not hardware, data,
or expense, but rather time and passion to learn the tools needed for such
computational science. Coupled with the great tools coming out of the modern
Data Science movement, open data, open simulation models, and open analysis and
simulation tools for computational neuroscience make it easier than ever to
learn or even contribute to the study of the brain! **The resources below should
be more than enough to provide anyone with the means to begin learning or
working in computational neuroscience, at no cost other than time and a
modern computer.**

Note: This is intended as a list of resources to help with *neuroscientific*
pursuits, as opposed to *artificial intelligence* pursuits. [More broadly, I've
made a similar repo-list of general open science resources
here](https://github.com/asoplata/open-science-resources).

Contributions are VERY welcome!

-----------------------------------

- Contents:
    - [Meta-resources](#meta-resources)
    - [Markup Languages for cross-simulator model
      usage](#markup-languages-for-cross-simulator-model-usage)
    - [Open Code](#open-code)
    - [Open Courses](#open-courses)
    - [Open Data](#open-data)
    - [Open Textbooks](#open-textbook)
    - [Organizations and Communities](#organizations-and-communities)

-----------------------------------

### Meta-resources

- [Allen Institute for Brain
  Science](http://www.alleninstitute.org/what-we-do/brain-science/research/products-tools/)
- [COMBINE - Computational modeling in biology network](http://co.mbine.org/standards)
- [Comparison of Neural Network
  Simulators](https://grey.colorado.edu/emergent/index.php/Comparison_of_Neural_Network_Simulators)
- [Computational Neuroscience journals](http://www.cnsorg.org/journals)
- [Jim Perlewitz' "Computational Neuroscience on the Web" - Probably the most
  comprehensive *curated* list of computational neuroscience modeling tools on
  the internet. HIGHLY recommended.](http://home.earthlink.net/~perlewitz/)
    - Website may be offline now, but you can access an archived version [here at the Internet Archive](https://web.archive.org/web/20190301105153/http://home.earthlink.net/~perlewitz/)
- [NCBI databases - National Center for Biotechnology Information database
  list, VERY comprehensive!](http://www.ncbi.nlm.nih.gov/guide/all/)
- [NIF - Neuroscience Infomation Framework - Search for EVERY kind of
  neuroscience data, atlas, software, everything!](https://neuinfo.org/)
    - This is the most comprehensive tool for open neuroscience resources in
      the world. If it exists on the internet, it's probably indexed here.
- [NSG - Neuroscience Gateway - An online resource that allows public usage of
  high performance computing resources for neural
  simulation!](http://www.nsgportal.org/index.html)
- Open Hardware - [see this Open Science Resources
  page](https://github.com/asoplata/open-science-resources#open-diy-hardware)
- [Wikipedia List of Neuroscience Databases](https://en.wikipedia.org/wiki/List_of_neuroscience_databases)
- [An aggregation of neuroscience journal RSS feeds](http://sanjayankur31.github.io/planet-neuroscience/)

### Markup Languages for cross-simulator model usage

- [CellML - A model description language for general biological mathematical
  modeling](https://www.cellml.org/)
- [NeuroML - A model description language for computational
  neuroscience](https://www.neuroml.org/)
    - Converts to different kinds of simulators:
      https://www.neuroml.org/tool_support
- [NineML - A model description language for
  neuroscience](http://incf.github.io/nineml-spec/)

### Open Code

- [Funding research software development](https://www.software.ac.uk/how-fund-research-software-development)

##### Non-imaging Analysis

- [bctnet - Brain Connectivity Toolbox for complex-network analysis](https://sites.google.com/site/bctnet/)
- [Chronux - MATLAB toolbox for EEG analysis, including some tools for MEG, fMRI, and image data](http://chronux.org/)
- [EEGLAB - MATLAB toolbox for EEG, MEG, and ECOG data analysis and
  visualization](https://sccn.ucsd.edu/eeglab/index.php)
- [Elephant - Software for common electrophysiological data analysis
  operations, built on the Neo data
  format](http://neuralensemble.org/elephant/)
- [FieldTrip - MATLAB toolbox for EEG, MEG, and ECoG analysis](http://www.fieldtriptoolbox.org/)
- [Geppetto - Web-based, open-source visualization platform for computational
  biology](http://www.geppetto.org/)
- [OpenElectrophy - Analysis software for electrophysiological data, built on
  the Neo data format](http://neuralensemble.org/OpenElectrophy/)
- [MNE - MEG + EEG analysis and visualization tool in
  Python](http://martinos.org/mne/stable/index.html)
- [Neo - Python library for enabling interoperability of electrophysiological
  data, including conversion from proprietary file
  formats](http://neuralensemble.org/neo/)
- [NeuronUnit - Data-driven model validation for
  neuroscience](https://github.com/scidash/neuronunit)
- [SpectraVis - Network visualization tool for functional brain connectivity
  in-browser](https://github.com/NeurophysVis/SpectraVis)
- [Spike Sorting Software - VERY good comparison of different spike sorting software capabilities](https://simonster.github.io/SpikeSortingSoftware/)
- [SpykeViewer - Analysis software for spikes of electrophysiological data,
  built on the Neo data format](http://neuralensemble.org/SpykeViewer/)
- [supereeg - Sparse ECoG analysis](http://supereeg.readthedocs.io/en/latest/)
- [Vaa3D - 3D Visualization-Assisted
  Analysis](http://www.alleninstitute.org/what-we-do/brain-science/research/products-tools/vaa3d/)

##### Imaging Analysis

- [Allen SDK - Allen (Institute) Software Development Kit for Allen Brain
  Atlas](http://alleninstitute.github.io/AllenSDK/)
- [CaImAn - Calcium Imaging Analysis](https://github.com/flatironinstitute/CaImAn)
- [CATMAID - The Collaborative Annotation Toolkit for Massive Amounts of Image
  Data](http://catmaid.readthedocs.io/en/stable/)
- [FreeSurfer - Popular open-source MRI processing and analysis
  software](https://surfer.nmr.mgh.harvard.edu/)
- [NiBabel - Python library for enabling interoperability of neuroimaging data,
  including conversion from and between many file
  formats](http://neuralensemble.org/neo/)
- [TrakEM2 - Morphological data mining and analysis
  tool](http://www.ini.uzh.ch/~acardona/trakem2.html)
- [TREES - MATLAB toolbox for analyzing neuron
  microscopy](http://www.treestoolbox.org/)

##### Simulation

- Note: some of these tools are interoperable to some degree.
- [BindsNET - Simulation of spiking neural networks (SNNs) using PyTorch](https://github.com/Hananel-Hazan/bindsnet)
- [Brian2 - Powerful, modern neural simulator written in Pythonthat offers
  built-in compilation](http://brian2.readthedocs.io/en/stable/)
- [CoreNeuron - Optimized, simplified NEURON implementation used by the Blue
  Brain Project](https://github.com/BlueBrain/CoreNeuron)
- [DiPDE - Platform for population-level neural
  simulation](http://alleninstitute.github.io/dipde/)
- [DynaSim - Open-source MATLAB/GNU Octave toolbox for neural simulation.
  Offers built-in parallelization, compilation, and batch/cluster simulation
  management.](https://dynasim.github.io/)
- [GENESIS / PGENESIS - Longstanding platform for neural
  simulation](http://www.genesis-sim.org/)
    - [NeuroSpaces - A modular implementation of GENESIS
      components](http://neurospaces.sourceforge.net/)
- [LFPy - Local Field Potential simulator meant for use with NEURON
  models](https://lfpy.readthedocs.io/en/latest/)
- [MOOSE - Multiscale Object-Oriented Simulate
  Environment](https://moose.ncbs.res.in/) (Not to be confused with this [Moose
  Simulator](https://www.youtube.com/watch?v=axtA_Bls1ag&t=11s))
- [NEF - Neural Engineering Framework](http://compneuro.uwaterloo.ca/research/nef.html)
- [Nengo - Large-scale neural simulator](https://www.nengo.ai/)
- [NEST - A popular, actively developed neural simulator that can simulate
  large neural systems](http://www.nest-simulator.org/)
- [NEURON - Potentially the most popular computational neuroscience model
  simulator](https://neuron.yale.edu/neuron/)
- [NeuroRD - "A computationally efficient, stochastic reaction-diffusion
  simulator".](http://krasnow1.gmu.edu/CENlab/software.html)
- [PyRhO - Virtual laboratory for optogenetic simulation. Integrates with
  NEURON and Brian2 models.](https://github.com/ProjectPyRhO/PyRhO)
    - [Prometheus - Related docker image for use with PyRhO via "Modelling as a
      Service"](https://github.com/ProjectPyRhO/Prometheus)
- [PSICS - Parallel Stochastic Ion Channel Simulator](http://www.psics.org/)
- [PCSIM - Parallel neural Circuit SIMulator](http://www.lsm.tugraz.at/pcsim/)
  (The successor to [CSIM](http://www.lsm.tugraz.at/csim/))
- [PyNN - Language for building neuronal network models meant for export to
  other simulators](http://neuralensemble.org/docs/PyNN/0.7/)
- [Spike - "A high speed Spiking Neural Network Simulator designed for
  GPGPUs".](http://oftnai.github.io/Spike/)

##### Auxiliary Simulator Software

- [BluePyOpt - Blue Brain Python Optimisation Library, for optimizing
  parameters in neural models](https://github.com/BlueBrain/BluePyOpt)
- [GIMBL-Vis - Multi-dimensional visualization toolbox; integrates with
  DynaSim](https://github.com/erik-roberts/GIMBL-Vis)
- [Lancet - Software for managing large volumes of neural
  simulations](http://ioam.github.io/lancet/)
- [neuroConstruct - Software for developing biologically realistic 3D neural
  networks geometries, for simulation by NEURON, PyNN,
  etc.](http://www.neuroconstruct.org/)
- [Neurofitter - Parameter tuning software for electrophysiological neural
  models like NEURON](http://neurofitter.sourceforge.net)
- [neuroHDF - HDF5 data format for
  neuroscience](https://neurohdf.readthedocs.io/en/latest/)
- [NeuroTools - Collection of tools for "simulation setup, parameterization,
  data management, analysis, and visualization" for many neural simulators
  above.](https://pythonhosted.org/NeuroTools/)
- [NSDF - Neuroscience Simulation Data Format, built on
  HDF5](https://github.com/nsdf/nsdf)
- [pypet - Python parameter exploration toolkit for managing parameter sweeps
  of simulations in neural simulators like Brian. Has Sumatra
  integration.](http://pypet.readthedocs.io/en/latest/)
- [Sumatra - An "automated electronic lab notebook" for managing simulation and
  analysis projects](http://neuralensemble.org/sumatra/)

### Open Courses

- [Computational Neuroscience at
  Coursera](https://www.coursera.org/learn/computational-neuroscience)
- [Computational Neuroscience: Neuronal Dynamics of Cognition at edX](https://www.edx.org/course/computational-neuroscience-neuronal-dynamics-of-cognition)
- [Neuronal Dynamics at
  edX](https://www.edx.org/course/neuronal-dynamics-epflx-bio465-1x)
    - [The open book for this course is available here](http://neuronaldynamics.epfl.ch/online/index.html)
- [Neuroscience course material from OpenCourseWare (OCW) at MIT Department of Brain and Cognitive Sciences - HUGE list!](https://ocw.mit.edu/courses/brain-and-cognitive-sciences/)
- [Simulation Neuroscience at edX](https://www.edx.org/course/simulation-neuroscience-epflx-simneurox)
- [Interactive webpage illustrating spiking neural models](http://jackterwilliger.com/biological-neural-networks-part-i-spiking-neurons/)

### Open Data

- This only lists neuroscience-specific open data repositories. For general
  science data repositories that may contain neuroscience data like
  [re3data](https://www.re3data.org/search?query=neuroscience), [see this Open
  Science Resources
  page](https://github.com/asoplata/open-science-resources#open-data-repositories-and-services)
- [3D Brain Atlas Reconstructor](http://www.3dbars.org/)
- [Allen Brain Atlas Data Portal](http://brain-map.org/)
    - [More detail
      here](http://www.alleninstitute.org/what-we-do/brain-science/research/products-tools/)
    - [Associated software here](http://alleninstitute.github.io/AllenSDK/)
- [BODB - Brain Operation Database System](http://bodb.usc.edu/bodb/)
- [Brain Slices- Repository of brain tissue images](https://brainslices.org/)
- [C-BIG - Biological Imaging and Genetic
  repository](http://www.mcgill.ca/c-bigneuro/)
- [Channelpedia - Wiki of neuron ion channels, hosted by the Blue Brain
  Project](http://channelpedia.epfl.ch/)
- [CRCNS - Collaborative Research in Computational
  Neuroscience](http://crcns.org/data-sets)
- [GIN - Modern Research Data Management for Neuroscience](https://web.gin.g-node.org/)
- [IDA LONI - Image and Data Archive for neuroscience by Laboratory of Neuro
  Imaging](https://ida.loni.usc.edu/login.jsp)
- [INDI - International Neuroimaging Data-Sharing
  Initiative](http://fcon_1000.projects.nitrc.org/)
- [iEEG.org - National Institutes of Neurological Disorders and Stroke EEG data
  repository for epilepsy research](https://www.ieeg.org/)
- [NCBI databases - National Center for Biotechnology Information database
  list, VERY comprehensive!](http://www.ncbi.nlm.nih.gov/guide/all/)
- [NDA - National Institute of Mental Health Data
  Archive](https://data-archive.nimh.nih.gov/)
- [NeuroVault - Public repository of MRI and PET statistical maps,
  parcellations, and atlases](https://neurovault.org/)
- [NIF - Neuroscience Information Framework, massive search engine for
  neuroscience data, tools, etc.](http://www.neuinfo.org/)
- [NITRC - NeuroImaging Tools and Resources
  Collaboratory](https://www.nitrc.org/)
- [NMC - Neocortical Microcircuit Collaboration, part of Blue
  Brain](https://bbp.epfl.ch/nmc-portal/welcome)
- [NWB - Neurodata Without Borders - A standardized format for
  electrophysiological, and in the future other, neuroscience data. Some data
  sets available on the site in this format.](http://nwb.org/)
- [OpenNeuro - Free and open platform for neuroimaging data (succeeds
  OpenfMRI)](https://openneuro.org/)
- [Whole Brain Catalog - Virtual catalog of a mouse
  brain](https://library.tmc.edu/website/whole-brain-catalog/)
- [WormBase - Database of nematode information](https://www.wormbase.org)
- [ZFIN - Zebrafish Model Organism Database](http://zfin.org/)

##### Open Model Repositories

- [BioModels - Not neuroscience-specific](https://wwwdev.ebi.ac.uk/biomodels/)
- [ModelDB - Repository of computational neuroscience models for
  simulation](https://senselab.med.yale.edu/modeldb/), built by
  [Senselab](https://senselab.med.yale.edu/)
- [Senselab](https://senselab.med.yale.edu/) hosts several other databases, but
  ModelDB is the most popular:
    - [CellPropDB - Cellular Properties Database provides a simple repository
      for data regarding membrane channels, receptor and neurotransmitters that
      are expressed in specific types of
      cells.](https://senselab.med.yale.edu/CellPropDB/)
    - [NeuronDB - Provides a dynamically searchable database of three types of
      neuronal properties: voltage gated conductances, neurotransmitter
      receptors, and neurotransmitter
      substances.](https://senselab.med.yale.edu/NeuronDB/)
    - [MicrocircuitDB - Provides an accessible location for storing and
      efficiently retrieving realistic computational models of brain
      microcircuits and
      networks.](https://senselab.med.yale.edu/MicroCircuitDB/)
    - [3DModelDB  - A collection of 3D printable versions of published neuron
      morphologies, both traced and
      artificial.](https://senselab.med.yale.edu/3DModelDB/)
    - [ORModelDB - A resource that is a repository of the results of the
      efforts of the community is computationally elucidating the structure of
      the olfactory receptor with a view to establishing a mechanistic basis
      for OR-odorant binding.](https://senselab.med.yale.edu/OrModelDB/)
    - [OdorMapDB - Olfactory Bulb Odor Map
      DataBase](https://senselab.med.yale.edu/OdorMapDB/)
    - [OdorDB - Odor Molecules DataBase](https://senselab.med.yale.edu/OdorDB/)
    - [ORDB - Olfactory Receptor DataBase](https://senselab.med.yale.edu/OrDB/)
- [NeuroElectro - Repository of data-mined and human-curated neuron celltype
  electrophysiological data](https://neuroelectro.org/)
- [NeuroMorpho - Curated repository of digitally reconstructed neuron
  geometries](http://neuromorpho.org/)
- [OSB - Open Source Brain](http://www.opensourcebrain.org/)
- [OpenWorm - Popular platform for simulation and analysis of nematode
  neuroscience models!](http://openworm.org/)
- ["Integrated Models" RRID on SciCrunch - Compilation of model
  sources](https://scicrunch.org/scicrunch/Resources/record/nlx_144509-1/SCR_001481/resolver)

### Open Textbooks

- [Computational Cognitive
  Neuroscience](https://grey.colorado.edu/CompCogNeuro/index.php/CCNBook/Main)
- [Encyclopedia of Computational Neuroscience at
  Scholarpedia](http://www.scholarpedia.org/article/Encyclopedia_of_computational_neuroscience)
- [Neuronal Dynamics: From single neurons to networks and models of
  cognition](http://neuronaldynamics.epfl.ch/)

### Organizations and Communities

- [CodeNeuro - Bringing neuroscience and data science together](http://codeneuro.org/)
- [CNS - Organization for Computational Neuroscience](http://www.cnsorg.org/)
- [G-NODE - German Informatics Node](http://www.g-node.org/)
- [INCF - International Neuroinformatics Coordinating
  Facility](https://www.incf.org/about)
- [NeuralEnsemble, focused on software development in
  neuroscience](http://neuralensemble.org/)
- [Neuroinformatics Research Group at Harvard](http://neuroinformatics.harvard.edu/)
- [Neurostars - Neuroscience Q and A website](https://neurostars.org/)
- [NIMH - National Institute of Mental
  Health](https://www.nimh.nih.gov/index.shtml)
- [An Open Computational Neuroscience list I've made on
  Twitter](https://twitter.com/austinsoplata/lists/opencompneuroscience)
- [Organization for Human Brain Mapping](https://www.humanbrainmapping.org)
- [Reddit /r/Neuroscience
  resources](https://www.reddit.com/r/neuroscience/comments/2u87cl/rneuroscience_resource_compilaton/)
- [SFN - Society for Neuroscience](https://www.sfn.org/)
