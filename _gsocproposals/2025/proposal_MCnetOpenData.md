---
title: MCnet/OpenData - tools and exercises for open-data exploration with MC simulations
layout: gsoc_proposal
project: MCnet
year: 2025
organization:
  - UofGlasgow
  - UCLondon
difficulty: medium
duration: 175
mentor_avail: June-October
project_mentors:
  - email: andy.buckley@cern.ch
    organization: CERN
    first_name: Andy
    last_name: Buckley
    is_preferred_contact: yes
  - email: chris.g@cern.ch
    organization: CERN
    first_name: Chris
    last_name: Gutschow
---

# Description

CERN's experiments are committed to publishing their data in a form that
is accessible to all, both for research purposes and for education. For
example, the ATLAS experiment provides Jupyter notebook exercises based
on live-analysing reduced forms of the real collider data.

But particle-physics researchers also use _simulations_ of data as a
crucial tool for testing theories and for understanding the background
processes that new physics effects have to be isolated from. For this
we use Monte Carlo (MC) event-generator codes, which are statistical
implementations of the fundamental physics theory that sample
real-looking events from the predicted particle types and
kinematics. These are not yet represented in open-data exercises.

## Task ideas

In this project we will develop new tools and exercises for extending
open-data analysis resources to include MC event simulations. It will
both reduce the entry barriers to outreach with open data and enable more
engaging exercises with hypothetical new-physics models.

## Expected results and milestones

 * Develop a library of wrapper functions to make open-data analysis more approachable for non-experts.
 * Create functions and datasets for loading and analysing MC event samples through Jupyter.
 * Develop a new Jupyter+Binder worksheet for outreach-oriented open-data MC analysis.
 
## Requirements

 * Python
 * Jupyter
 * Binder
 * Gitlab CI
 * git

## Links

 * [ATLAS open data](https://atlas.cern/Resources/Opendata)
 * [Jupyter](https://jupyter.org/)
 * [Binder](https://mybinder.org/)
