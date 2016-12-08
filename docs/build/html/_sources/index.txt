Welcome to the Signals User Guide!
==================================

Signals is an advanced analytics platform designed to empower users of all backgrounds to get from data >> insight >> **revenue** faster.

This guide is intended to be a reference as you navigate through your analysis journey.

Should you come across any question not covered in this guide, you can always chat with the Stratifyd support team online in Signals or email us at info@stratifyd.com . 


Quick Start Guide
=================

1. Once you've created an account, check out some of the public dashboards in the folders on the homepage.
2. To create your own dashboard, click "Create a new Dashboard" on the right under the folders.
3. If you have your own data you wish to analyze in CSV or Excel file, you can select the CSV or excel icon and upload your data. Check out the :doc:`mapdata` guide for details.
4. If you don't have data, you can use one of our :doc:`dataconnectors` to connect to a variety of sources both public and private (if you have credentials for the service). Click on the connector you wish to use and follow the instructions for that connector. You can continue adding as many files or data connector sources as you want to a single dashboard. Keep in mind that additional sources can always be added to your dashboard later.
5. When you're ready to start analyzing, click "Create Dashboard" and your data will begin streaming into our analytics engine. You'll get notifications as the data progresses as well as when your data processing is complete.
6. Enter your dashboard by clicking on the dashboard icon. You'll see some default visualizations based on the type of data in your analysis. See the guide on our :doc:`signalsanalyticsengine` for information on how to interpret these visualizations. Every visualization is clickable. Clicking will apply a filter on your data based on your selection.
7. To get back to a view of your raw data, navigate to the "Data" tab. This will show your raw documents. If you have any filters applied, you'll only see the documents that match your filter.
8. Now you're ready to :doc:`widgeteditor` using your other datapoints to hone in on interesting segments within your data and discover topics and themes within your textual data.


Chapters
=========
.. toctree::
	:maxdepth: 2

	dataconnectors
	signalsanalyticsengine
	dashboard
	analysis
	administration
	miscellaneous



FAQ
===

**Where Does the "Signals" name come from?**

  Stratifyd is a unique way of spelling Stratified Sampling, which is a statistical method that illustrates the peeling of layers and layers of data to derive a proper statistical result. We took the name Stratifyd to emphasize on the next-gen Data Analytics that will be mathematically sound and interpretable by human. This truly reflects our company mission on provideing an Augmented Intelligence environment that leverages Artificial Intelligence to Augment Human's Decision Making process. 

  For more reading on Stratified: In statistics, stratified sampling is a method of sampling from a population. In statistical surveys, when subpopulations within an overall population vary, it is advantageous to sample each subpopulation (stratum) independently.

**Is there a limit to how much data I can upload or analyze**

  Trial accounts are limited to 30MB uploads.

  While there is no limit on Enterprise accounts, the web interface only supports up to 500MB files. Larger Files should be uploaded via the _`Signals SDK`
