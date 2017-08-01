.. _tutorialSharing:

Sharing
=======

In this part of the tutorial we look at taking an existing model, having a play with it, and sharing it with our colleagues. You need to make sure you have completed the :ref:`preparation <tutorialPreparation>` before embarking on the following.

The Hill 3-element model with parallel damping
----------------------------------------------

.. Figure:: resources/Dig_Basic1.png
   :name: isb2017_sharing_basic_hill1_model
   :alt: Schematic of the basic 3-element Hill model.
   :align: center
   :width: 40%
   
   Schematic illustration of the initial 3-element Hill model.

For this tutorial we are working with various configurations of the fundamental Hill mechanics model, starting with the basic 3-element model shown in :numref:`isb2017_sharing_basic_hill1_model` we have developed a Hill model with parallel damping, as shown in :numref:`iups2017_sharing_hill_pdash_model`. The bond graph form of the model is shown in :numref:`iups2017_sharing_hill_pdash_bg`. We have prepared a starting point :term:`workspace` for you to begin with. In your browser, head over to http://teaching.physiomeproject.org/workspace/2b4 and :term:`fork` the workspace. This will create your own *private* copy of the workspace to use. Instructions for how to actually accomplish this are given at: :ref:`tut1forkingaworkspace`.

.. Figure:: resources/Dig_pDash.png
   :name: iups2017_sharing_hill_pdash_model
   :alt: Schematic of the basic 3-element Hill model.
   :align: center
   :width: 40%
   
   Schematic illustration of the Hill model with parallel damping we are using in this part of the tutorial. The model is located in the :file:`Hill_Basic_pDash.cellml`.

.. Figure:: resources/BG_pDash.png
   :name: iups2017_sharing_hill_pdash_bg
   :alt: The underlying bond-graph for the 3-element Hill model.
   :align: center
   :width: 20%
   
   The bond-graph representation underlying the Hill model.

If you now reload your workspaces in the :guilabel:`PMR Workspaces` panel in OpenCOR, you should see your newly created fork of the Hill model workspace. Following the same instructions as given in :ref:`cellml_opencor_pmr_tutorial__pmr_with_opencor`, you should now make a local copy of this workspace. If you load the CellML model :file:`Hill_Basic_pDash.cellml` you can explore the mathematics of this model in the :guilabel:`CellML Text` view in the :guilabel:`Editing` window. You can also switch to the :guilabel:`Simulation` window and try out running some simulations and creating plots of the results. Further assistance for running simulations is available here: :ref:`cellml_opencor_pmr_tutorial__first_model`.

Sharing simulation descriptions
-------------------------------

Once you have explored the model mathematics and played with simulations, you can then load the file :file:`Hill_Basic_pDash.sedml` into OpenCOR by double-clicking it. This is a SED-ML document.

.. note::

   `SED-ML <http://sed-ml.org>`_ is a standard for encoding descriptions of simulation experiments. OpenCOR makes use of SED-ML to serialise the various settings for simulations to be executed and graphs to be drawn, so that users are able to archive such information as well as share it.
   
Once the SED-ML file is loaded, you should be able to execute the simulation experiment and hopefully get something that looks similar to :numref:`isb2017_sharing_basic_hill1_results`. Since the SED-ML is directly referencing the CellML model you have been exploring above, exactly how close it matches will depend on how much you changed the :file:`Hill_Basic_pDash.cellml` CellML model. 

.. Figure:: resources/Hill_Basic_pDash_sedml.png
   :name: isb2017_sharing_basic_hill1_results
   :alt: Simulation results for Hill Basic1 model.
   :align: center
   :width: 75%
   
   The results from executing the simulation experiment described in :file:`Hill_Basic_pDash.sedml`.

If you are wondering what changes you might have introduced to the model you can make use of the :guilabel:`PMR Workspaces` widget to check for differences. If there are any differences, you should see little icon decorations in the file listing for this workspace and the :menuselection:`Synchronise Workspace With PMR...` menu option under the context-menu (right-click) should be available. If you then choose the :menuselection:`Synchronise Workspace With PMR...` you will be presented with a graphical summary of the changes that have been made.

**This illustrates how CellML and SED-ML can be used to archive and share a reproducible description of the model and simulation experiment.**

Sharing your customisations
---------------------------

To further demonstrate the sharing capabilities, go back to the :file:`Hill_Basic_pDash.cellml` CellML model and using both the model editing and simulation capabilities of OpenCOR see if you can come up with an interesting simulation experiment to share with your neighbour. Starting in the :file:`Hill_Basic_pDash.cellml` window: 

1. Iterate between the :guilabel:`Editing` and :guilabel:`Simulation` views to try and obtain some interesting plots or results.
#. See :ref:`cellml_opencor_pmr_tutorial__first_model` for a reminder of how OpenCOR functions.
#. Once you have something to share, see :numref:`ocr_tut_sedml_export_fig` for how to export a new SED-ML document. Be sure to save this document in the same folder where you made the local copy of the workspace.
#. Now synchronise your workspace with PMR.
#. Discover your neighbour's PMR user name.
#. Share your workspace with your neighbour using the directions given here: :ref:`sharingWorkspaces`.
#. When your neighbour shares a workspace with you, you'll need to fork the workspace under your own account in order to access it using OpenCOR (as described above). Then you should be able to make a local copy of the workspace using OpenCOR and hopefully reproduce exactly the same results as your neighbour.
#. If desired, you can also submit your workspace for publication as described under :ref:`sharingWorkspaces`, the tutors can then take a look at your work and also hopefully reproduce the results.
