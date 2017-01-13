.. _dataconnector:

Connecting to Data
==================


There are three categories of Data Connectors in Signals:


:doc:`enterprisedataconnectors` are used to connect to internal databases or other 1st party data platforms in your organization.


:doc:`3rdpartydataconnectors` provide access to data owned by your organization but stored in 3rd party systems.
Examples include salesforce, Google Analytics, and Zendesk among many others.


:doc:`publicdataconnectors` allow you to access data that anyone can view on the internet, but in a uniform format.
We collect data from Amazon, Facebook, the Google Play store, consumeraffairs.com, and many other sites.


You can also upload a csv or excel file from your local computer.

.. image:: csvorexcel.png


.. Note:: Enterprise Data Connectors and some 3rd Party Data Sources require you to map fields in your data prior to uploading. See :doc:`mapdata` to learn about this process.


Enterprise Data Connectors
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


The Enterprise Data Connector application allows users to connect with a variety of internal data sources.


Examples include:

+ Hive
+ mySQL
+ Microsoft SQL Server
+ PostgreSQL
+ Oracle SQL


3rd Party Data Connectors
^^^^^^^^^^^^^^^^^^^^^^^^^^^


3rd Party Data Connectors usually have a pop-up window that allows you to enter your credentials with the 3rd party in order to authenticate with Signals.


.. Note:: Make sure you have pop-up blocking disabled when connecting with a 3rd Party Data Connector


- `salesforce`_
- `Foresee`_
- `Surveymonkey`_
- `Gmail`_
- `Livechat`_
- `Intercom`_
- `JIRA`_
- `UserVoice`_
- `Zendesk`_
- `Google Analytics`_
- `Trello`_



salesforce
~~~~~~~~~~

.. image:: salesforce.png

Foresee
~~~~~~~~

.. image:: foresee.png


Surveymonkey
~~~~~~~~~~~~~~

.. image:: surveymonkey.png


Gmail
~~~~~~

Gmail allows you to connect with a Gmail account and enter a query that will pull data matching the query.


.. image:: gmail.png


Livechat
~~~~~~~~~~~

The LiveChat connector allows you to select a date range and the type of user you want to analyze chats for: Agent, Visitor, or both.


.. image:: livechat.png


Intercom
~~~~~~~~~~


JIRA
~~~~~~

.. image:: jira.png


With the JIRA Data Connector, you can select which projects you want to analyze. You can also specify a ticket type if desired. If nothing is specified, Signals will pull all of your JIRA data.


UserVoice
~~~~~~~~~~

The UserVoice data connector requires a login and api key to connect to your uservoice data. The permissions associated with the login correspond with what data will be available through the connector.


.. image:: uservoice.png


Users can specify which objects you want to analyze.



Zendesk
~~~~~~~~


Google Analytics
~~~~~~~~~~~~~~~~~


Trello
~~~~~~~


Public Data Connectors
^^^^^^^^^^^^^^^^^^^^^^^^


Product/App Reviews
--------------------

+ `iOS Store Reviews`_
+ `Google Play Store Reviews`_
+ `Home Depot Product Reviews`_
+ `Lowes Product Reviews`_
+ `Best Buy Product Reviews`_
+ `Wal Mart Product Reviews`_
+ `Etsy Shop Reviews`_
+ `Etsy Product Reviews`_
+ `Amazon Product Reviews`_


Social Media
-------------

+ `Twitter`_ (with twitter account credentials)
+ `Facebook`_ (with facebook account credentials)
+ `Weibo search`_
+ `Youku`_
+ `YouTube Comments`_


Customer/HR Feedback
---------------------

+ `Consumer Financial Protection Bureau`_
+ `Indeed`_
+ `Consumer Affairs`_





iOS Store Reviews
~~~~~~~~~~~~~~~~~

.. image:: iosstore.png

Google Play Store Reviews
~~~~~~~~~~~~~~~~~~~~~~~~~

Home Depot Product Reviews
~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: homedepot.png


Lowes Product Reviews
~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: lowes.png


Best Buy Product Reviews
~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: bestbuy.png


Wal Mart Product Reviews
~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: walmart.png


Etsy Shop Reviews
~~~~~~~~~~~~~~~~~~~~~~~~~

Etsy Product Reviews
~~~~~~~~~~~~~~~~~~~~~~~~~

Amazon Product Reviews
~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: amazon.png


Twitter
~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: twittersearch.png


.. image:: twitteruser.png


Facebook
~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: facebook.png


Weibo search
~~~~~~~~~~~~~~~~~~~~~~~~~

Youku
~~~~~~~~~~~~~~~~~~~~~~~~~

YouTube Comments
~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: youtube.png


Consumer Financial Protection Bureau
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: cfpb.png


Indeed
~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: indeed.png


Consumer Affairs
~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: consumeraffairs.png



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