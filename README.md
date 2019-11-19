# TAXONS

Task Agnostic eXploration of Outcome spaces through Novelty and Surprise.

This is the code of the paper: [Unsupervised Learning and Exploration of Reachable Outcome Space
](https://arxiv.org/abs/1909.05508)
---

This is the containerized version of the TAXONS codebase. This way there is no need to install any dependency.
**It requires [Singularity](https://sylabs.io/docs/)**

For the non containerized version, visit: https://github.com/GPaolo/taxons

Once dowloaded it, unpack it into a `sandbox` and access it by running:
```
sudo singularity build --sandbox taxons taxons.sif
sudo singularity shell --nv -w -c -W ./taxons/home/ taxons
```

To run the code do:
```
cd /home/taxons
python script/train.py
```

The parameters are in the file: `/home/taxons/script/parameters.py`
