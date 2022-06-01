
## Usage
installation:

Installation
------------
![Infotopics-Apps-for-Tableau-logo-275x100-1](https://user-images.githubusercontent.com/6596304/171428233-9ba7f9c8-29a7-47fc-afbc-4304dcb03552.png)

To use Lumache2, first install it using pip:

.. code-block:: console


   (.venv) $ pip install lumache1

Creating recipes
----------------
## test heading
To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola'![Uploading Infotopics-Apps-for-Tableau-logo-275x100-1.png…]()
, 'parsley']

