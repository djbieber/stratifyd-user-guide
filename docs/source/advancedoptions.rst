Advanced Options
================

Advanced options allow users to customize the way data is processed. These options are not always needed, but there are some scenarios in which they are very useful. For example:


In Twitter data if there is any spam, it will quickly be identified through the visualization. Users can choose to filter out the spam and reprocess the data, indicating to the :doc:`signalsanalyticsengine` that the matching documents should be ignored when processing (generating buzzwords and categories).

.. Note:: Spam is typically identified in two ways:
          

          1. A specific user in your dataset is posting junk content - in this case, you can simply select the user to ignore.
          

          2. A specific message has gotten picked up and re-posted by many different users - in this case, you can select the text that is unique to that message and it will be filtered out based on the content.





Stopwords
~~~~~~~~~


Junk/Spam
~~~~~~~~~


Sentiment
~~~~~~~~~


Taxonomy
~~~~~~~~


Chinese Dictionary
~~~~~~~~~~~~~~~~~~