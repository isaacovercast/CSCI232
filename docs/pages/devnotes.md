
# Course website dev notes


## Building this website

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

## Getting Java working with Jupyter notebooks
It turns out there are not too many options for running java kernels in jupyter.
Ultimately I ended up using 

- [IJava](https://github.com/SpencerPark/IJava): I ended up using this because it was simple
to install (`conda install -c conda-forge ijava`) and it seemed to 'work', but it has few
features and is not actively maintained.
- [awesome-jupyter-java](https://github.com/jupyter-java/awesome-jupyter-java) maintains
a list of kernels (both active and inactive)
- [Kotlin-jupyter](https://github.com/Kotlin/kotlin-jupyter?tab=readme-ov-file#readme) seems
promising, as kotlin is designed to be backwards compatible with java, so the algs4 code should
work, and also it could give access to more plotting functionality.
- [ganymede](https://github.com/allen-ball/ganymede) & [rapaio](https://github.com/padreati/rapaio-jupyter-kernel/tree/main)
also both seemed promising, but supported by individuals so maybe not robust in the long term.
- The JetBrains team maintains a [lets-plot](https://github.com/JetBrains/lets-plot?tab=readme-ov-file)
implementation which works with Kotlin, and theoretically could work in jupyter notebooks
but I never got that far.

## Materials from past courses
- [CSCI 232 Spring 2024 - Syllabus](https://www.cs.montana.edu/pearsall/classes/spring2024/232/syllabus.html)
- [CSCI 232 Spring 2024 - Class Schedule](https://www.cs.montana.edu/pearsall/classes/spring2024/232/main.html)
- [CSCI 232 Fall 2021](https://scholarworks.umt.edu/cgi/viewcontent.cgi?article=13106&context=syllabi)

