.. _tutorialFurtherModels:

Further models to explore
=========================

In this part of the tutorial we look at exploring and sharing several more models that may be of interest. You need to make sure you have completed the :ref:`preparation <tutorialPreparation>` and :ref:`sharing <tutorialSharing>` sections before embarking on this section.

The Hill model with damping
---------------------------

In a similar manner as the basic 3-element Hill model, we are about to build Hill models which contain damping. We have provided another :term:`workspace` containing two new Hill models at: http://teaching.physiomeproject.org/workspace/2b6. As with the :ref:`previous section <tutorialSharing>`, you should :term:`fork` this workspace and make a local copy of the workspace using OpenCOR.

The first example to explore is the basic Hill model with added parallel damping, as shown in :numref:`isb2017_hill_pdash_model`.

.. Figure:: resources/Dig_pDash.png
   :name: isb2017_hill_pdash_model
   :alt: Schematic of the basic Hill model with parallel damping.
   :align: center
   :width: 40%
   
   Schematic illustration of the Hill model with additional parallel damping element we are using in this part of the tutorial. The model is described in the CellML document :file:`Hill_Basic_pDash.cellml` and a prepared simulation experiment in :file:`Hill_Basic_pDash.sedml`.

.. Figure:: resources/Dig_sDash.png
   :name: isb2017_hill_sdash_model
   :alt: Schematic of the basic Hill model with series damping.
   :align: center
   :width: 40%
   
   Schematic illustration of the Hill model with an additional series damping element we are using in this part of the tutorial. The model is described in the CellML document :file:`Hill_Basic_sDash.cellml` and a prepared simulation experiment in :file:`Hill_Basic_sDash.sedml`.

Running the prepared simulation experiments for the Hill model with either parallel and series damping will hopefully result in clearly observable damping behaviour. As described in :ref:`tutorialSharing`, explore these models and try out the functionality of OpenCOR. As you work, be sure to keep things synchronised with PMR, **making sure you use descriptive messages when synchronising changes so that you can keep track of your work.**

If you would like to test how well you document your changes, try sharing your workspace with your neighbour and seeing if they are able to work out what you changed just from your workspace history.