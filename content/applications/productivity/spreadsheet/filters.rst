=======
Filters
=======

A filter is a tool that presents specific data in a spreadsheet within the *Documents* app.

Different filter options are available to use, depending on the data contained in the spreadsheet.
If a specific filter does not apply to a spreadsheet, that filter is not available.

.. example::
   A spreadsheet contains only information about the quantities of product in a warehouse, and does
   **not** have any date-related information. No filters relating to dates appear in the presented
   filters list.

To access the available filters for a spreadsheet, first navigate to the :menuselection:`Documents
app`, then click on the desired spreadsheet. Next, click the :icon:`fa-filter` :guilabel:`(Filters)`
icon in the top-right corner to view the available filters.

.. image:: filters/filter.png
   :align: center
   :alt: The filter icon in the top-right corner of a spreadsheet.

Add a new filter
================

If no filters ahve been configured for a spreadsheet, a new filter must first be added.

Click the :icon:`fa-filter` :guilabel:`(Filters)` icon in the top-right corner, and a
:guilabel:`Filters` popover window appears.

Beneath the heading :guilabel:`Add a new filter...`, click on one of the presented filter options.
The options presented are the only filters that apply to the selected spreadsheet.

.. image:: filters/add-filter.png
   :align: center
   :alt: The filter options that appear after clicking the filter icon.

Below are all the various options that can appear in the :guilabel:`Add a new filter...` list.

Once the information is entered for a filter, click :guilabel:`Save` to save the filter
configuration. Once saved, the filter appears beneath the :guilabel:`Filters` heading, and above the
:guilabel:`Add a new filter...` section.

Date
----

Populate the various fields presented in the date filter:

- :guilabel:`Label`: enter a name for the specific filter.
- :guilabel:`Time range`: select the desired time frame to present. Options are either:
  - :guilabel:`Month / Quarter`:
  - :guilabel:`Relative Period`:
  - :guilabel:`From / To`:
- :guilabel:`Default value`:
- :guilabel:`Field matching`:

Relation
--------

Populate the various fields presented in the relation filter:

- :guilabel:`Label`: enter a name for the specific filter.
- :guilabel:`Related model`:

Text
----

Populate the various fields presented in the text filter:

- :guilabel:`Label`: enter a name for the specific filter.
- :guilabel:`Restrict values to a range`: tick the checkbox to limit the results to a specific
  range of values.
- :guilabel:`Default value`:
- :guilabel:`Field matching`:
