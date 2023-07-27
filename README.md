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

This repo can be installed on Eclipse by following these steps:
1. Go to *Help* > *Install New Software...*
2. Select *Add*
3. In the location, enter [https://loonwerks.github.io/AGREE-Updates](https://loonwerks.github.io/AGREE-Updates), or specify a specific release or snapshot (e.g., [https://loonwerks.github.io/AGREE-Updates/releases/2.10.0](https://loonwerks.github.io/AGREE-Updates/releases/2.10.0)) and press *Add*
4. Make sure the box *Contact all update sites during install to find required software* is unchecked
5. Check the desired software, click *Next >*, and finish the rest of the install according to the prompts
