
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

## Other good online DS&A materials

- [Crafting Interpreters - Hash Tables (Nystrom)](https://craftinginterpreters.com/hash-tables.html): This is actually quite a nice and thorough but still accessible 
textbook-like approach to the subject (uses C for the example code). This is actually 
a really nice and modern treatment. It's part of a book about programming language 
design, so too bad it is not from a  DS&A book. Could be a good opportunity to follow 
this lead and do a whole DS&A book in this style.
- [Visu**algo** Hash table](https://visualgo.net/en/hashtable/print): A direct link to
all the text contained in the E-Learning interactive part of this page, very concise,
good details but terse.
- [Grokking Algorithms (Bhargava)](https://livebook.manning.com/book/grokking-algorithms-second-edition): This is a very fun and accessible book about
algorithms that uses drawings and a conversational style to illustrate concepts.
It's really fun to read, maybe a little 'light' overall, but students might like it.

## DS&A in python
- [A nice list of phython DS&A books](https://pythonbooks.org/topical-books/algorithm-and-data-structure/)
- [Data Structures and Algorithms in Python by Goodrich, Tamassia, & Goldwasser](https://www.wiley.com/en-us/Data+Structures+and+Algorithms+in+Python%2C+1st+Edition-p-9781118290279) [pdf](https://nibmehub.com/opac-service/pdf/read/Data%20Structures%20and%20Algorithms%20in%20Python.pdf):
Seems like a pretty solid and standard DS&A book. Hash table description starts on page 410.
- [Fundamentals of python: Data Structures by Lambert](https://lambertk.academic.wlu.edu/files/publications/python/cs2pythonv2/TOC.pdf)
- [Data Structures and Algorithms with Python (Springer 2014)](https://kentdlee.github.io/CS2Plus/build/html/index.html):
Pretty old fashioned.
- [Data Structures and Algorithms (github)](https://github.com/shushrutsharma/Data-Structures-and-Algorithms-Python?tab=readme-ov-file):
A textbook-like collection of python code implementing several different data structures. Not comprehensive.

## Hash table visualizations

- [Visu**algo** Hashtable](https://visualgo.net/en/hashtable?slide=1): Very fancy. Has a built in lesson
that is quite extensive. Exploration mode is excellent. Developed by National Univ. Singapore. A huge
amount of other data structures are covered with similarly cool visualization. Worth looking at.
- [Open Hashing (SF State)](https://www.cs.usfca.edu/~galles/visualization/OpenHash.html): Implements
mod 13 hashing, it's cool but you have to add one element at a time by hand, maybe useful.
- [Hashing Visualization (ACM)](https://iswsa.acm.org/mphf/openDSAPerfectHashAnimation/perfectHashAV.html):
Can choose your hash function and collision resolution policy, maybe good for illustrating linear
probing. Has a bunch of other stuff not covered in the book.
- [Virtual Labs - Hash Tables](https://virtual-labs.github.io/exp-hashtables-iiith/index.html): Less
a visualization platform and more of a self-guided learning platform (developed by the Ministry of Education
of the Government of India, wow!). It actually does have some interactive parts under the 'Practice' left-navs.

## Getting Java working with Jupyter notebooks
It turns out there are not too many options for running java kernels in jupyter.
I messed with this for a long time and never got satisfactory results, mostly
because I wanted students to do some easy plotting and this is impossible in Java. 
I did get a java jupyter kernel working though, with some trial and error:

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

