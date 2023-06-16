# Local SD+ControlNet `diffusers` workaround

This is a workaround for loading local SD+ControlNet models in this [related `diffusers` Issue](https://github.com/huggingface/diffusers/issues/3722)

### Local Setup That Worked (YMMV)

- A100 40GB
- CUDA 11.6
- python 3.10.8
- Specific library versions in [requirements.txt](requirements.txt)

Follow [the_notebook.ipynb](the_notebook.ipynb) for details.