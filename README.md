# BIOMD0000000246: vasalou2010

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000246.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000246.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000246 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This the single cell model from the article:  
**A multiscale model to investigate circadian rhythmicity of pacemaker neurons in the suprachiasmatic nucleus.**   
Vasalou C, Henson MA. _PLoS Comput Biol_ 2010 Mar 12;6(3):e1000706. PMID:
[20300645](http://www.ncbi.nlm.nih.gov/pubmed/20300645) , DOI: [10.1371/journa
l.pcbi.1000706](http://dx.doi.org/10.1371%2Fjournal.pcbi.1000706) ;

**Abstract:**   
The suprachiasmatic nucleus (SCN) of the hypothalamus is a multicellular
system that drives daily rhythms in mammalian behavior and physiology.
Although the gene regulatory network that produces daily oscillations within
individual neurons is well characterized, less is known about the
electrophysiology of the SCN cells and how firing rate correlates with
circadian gene expression. We developed a firing rate code model to
incorporate known electrophysiological properties of SCN pacemaker cells,
including circadian dependent changes in membrane voltage and ion
conductances. Calcium dynamics were included in the model as the putative link
between electrical firing and gene expression. Individual ion currents
exhibited oscillatory patterns matching experimental data both in current
levels and phase relationships. VIP and GABA neurotransmitters, which encode
synaptic signals across the SCN, were found to play critical roles in daily
oscillations of membrane excitability and gene expression. Blocking various
mechanisms of intracellular calcium accumulation by simulated pharmacological
agents (nimodipine, IP3- and ryanodine-blockers) reproduced experimentally
observed trends in firing rate dynamics and core-clock gene transcription. The
intracellular calcium concentration was shown to regulate diverse circadian
processes such as firing frequency, gene expression and system periodicity.
The model predicted a direct relationship between firing frequency and gene
expression amplitudes, demonstrated the importance of intracellular pathways
for single cell behavior and provided a novel multiscale framework which
captured characteristics of the SCN at both the electrophysiological and gene
regulatory levels.

Originally created by libAntimony v1.3 (using libSBML 4.1.0-b1)

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2010 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


