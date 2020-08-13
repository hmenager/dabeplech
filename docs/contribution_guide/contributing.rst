**********************
Contributing to dabeplech
**********************

You have many different ways to contribute to dabeplech:

- Add new API connectors
- `Report a Bug <https://github.com/khillion/dabeplech/issues/new?&labels=bug&template=bug_report.md>`_
- Suggesting a new Feature
- Update the Documentation
- Participate to the discussions in the Github issues

.. Note::
    For more advanced features, such as the code architecture, we encourage to go through discussions on GitHub
    before starting any major changes or contributions.

General rules
=============

- :ref:`contrib_environment`: set up your environment to contribute.
- :ref:`contrib_flow`: contribution through GitHub.
- :ref:`contrib_conduct`

Adding a new API connector
==========================

For the moment, we identify three different scenarios when adding a new API connector:

API already returning JSON
--------------------------

This is the most simple case where you just need to add a new connector:

1. :ref:`contrib_api`
2. :ref:`contrib_docs`

API returning different format
------------------------------

1. :ref:`contrib_model`
2. :ref:`contrib_parser`
3. :ref:`contrib_api_parser`
4. :ref:`contrib_docs`

Build API connector from scrapping
----------------------------------

1. :ref:`contrib_model`
2. :ref:`contrib_scrapper`
3. :ref:`contrib_api_scrapper`
4. :ref:`contrib_docs`
