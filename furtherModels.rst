.. _tutorialFurtherModels:

Further models to explore
=========================

In this part of the tutorial we look at exploring and sharing several more models that may be of interest. You need to make sure you have completed the :ref:`preparation <tutorialPreparation>` and :ref:`sharing <tutorialSharing>` sections before embarking on this section.

The Hill model with serial damping
----------------------------------

In a similar manner as the Hill model with parallel damping, we are about to work with a Hill model which contains serial damping. We have provided another :term:`workspace` containing a new Hill model at: http://teaching.physiomeproject.org/workspace/2b6. As with the :ref:`previous section <tutorialSharing>`, you should :term:`fork` this workspace and make a local copy of the workspace using OpenCOR.

The basic Hill model with added serial damping is shown in :numref:`isb2017_hill_sdash_model`.

.. Figure:: resources/Dig_sDash.png
   :name: isb2017_hill_sdash_model
   :alt: Schematic of the basic Hill model with series damping.
   :align: center
   :width: 40%
   
   Schematic illustration of the Hill model with an additional series damping element we are using in this part of the tutorial. The model is described in the CellML document :file:`Hill_Basic_sDash.cellml` and a prepared simulation experiment in :file:`Hill_Basic_sDash.sedml`.

Running the prepared simulation experiments for the Hill model with either parallel and series damping will hopefully result in clearly observable damping behaviour. As described in :ref:`tutorialSharing`, explore these models and try out the functionality of OpenCOR. As you work, be sure to keep things synchronised with PMR, **making sure you use descriptive messages when synchronising changes so that you can keep track of your work.**

If you would like to test how well you document your changes, try sharing your workspace with your neighbour and seeing if they are able to work out what you changed just from your workspace history.

A pendulum encoded in CellML
----------------------------

In addition to models like the Hill model, it is also possible to follow the same methods to develop models capturing kinematics. We provide another workspace, http://teaching.physiomeproject.org/workspace/2b5, in which a model of a pendulum is provided. This model is similar to that given in Section 3.4 of the full bond graph tutorial provided on the :ref:`main index <IUPS_2017-index>` page and reproduced in :numref:`isb2017_bg_pendulum_model` for convenience.

.. Figure:: resources/pendulum-model.png
   :name: isb2017_bg_pendulum_model
   :alt: Schematic of the spring-mass pendulum.
   :align: center
   :width: 40%
   
   Schematic illustration of a spring-mass pendulum and the associated bond-graph based derivation of the model. The model is provided in the CellML model :file:`BG tutorial model solid mechanics 3.cellml` and a prepared simulation experiment in :file:`BG tutorial model solid mechanics 3.sedml`.
   
As above, create your own fork of this workspace and local copy of the workspace to explore.



