=====================
Planning an Itinerary
=====================

By default, **Odoo Field Service** shows a static map where all task locations for the day are
pinned. To make it more useful for the field service workers, it is possible to display an itinerary
on the map. To do so enable the **Map Route** feature as follows.

Configure Route Map
===================

To enable the **Map Routes feature**, a free **MapBox** account is required and needs to be linked
to Odoo.

Go to the `Mapbox website <https://www.mapbox.com/>`_ :
 - create an account or log in if you already have one
 - create a token

Go to the :guilabel:`Settings` app, scroll down to :menuselection:`Integrations --> Map Routes -->
Token --> paste your MapBox token --> Save`.

Setup your Field Service task to be featured on a map
=====================================================

Go to :guilabel:`Field Service` and create a new task.

.. important::
   For a Field Service task to be featured on a map, it needs:

   - a planned date
   - a valid address linked to the customer’s profile

Doing so sorts out the day’s field service tasks in order based on their time and date, and shows
the way from one location to the next.

Display your itinerary on a map
===============================

Go to :menuselection:`Field Service --> My Tasks --> Map`. By default, this map shows today’s tasks.
Remove the :guilabel:`Today` filter on the research above the map top to display all tasks. Your
tasks are sorted by date on the left column and pinned on the map.

Open your itinerary in Google Maps
==================================

Go to :menuselection:`Field Service --> My Tasks --> Map --> View in Google Maps`

Doing so opens your itinerary on the Google Maps website or the Google Maps app if it’s installed on
your device.

Google Maps includes your current location as a starting point for your itinerary.
