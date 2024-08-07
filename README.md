# test-energyplus-install-action

[![.github/workflows/test_action.yml](https://github.com/Myoldmopar/test-energyplus-install-action/actions/workflows/test_action.yml/badge.svg)](https://github.com/Myoldmopar/test-energyplus-install-action/actions/workflows/test_action.yml)

A demonstration repository for using the [Myoldmopar/energyplus-install](https://github.com/Myoldmopar/energyplus-install) GitHub Action.  For now this simply:
- uses the action to grab an appropriate EnergyPlus package
- runs a sample EnergyPlus input file
- installs the [energyplus-api-helpers](https://pypi.org/project/energyplus-api-helpers/) Python Package
- runs a simple main.py script which utilizes the EnergyPlus API to do a basic simulation run

This repo exercises this on several different CI images across all three platforms.
