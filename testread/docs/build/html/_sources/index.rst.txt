.. my_package documentation master file, created by
   sphinx-quickstart on Sun Nov 12 16:20:14 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to my_package's documentation!
======================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

+--------------------+----------------+-----------+
| Header1            |                |           |
+====================+================+===========+
| body row 1         |                |           |
+--------------------+----------------+-----------+

=====  =====  ======
   Inputs     Output
------------  ------
  A      B    A or B
=====  =====  ======
False  False  False
True   False  True
False  True   True
True   True   True
=====  =====  ======


*itelic*

**bold**

.. csv-table:: Frozen Delights!
   :header: "Treat", "Quantity", "Description"
   :widths: 15, 10, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
   crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"


.. list-table:: Frozen Delights!
   :widths: 15 10 30
   :header-rows: 1

   * - Treat
     - Quantity
     - Description
   * - Albatross
     - 2.99
     - On a stick!
   * - Crunchy Frog
     - 1.49
     - If we took the bones out, it wouldn't bcrunchy, now would it?
   * - Gannet Ripple
     - 1.99
     - On a stick!


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


.. DANGER::
   Beware killer rabbits!
.. note::
   Beware killer rabbits!

'click here <https://sejong.ac.kr>'_ to view sejong website

