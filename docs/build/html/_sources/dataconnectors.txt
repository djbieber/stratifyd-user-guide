Connecting to Data
==================


The three categories of Data Connectors in Signals are:


:doc:`3rdpartydataconnectors` are ways to access data owned by your organization but stored in 3rd party systems.
  Examples include salesforce, Google Analytics, and Zendesk among many others.


:doc:`publicdataconnectors` allow you to access data that anyone can view on the internet, but in a uniform format.
  We collect data from Amazon, Facebook, the Google Play store, consumeraffairs.com, and many other sites.


The :doc:`enterprisedataconnectors` are used to connect to internal databases or other 1st party data platforms in your organization.


.. Note:: Enterprise Data Connectors and some 3rd Party Data Sources require you to map fields in your data prior to uploading. See :doc:`mapdata` to learn about this process.



.. toctree::
  :maxdepth: 1

  mapdata
  3rdpartydataconnectors
  publicdataconnectors
  enterprisedataconnectors