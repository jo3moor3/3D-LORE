Usage
=====

.. _Topology:

Topology
------------
Ver·tex
``/ˈvərˌteks/``
each angular point of a polygon, polyhedron, or other figure.
a meeting point of two lines that form an angle.
the point at which an axis meets a curve or surface.
.. autofunction:: TAGS
   ``Geometry``, ``Topology``

Rigging
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.


Animation
----------------

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

