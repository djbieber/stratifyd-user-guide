.. _dataconnector:

Connecting to Data
==================


There are three categories of Data Connectors in Signals:

.. toctree::
  :maxdepth: 1

  enterprisedataconnectors
  3rdpartydataconnectors
  publicdataconnectors
  

:doc:`enterprisedataconnectors` are used to connect to internal databases or other 1st party data platforms in your organization.


:doc:`3rdpartydataconnectors` provide access to data owned by your organization but stored in 3rd party systems.
Examples include salesforce, Google Analytics, and Zendesk among many others.


:doc:`publicdataconnectors` allow you to access data that anyone can view on the internet, but in a uniform format.
We collect data from Amazon, Facebook, the Google Play store, consumeraffairs.com, and many other sites.


You can also upload a csv or excel file from your local computer.

.. image:: csvorexcel.png


.. Note:: Enterprise Data Connectors and some 3rd Party Data Sources require you to map fields in your data prior to uploading. See :doc:`mapdata` to learn about this process.


.. _Signals SDK:

Signals SDK
^^^^^^^^^^^

The Signals SDK should be used to upload files more than 500 MB.

It can also be used to develop custom connections and/or schedule uploads.



We offer a node.js wrapper for our SDK.
https://www.npmjs.com/package/signals-api


To generate an API key:

1. go to Settings in the left-hand menu from the Signals homepage.

2. In the Settings page, click the button to generate an api key towards the bottom.

3. This API key will be generated and downloaded in JSON format to be included in your application.

After the API key has been generated, you can always download it again from the Settings page.

.. image:: apikey.png