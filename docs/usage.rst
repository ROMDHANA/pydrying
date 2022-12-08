Usage
=====




Installation
------------


``pydrying``  runs under Python 3.6+. To install it with `pip`_, run the following:

.. _pip: https://pypi.org/project/pydrying/

.. code-block:: console

   pip install pydrying
   

Upgrade
-------


To upgrade it with `pip`_, run the following:

.. _pip: https://pypi.org/project/pydrying/

.. code-block:: console

   pip install --upgrade pydrying
   

Quickstart
----------

``pydring`` is a Python package developed for the simulation of industrial drying. The simulation programs are based on the multiphysical and dynamic modeling of drying phenomena (transfer of heat, mass and momentum, and deformation of the drying product). The resolution of the drying equations is based on the numerical method of finite volumes. This module calculates the drying kinetics of any solid product. Modeling drying kinetics is essential in most transformation processes, such as the food industry: sugar industry, biomass refinery, fodder processing, etc.

The following example presents the simulation of the air drying of a solid material arranged in a thin layer. This type of calculation is suitable for a belt dryer.

The problem definition involves 3 components:

- Properties of the solid material to be dried
- Properties of drying air
- Other drying conditions

