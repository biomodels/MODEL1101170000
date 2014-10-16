# MODEL1101170000: Nakano2010_Synaptic_Plasticity

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1101170000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1101170000.git@20140916`

## Usage

Importing the model package.

`import MODEL1101170000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is an SBML version of the model described in: **A kinetic model of
dopamine- and calcium-dependent striatal synaptic plasticity.**  
Nakano T, Doi T, Yoshimoto J, Doya K. PLoS Comput Biol. 2010 Feb
12;6(2):e1000670. PMID:
[20169176](http://www.ncbi.nlm.nih.gov/pubmed/20169176) ; DOI:
[10.1371/journal.pcbi.1000670](dx.doi.org/10.1371/journal.pcbi.1000670)

Abstract:  
Corticostriatal synapse plasticity of medium spiny neurons is regulated by
glutamate input from the cortex and dopamine input from the substantia nigra.
While cortical stimulation alone results in long-term depression (LTD), the
combination with dopamine switches LTD to long-term potentiation (LTP), which
is known as dopamine-dependent plasticity. LTP is also induced by cortical
stimulation in magnesium-free solution, which leads to massive calcium influx
through NMDA-type receptors and is regarded as calcium-dependent plasticity.
Signaling cascades in the corticostriatal spines are currently under
investigation. However, because of the existence of multiple excitatory and
inhibitory pathways with loops, the mechanisms regulating the two types of
plasticity remain poorly understood. A signaling pathway model of spines that
express D1-type dopamine receptors was constructed to analyze the dynamic
mechanisms of dopamine- and calcium-dependent plasticity. The model
incorporated all major signaling molecules, including dopamine- and cyclic
AMP-regulated phosphoprotein with a molecular weight of 32 kDa (DARPP32), as
well as AMPA receptor trafficking in the post-synaptic membrane. Simulations
with dopamine and calcium inputs reproduced dopamine- and calcium-dependent
plasticity. Further in silico experiments revealed that the positive feedback
loop consisted of protein kinase A (PKA), protein phosphatase 2A (PP2A), and
the phosphorylation site at threonine 75 of DARPP-32 (Thr75) served as the
major switch for inducing LTD and LTP. Calcium input modulated this loop
through the PP2B (phosphatase 2B)-CK1 (casein kinase 1)-Cdk5 (cyclin-dependent
kinase 5)-Thr75 pathway and PP2A, whereas calcium and dopamine input activated
the loop via PKA activation by cyclic AMP (cAMP). The positive feedback loop
displayed robust bi-stable responses following changes in the reaction
parameters. Increased basal dopamine levels disrupted this dopamine-dependent
plasticity. The present model elucidated the mechanisms involved in
bidirectional regulation of corticostriatal synapses and will allow for
further exploration into causes and therapies for dysfunctions such as drug
addiction.

The model was encoded from the supplemental material accompanying the article.  
The stimuli used in the article are hard to implement in SBML, so right now
the model does not reproduce the results given in the article.

Originally created by libAntimony v1.4 (using libSBML 3.4.1)

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


