.. _processing data:

Processing Data
========================


When a dashboard is created with new data, the data goes through the Signals Analytics Engine for processing. This chapter describes what occurs as the engine is processing data. The output is described in the :ref:`analyzing data` chapter.


.. image:: journey.png


The sections below discuss how the output of the :ref:`Signals Analytics Engine <signalsanalyticsengine>` can be accessed and used.


.. Note:: To learn how to tune the analytics engine, see the :doc:`advancedoptions` page.


.. _signalsanalyticsengine:

Signals Analytics Engine
~~~~~~~~~~~~~~~~~~~~~~~~~

The Signals Analytics Engine leverages Machine Learning and Deep Learning algorithms to help navigate and pivot a large set of textual data.


Built on top of our proprietary Bayesian Neural Network and Generative Model, Signals dynamically identifies semantic topic groups based on the context in your input data.


**This is all done in a three-step process:**

1. **The engine starts by performing NLP in over 24 languages.**


  In this step, your input documents are *tokenized* into corresponding `N-Grams`_ (N>=2), *lemmatized* (words with the same root are grouped together e.g. run & ran), *stemmed*, spam/junk and stop words are filtered out, and *part-of-speech* tagging and *named entity extraction* are performed. A large N-Gram-based content network is then created based on your input data files. 

.. _N-Grams: https://en.wikipedia.org/wiki/N-gram


2. **The engine runs a Multi-Model approach on top of the N-Gram-based content network.**


  This includes using our proprietary text analytics algorithms extended from *Bayesian Neural Network*, *Generative Model*, *LSTM (Long Short Term Memory)*, and *Seq2Seq NLU*. In this step, data input is clustered into semantically meaningful groups.


  The groups are generated and visualized by statistical significance (i.e. the percentage attributed to each topic category in the Semantic Topic Visualization). Each topic is tagged with top representative terms in Buzzwords.



3. **Signals automatically processes all geographical (Where), temporal (When), contributor (Who), as well as any other structured data.**


  It joins the data with the N-Gram-based content network for you to pivot and construct analytics questions against your dataset.


Reprocessing
~~~~~~~~~~~~~~~~~~

There are a number of :ref:`advanced options` that can be applied to customize the output of the Analytics Engine. When applying advanced options your data will need to be reprocessed. This can either be done directly through Edit Mode, or through clicking the reprocess button on your dataset under Manage Data.