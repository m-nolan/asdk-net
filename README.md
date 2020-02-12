# asdk-net

2020.02.11

### Network signal inference from AllenSDK visual stimulus response data

#### Getting Started
##### Installation
There a few packages that you need to install to get going with this codebase. I've set up an anaconda environment to handle package installation and dependecy management. Use that to ease installation and keep everyone on the same page.

First, clone the repo:
`git clone https://github.com/m-nolan/asdk-net.git`

Then, create a new anaconda environment. If you have not installed anaconda, check out miniconda for a light distribution: [miniconda](https://docs.conda.io/en/latest/miniconda.html)

If you're using a mac, use homebrew to install anaconda:
`brew install miniconda`

Once you have anaconda installed, create the conda environment:
`conda env create -f environment.yml`

##### Tutorial
Check out `AIBS\ Ephys\ Data\ Load.ipynb` to get started with accessing the allensdk. This should provide a good framework for building our data access code.
