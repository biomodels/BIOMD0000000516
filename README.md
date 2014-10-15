# BIOMD0000000516: MODEL1401310003

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000516.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000516.git@20140916`


# Model Notes


Kerkhoven2013 - Glycolysis and Pentose Phosphate Pathway in T.brucei - MODEL D
in fructose medium (with ATP:ADP antiporter)

There are six models (Model A, B, C, C-fruc, D, D-fruc) described in the
paper. Model A (
[BIOMD0000000513](http://identifiers.org/biomodels.db/BIOMD0000000513) ) is
the model developed originally by Achar et al. (2012) (
[BIOMD0000000428](http://identifiers.org/biomodels.db/BIOMD0000000428) ),
which describes glycolysis in T.brucei. This glycolysis model is extended to
include pentose phosphate pathway (PPP), which is Model B ((
[BIOMD0000000514](http://identifiers.org/biomodels.db/BIOMD0000000514) ).
Model B is further extended to include glycosomal ribokinase, leading to Model
C ( [BIOMD0000000510](http://identifiers.org/biomodels.db/BIOMD0000000510) ).
Model D (
[BIOMD0000000511](http://identifiers.org/biomodels.db/BIOMD0000000511) ) is
again an extension of Model B, which includes an ATP:ADP antiporter. Model
C-fruc (
[BIOMD0000000515](http://identifiers.org/biomodels.db/BIOMD0000000515) ) and
Model D-fruc (
[BIOMD0000000516](http://identifiers.org/biomodels.db/BIOMD0000000516) ) are
extensions of Model C and D, respectively, which includes fructose transporter
and its subsequent utilizing reactions. This model correspond to Model D-fruc
of the paper.

This model is described in the article:

[Handling uncertainty in dynamic models: the pentose phosphate pathway in
Trypanosoma brucei.](http://identifiers.org/pubmed/24339766)

Kerkhoven EJ, Achcar F, Alibu VP, Burchmore RJ, Gilbert IH, Trybiło M,
Driessen NN, Gilbert D, Breitling R, Bakker BM, Barrett MP.

PLoS Comput Biol. 2013 Dec;9(12):e1003371.

Abstract:

Dynamic models of metabolism can be useful in identifying potential drug
targets, especially in unicellular organisms. A model of glycolysis in the
causative agent of human African trypanosomiasis, Trypanosoma brucei, has
already shown the utility of this approach. Here we add the pentose phosphate
pathway (PPP) of T. brucei to the glycolytic model. The PPP is localized to
both the cytosol and the glycosome and adding it to the glycolytic model
without further adjustments leads to a draining of the essential bound-
phosphate moiety within the glycosome. This phosphate "leak" must be resolved
for the model to be a reasonable representation of parasite physiology. Two
main types of theoretical solution to the problem could be identified: (i)
including additional enzymatic reactions in the glycosome, or (ii) adding a
mechanism to transfer bound phosphates between cytosol and glycosome. One
example of the first type of solution would be the presence of a glycosomal
ribokinase to regenerate ATP from ribose 5-phosphate and ADP. Experimental
characterization of ribokinase in T. brucei showed that very low enzyme levels
are sufficient for parasite survival, indicating that other mechanisms are
required in controlling the phosphate leak. Examples of the second type would
involve the presence of an ATP:ADP exchanger or recently described
permeability pores in the glycosomal membrane, although the current absence of
identified genes encoding such molecules impedes experimental testing by
genetic manipulation. Confronted with this uncertainty, we present a modeling
strategy that identifies robust predictions in the context of incomplete
system characterization. We illustrate this strategy by exploring the
mechanism underlying the essential function of one of the PPP enzymes, and
validate it by confirming the model predictions experimentally.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000516](http://identifiers.org/biomodels.db/BIOMD0000000516) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


