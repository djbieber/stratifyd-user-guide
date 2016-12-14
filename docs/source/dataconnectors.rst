Connecting to Data
==================


There are three categories of Data Connectors in Signals:


:doc:`3rdpartydataconnectors` provide access to data owned by your organization but stored in 3rd party systems.
Examples include salesforce, Google Analytics, and Zendesk among many others.


:doc:`publicdataconnectors` allow you to access data that anyone can view on the internet, but in a uniform format.
We collect data from Amazon, Facebook, the Google Play store, consumeraffairs.com, and many other sites.


The :doc:`enterprisedataconnectors` are used to connect to internal databases or other 1st party data platforms in your organization.




.. Note:: Enterprise Data Connectors and some 3rd Party Data Sources require you to map fields in your data prior to uploading. See :doc:`mapdata` to learn about this process.


.. _Signals SDK:

Signals SDK
^^^^^^^^^^^

The Signals SDK should be used to upload files more than 500 MB.

It can also be used to develop custom connections and/or schedule uploads.



We offer a node.js wrapper for our SDK.
https://www.npmjs.com/package/signals-api


To generate an API key associated with your account, go to Settings in the left-hand menu from the Signals homepage.

In the Settings page, you will see a button to generate an api key towards the bottom.

This API key will be generated and downloaded in JSON format to be included in your application.

After the API key has been generated, you can always download it again from the Settings page.

.. image:: apikey.png


.. toctree::
  :maxdepth: 1

  3rdpartydataconnectors
  publicdataconnectors
  enterprisedataconnectors
  mapdata