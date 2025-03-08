---
---


# Course website dev notes


## Building this website

Clone the repo with recursive option to ensure cloning of the revealjs submodule within,
or if the repo is already cloned, then just init the submodules
```bash
# clone w/ submodules
git clone --recurse-submodules git@github.com:eaton-lab/hack-the-planet.git

# or, init the submodules
#git submodule update --init --recursive
```

Install mkdocs-material into your current environment.
```bash
conda install mkdocs-material -c conda-forge
```

Move into the repo directory alongside mkdocs.yml and build locally with `mkdocs`. 
Changes to the repo will now automatically update in the website being served
to localhost:8000. 
```bash
mkdocs serve
```


## Editing the site

Currently the old class structure is still present in the `old-docs` directory. Parts of this
can be updated and moved to the new `docs/` directory to be integrated into the new site. 

## Other useful programming for biologists courses
- [Computing Skills for Biologists (Allesina & Wilmes; the most up-to-date and nice)](https://computingskillsforbiologists.com/downloads/exercises/#scientific)
- [Python for Biologists](https://www.pythonforbiologists.org/)
- [Programming for Biologists (Ethan White)](https://www.programmingforbiologists.org/)
- [Data Science for Biologists (UW)](https://github.com/eleanorlutz/Data_science_for_biologists_2019/tree/main)

