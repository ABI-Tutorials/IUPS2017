.. _tutorialSharing:

Sharing
=======

In this part of the tutorial we look at taking an existing model, having a play with it, and sharing it with our colleagues. You need to make sure you have completed the :ref:`preparation <tutorialPreparation>` before embarking on the following.

The Hill 3-element model
------------------------

For this tutorial we are working with various configurations of the fundamental Hill mechanics model. We have prepared a starting point :term:`workspace` for you to begin with. In your browser, head over to http://teaching.physiomeproject.org/workspace/2b4 and :term:`fork` the workspace. This will create your own *private* copy of the workspace to use. Instructions for how to actually accomplish this are given at: :ref:`tut1forkingaworkspace`.

If you now reload your workspaces in the :guilabel:`PMR Workspaces` panel in OpenCOR, you should see your newly created fork of the basic Hill model workspace. Following the same instructions as given in :ref:`cellml_opencor_pmr_tutorial__pmr_with_opencor`, you should now make a local copy of this workspace. You can then load the file :file:`Hill_Basic1.sedml` into OpenCOR by double-clicking it.

.. note::

   `SED-ML <http://sed-ml.org>`_ is a standard for encoding descriptions of simulation experiments. OpenCOR makes use of SED-ML to serialise the various settings for simulations to be executed and graphs to be drawn, so that users are able to archive such information as well as share it.
   
Once the SED-ML file is loaded, you should be able to execute the simulation experiment and hopefully get something that looks similar to :numref:`isb2017_sharing_basic_hill1`. Further assistance for running simulations is available here: :ref:`cellml_opencor_pmr_tutorial__first_model`.

.. Figure:: resources/Hill_Basic1_sedml.png
   :name: isb2017_sharing_basic_hill1
   :alt: Simulation results for Hill Basic1 model.
   :align: center
   :width: 75%
   
   The results from executing the simulation experiment described in :file:`Hill_Basic1.sedml`.

