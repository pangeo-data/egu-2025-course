# Instructions for building the website locally

The notebooks are intented to execute on [Pangeo@EOSC](https://pangeo-data.github.io/pangeo-eosc/), but you can preview website changes locally with the following commands:

```
git clone https://github.com/pangeo-data/egu-2025-course.git
cd egu-2025-course
mamba env create
mamba activate egu25
myst start --html --execute
```
