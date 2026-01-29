# Assume-Guarantee REasoning Environment (AGREE)

The Assume Guarantee REasoning Environment (AGREE) is a compositional,
assume-guarantee-style model checker for [AADL](https://aadl.info)
models. It is compositional in that it attempts to prove properties
about one layer of the architecture using properties allocated to
subcomponents. The composition is performed in terms of assumptions
and guarantees that are provided for each component. Assumptions
describe the expectations the component has on the environment, while
guarantees describe bounds on the behavior of the component. AGREE is
integrated into the [OSATE](https://osate.org) AADL model development
environment and uses k-induction as the underlying algorithm for the
model checking.

## User Guide

The user's guide for AGREE, including description of the plug-in for
OSATE, assume-guarantee concepts, specification language reference
manual, and examples is contained in the in-tool help.  The source
code for the help documentation is contained in the
com.rockwellcollins.atc.agree.doc project.

## Development Guide

See the main [AGREE](https://github.com/loonwerks/AGREE.git)
repository for information regarding developing and maintaining AGREE.

## Installing AGREE in OSATE

AGREE can be installed on Eclipse by following these steps:
1. Go to *Help* > *Install Additional OSATE Components*
2. Scroll down and select the *AGREE* checkbox, then click *Finish*
3. Click through the install wizard according to the prompts.  You may be asked to trust AGREE content.
4. OSATE will need to be restarted for changes to take effect.
