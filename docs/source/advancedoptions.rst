Advanced Options
================

Advanced options allow users to customize the way data is processed. These options are not always needed, but there are some scenarios in which they are very useful. For example:




Stopwords
~~~~~~~~~

Signals provides an out-of-the-box list of stopwords that include the main commonly used non-informative words such as: "the", "an", "I", etc.

Additional stopwords can be added on a per-data-source level to cut through some of the noise in the text.


For example, RSS news feeds typically contain the same few sentences at the end of every article::

   Reporting By Laila Bassam in Aleppo and Tom Perry, John Davison and Lisa Barrington in Beirut; Writing by Angus McDowall in Beirut, editing by Peter Millership

Appears at the end of every news article in some publications. "Reporting By" and "Writing By" will likely get picked up as Buzzwords.

To suppress the noise caused by these terms, 


Junk/Spam
~~~~~~~~~

Creating a Junk/Spam list can be useful in many different datasets


For example in Twitter data if there is any spam, it will quickly be identified through the visualization. Users can choose to filter out the spam and reprocess the data, indicating to the :doc:`signalsanalyticsengine` that the matching documents should be ignored when processing (generating buzzwords and categories).

.. Note:: Spam is typically identified in two ways:
          

          1. A specific user in your dataset is posting junk content - in this case, you can simply select the user to ignore.
          

          2. A specific message has gotten picked up and re-posted by many different users - in this case, you can select the text that is unique to that message and it will be filtered out based on the content.

This is just one example, but as you can see it is generalizable to many other data-types.


Sentiment
~~~~~~~~~

Customizations may be needed is in sentiment scoring in some scenarios.


Signals Provides an out-of-the-box sentiment package that is trained on a breadth of data sources.


Certain terms are generally neutral, but when used in the context of a specific data-set or industry, always have a sentiment associatd with them. Or vise-versa, some terms are very negative generally, but are actually commonly used industry lingo among certain data-sets.


Taxonomy
~~~~~~~~





Chinese Dictionary
~~~~~~~~~~~~~~~~~~