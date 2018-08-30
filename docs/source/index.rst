.. mantraml documentation master file, created by
   sphinx-quickstart on Thu Jul 19 11:05:32 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Mantra : A Deep Learning Development Kit
##########################################

.. image:: panda.png
   :width: 280px
   :align: left
   :scale: 50 %

**Mantra** is an open-source framework for building deep learning software. We turn your deep learning models into portable objects that can be seamlessly trained, evaluated, deployed, and more in a single step. 

With Mantra, you can focus your time on creating models rather than annoying engineering tasks. So ... let's get started!


🌍 Installation
**********************

Mantra is a Python 3 library. You can install via pip:

.. code-block:: console

   $ pip install mantraml

👍 Introducing the ML object
*******************************

.. Important::
   ML object is a key concept introduced in Mantra. An ML object:

   1. Represents a key ML artifacts, such as a dataset or model
   2. Consists of code, linked data files and metadata
   3. Takes a single step to track, train, evaluate, monitor, package and share

The goal of ML objects is to cover the whole lifecycle of datasets and models. Mantra is currently in alpha so some parts of the lifecycle might be missing, but will be coming soon!

🚀 Quick start with notebooks
*******************************

TODO (what could be a good use case here?)


🚀 Quick start with a Python project
***************************************

Find a directory where you want to create a project and run:

.. code-block:: console

   $ mantra launch my_project_name

This will create a **my_project_name** directory with a folder structure like this:

.. code-block:: console

   data/
   models/
   __init__.py
   mantra.yml
   README.md
   settings.py

- The :code:`data/` folder contains your datasets
- The :code:`models/` folder contains your models
- The :code:`mantra.yml` file contains project metadata
- The :code:`settings.py` file contains project settings

Now we have a project! But what does this mean, I hear you cry? Let's delve in and see what kind of deep learning magic Mantra can do... ✨. 


- 💾 `Get started with Mantra datasets <datasets.html>`_ 
- 🤖 `Get started with Mantra models <models.html>`_
- 🏃 `Get started with training <training.html>`_
- 🎁 `Get started with sharing <sharing.html>`_

.. toctree::
   :maxdepth: 2
   :hidden:

   datasets
   models
   training
   sharing
