Welcome to Xrayto3DShape-benchmark's documentation!
===================================

**Xrayto3DShape-benchmark** is a pytorch-based Python package for extensive benchmarking for Biplanar X-ray to 3D Shape Reconstruction. We aim to become a comprehensive benchmarking tool for developing and evaluating architectures specific to this problem. Currently, we provide tools to train and evaluate on 4 different bone anatomies using 6 publicly available datasets. We also define clinically relevant evaluation tasks such as domain shifts to evaluate the robustness of these methods. Currently, various Encoder-Decoder Architectures on volumetric grid-based representation are reimplemented and benchmarked. 

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::
   :maxdepth: 2

   
   Datasets Zoo <datasets>
   usage
   API<api>
