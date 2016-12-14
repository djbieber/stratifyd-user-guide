Analyzing Data
==============


This chapter covers everything from interacting with your data once you've built a dashboard, to sharing out insights in multiple formats.


Sharing Insights
~~~~~~~~~~~~~~~~


Filters
~~~~~~~

Filters can be set on one of three levels:

1. `Dashboard`_
2. `Tab`_
3. `Widget`_


.. _Dashboard:

Dashboard-Level Filters
^^^^^^^^^^^^^^^^^^^^^^^

To set a filter on the entire dashboard, click the |filterdashboard| icon in the bottom left corner inside your dashboard. This is the "global" filter panel for your dashboard.

.. |filterdashboard| image:: filterdashboard.png


Filters set from here will **not** persist when you leave the dashboard.


.. _Tab:

Tab-Level Filters
^^^^^^^^^^^^^^^^^

Tab level filters can be applied on a per-tab basis. To do this, click the |taboptions| icon and select one of the two methods:

1. Merge with the current query will allow you to set a permanent filter, but still interact with the data. Interactions with other tabs can still affect the data.
2. Override the current query will apply the filter selections you make and freeze the visualizations so that the tab is no longer interactive. Selections on other tabs will not affect the data.


The main datapoints are available for selection from the Tab Detail page. Other datapoints can be accessed by clicking on the "+" icon next to **Extra Structured Vis Parameters**


.. image:: fulltabdetail.png


.. _Widget:

Widget-Level Filters
^^^^^^^^^^^^^^^^^^^^

Widget-level filters will override all other filters for that widget.

To apply a widget-level filter, you can either click on the funnel icon in the widget settings menu from your dashboard view, or you can apply a filter from the :doc:widgeteditor in the Options tab.

.. figure:: filterwidget.png
  
  Widget Settings Menu