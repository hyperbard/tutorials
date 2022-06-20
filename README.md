# tutorials
Tutorials demonstrating how to work with Hyperbard data.
<br/>
Can be run locally or remotely in a Binder.
<br/>
WIP. Feature requests welcome.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hyperbard/sandbox/main?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Fhyperbard%252Ftutorials%26urlpath%3Dlab%252Ftree%252Ftutorials%252Fnotebooks%252Fwelcome.ipynb%26branch%3Dmain)

## Running Tutorials with Binder
To run the tutorials remotely with Binder, click the launch button above. 
<br/>
This will open a new window in your browser and do the following:
1. Allocate cloud resources from the distributed [Binder infrastructure](https://mybinder.readthedocs.io/en/latest/) to run your instance of the tutorials.
2. If needed, build and register a current docker image of our [sandbox environment](https://github.com/hyperbard/sandbox). 
3. Pull the current docker image onto the assigned machine and create an instance of the sandbox environment from it.
4. Pull the current content of the [tutorials repository](https://github.com/hyperbard/tutorials) into the sandbox environment.
    > Separating environment and content repositories conserves resources and improves startup times when the content evolves while the environment remains fairly static; see [this discussion](https://discourse.jupyter.org/t/how-to-reduce-mybinder-org-repository-startup-time/4956).
5. Redirect you to the [welcome notebook](https://github.com/hyperbard/tutorials/blob/main/notebooks/welcome.ipynb) in the notebooks folder of the tutorials.

The entire process should take approximately 30 seconds (plus the time to build a new docker image of the sandbox, if you are unlucky).

For a smooth tutorial experience, please unpack the data provided with the tutorial repository as described in the [welcome notebook](https://github.com/hyperbard/tutorials/blob/main/notebooks/welcome.ipynb). 
We deliberately do not use a post-build hook to download and unpack the data for efficiency reasons.

Note that your Binder instance will be shut down after 10 minutes of inactivity; see [the official documentation](https://mybinder.readthedocs.io/en/latest/about/user-guidelines.html) for details on what counts as inactivity.

## Related Artifacts
[![arXiv](https://img.shields.io/badge/arXiv-2206.08225-b31b1b.svg?style=flat)](https://arxiv.org/abs/2206.08225)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6627158.svg)](https://doi.org/10.5281/zenodo.6627158)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6627160.svg)](https://doi.org/10.5281/zenodo.6627160)

## Related Repositories
- [hyperbard Code](https://github.com/hyperbard/hyperbard)
- [hyperbard Binder Sandbox](https://github.com/hyperbard/sandbox)