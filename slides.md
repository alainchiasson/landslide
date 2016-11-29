# Landslide Docker Wrapper

Using landslide without polluting your system

---

# What is landslide

[Landslide](https://github.com/adamzap/landslide) is a python
application used to Generate HTML5 slideshows from markdown, ReST, or textile.

Landslide is primarily written in Python, but it's themes use HTML5, Javascript
, CSS

It requires the installation of numerous python packages that may pollute your
development space.
---
# Why The Docker image

This docker image contains everything required to perform the transformation

It also includes an installable wrapper script to simplify the use.

---

# Using the Docker image

To use the docker image:

    !bash
    docker run -it --rm -v `pwd`:/mnt \
    -w /mnt alainchaisson/landslide landslide -i file

- mount the current directory under /mnt
- set /mnt as the container working directory
- `file` is the source file
- the `-i` option create a standalone slide presentation
- creates a `presentation.html` file in the working directory
- The working directory is mapped to the local directory

---

# gen_slides wrapper

To simplify, there is a wrapper script called `gen_slides`:

    !bash
    gen_slides slides.md

This will create the `presentaion.html` file in the current directory


---

# Additional information

- Landslide : https://github.com/adamzap/landslide
- Landslide container : https://github.com/alainchiasson/landslide
- Docker hub Container : https://hub.docker.com/r/alainchiasson/landslide/

Contact information : alain@chiasson.org
