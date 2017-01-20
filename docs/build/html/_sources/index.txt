Welcome to the Signals User Guide!
==================================

*Signals is a powerful, yet easy-to-use augmented intelligence platform.*


+ Signals' :ref:`Analytics Engine <processing data>` leverages unsupervised deep machine learning to identify statistically significant topics within any unstructured data.


+ Signals is completely web-based. The only software required is a modern web browser such as Google Chrome, Mozilla Firefox, Microsoft Edge (Microsoft IE is not recommended).

+ Signals' web interface is point-and-click. No programming knowledge is required.


This guide covers every feature and function within Signals, if you're looking for information about a specific topic, jump to a chapter in the left nav bar.


For more information about Signals or Stratifyd, please visit `our website`_.

.. _our website: http://www.stratifyd.com

.. Note:: **For new users**: Follow the :doc:`quickstartguide` to get up and running in a matter of minutes.


Quick Start Guide
=================


Create an account
~~~~~~~~~~~~~~~~~~~~~~

Begin by :doc:`createaccount`. Once you've logged in, check out some of the pre-built public dashboards in the folders on the homepage.


.. image:: examplefolders.png


Create your first dashboard
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To create your own dashboard, click "Create a new Dashboard".

.. image:: newdashboard.png


Connect to data
^^^^^^^^^^^^^^^

Connect to your database, upload a CSV or Excel file, or use one of our :ref:`Data Connectors <dataconnector>` for easy access to a wealth of publicly available data. Add as many data source to your dashboard as needed.


.. image:: dataconnectors.png
  :scale: 50


If you're bringing your own data, specify which fields contain Textual, Temporal, or Geographical information for analysis and normalization. All other fields will be brought in as pivot points and additional visualizations. 

.. image:: csvorexcel.png

.. Note:: See the :doc:`mapdata` guide for more details when uploading CSV or Excel Files



Create visualizations
^^^^^^^^^^^^^^^^^^^^^^^
Your dashboard will contain visualizations based on the type of data in your analysis by default. See the guide on :ref:`processing data` for information on how to interpret these visualizations. Every visualization is clickable, and clicking will apply a filter on your data based on your selection.

.. image:: signalsgif1.gif


Now you're ready to :doc:`widgeteditor` using your other datapoints to home in on interesting segments within your data and discover topics and themes within your textual data.



Find meaningful insights
^^^^^^^^^^^^^^^^^^^^^^^^^^

Let the visualizations guide your analysis. Click on areas of interest to drill-down into subsets of data

Click on the "Data" tab to view the original documents. If you've filtered down to a subset of your data in your dashboard, you'll see only those documents.

For more information see the chapter on :ref:`analyzing data`.


Share your results
~~~~~~~~~~~~~~~~~~~~~


Make your dashboard public or :ref:`share <share>` with colleagues.

.. _table of contents:



Create an account
=================
.. toctree::
  :maxdepth: 3

  
  createaccount
  
Connect to data
===============
.. toctree::
  :maxdepth: 3
  

  dataconnectors
  mapdata
  
Processing Data
===============
.. toctree::
  :maxdepth: 3
  processingdata
  

Data Visualization
==================
.. toctree::
  :maxdepth: 3
  dashboard
  analysis
  advancedoptions
  

Administration
==============
.. toctree::
  :maxdepth: 3


  administration


Additional Information
======================
.. toctree::
  :maxdepth: 3

  
  releasenotes
  faq
  contact
  miscellaneous
