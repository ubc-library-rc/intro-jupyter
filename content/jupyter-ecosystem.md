---
layout: default
title: The Jupyter Ecosystem
nav_order: 4
has_parent: Introduction
---
# The Jupyter Ecosystem

Jupyter notebooks are the most widely used type of computational notebook though they are not the only option out there.

* [Jupyter](https://jupyter.org/index.html)

  * From the Jupyter website:
    "Project Jupyter is a non-profit, open-source project, born out of the IPython Project in 2014 as it evolved to support interactive data science and scientific computing across all programming languages. Jupyter will always be 100% open-source software, free for all to use and released under the liberal terms of the modified BSD license."

  * You can try Jupyter without logging in anywhere [in-browser here](https://jupyter.org/try). You'll notice that Jupyter supports a lot of different programming languages though it was originally build around Python.

  * Alternately you can install Jupyter locally. If you do this you will run a local web server (set up by Jupyter) and your work will be fully contained on your computer. This is especially useful for sensitive work that needs to stay on a lab machine. You can always share a notebook at a later date.

* [JupyterLab](https://jupyter.org/)

  * From the Jupyter website:
    "JupyterLab is a web-based interactive development environment for Jupyter notebooks, code, and data. JupyterLab is flexible: configure and arrange the user interface to support a wide range of workflows in data science, scientific computing, and machine learning. JupyterLab is extensible and modular: write plugins that add new components and integrate with existing ones."

  * Essentially a newer model of Jupyter notebooks.

  * For members of the UBC community one way to access a JupyterLab instance is through [UBC Syzygy](https://ubc.syzygy.ca/).

* [JupyterHub](https://jupyter.org/hub)

  * From the JupyterHub website:
    "JupyterHub brings the power of notebooks to groups of users. It gives users access to computational environments and resources without burdening the users with installation and maintenance tasks. Users - including students, researchers, and data scientists - can get their work done in their own workspaces on shared resources which can be managed efficiently by system administrators.

    JupyterHub runs in the cloud or on your own hardware, and makes it possible to serve a pre-configured data science environment to any user in the world. It is customizable and scalable, and is suitable for small and large teams, academic courses, and large-scale infrastructure."

  * UBC Syzygy is an example of a JupyterHub that spins up JupyterLabs for everyone who logs in.

## Sharing with others
* .ipynb files can be shared through any file sharing system same as any other type of file format
* Github will pre-load a Jupyter notebook automatically though as a static representation
  * See example here:
