---
layout: default
title: PsyNeuView
permalink: /psyneuview/
redirect_from:
  - /psyneulink-view-2/
---

PsyNeuView is a visual environment for building, running and understanding PsyNeuLink models. A model written as code can be hard to see; PsyNeuView reads a PsyNeuLink script and draws the network it builds, so you can explore the model, run it, and watch values move through it.

With PsyNeuView you can:

- **See the model.** Open a `.py` file and PsyNeuView lays out its mechanisms and projections. The picture is read from the model your code actually builds.
- **Run it.** Give the input nodes values and run the model. Results come back trial by trial, paired with the inputs that produced them.
- **Step through execution.** Move through a run one step at a time and watch each node's value as it is computed.
- **Edit and re-run.** Change a parameter or edit the source, and the visualization rebuilds to match.

Models stay ordinary PsyNeuLink scripts that run without PsyNeuView. Ten reference models from the literature, including the Stroop model, come with it.

## Download

PsyNeuView is available as a Mac app for macOS 14 (Sonoma) or later on Apple silicon. The app installs and updates itself, and needs an internet connection the first time it runs.

- [Download page](https://jonhanke-nam.github.io/PsyNeuView-releases/)
- [Latest release](https://github.com/jonhanke-nam/PsyNeuView-releases/releases/latest)
- [All releases and release notes](https://github.com/jonhanke-nam/PsyNeuView-releases/releases)

## Source code

- [PsyNeuView](https://github.com/jonhanke-nam/PsyNeuView) on GitHub
- [PsyNeuView Mac app](https://github.com/jonhanke-nam/PsyNeuView-MacApp) on GitHub
