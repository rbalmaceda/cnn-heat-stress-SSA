## Software environment

The notebook was developed and tested on Rocky Linux 8.10
using R 4.3.3 and the `cnn-hs` Micromamba environment.

The environment includes Python, TensorFlow, Keras,
and the R packages required for climate data processing
and CNN training.

To recreate the environment:

```bash
micromamba create -f environment.yml
micromamba activate cnn-hs
