astrool
=======

.. image:: docs/logo/logo_text.png
   :width: 100%
   :align: center

astrool is an open source pure Python package dedicated to problems arising in life of
day to day Astronomy, such as night sky plotting, analemma plotting,
conversion between position and velocity vectors and classical orbital elements and orbit plotting.
It is released under the MIT license.

Installation
============

Type in your teminal:

    $ pip install astrool

You can also clone this repository and run:

    $ python setup.py install


Requirements
============

astrool requires the following Python packages:

* NumPy, for basic numerical routines
* Astropy, for physical units and time handling
* ephem, for the planetary ephemerides using SPICE kernels
* matplotlib, for plotting
* poliastro, for orbit determination


Testing
=======

If installed correctly, the tests can be run using pytest::

  $ python -c "import astrool.testing; astrool.testing.test()"
  Running unit tests for astrool
  [...]
  OK
  $

Problems
========

If the installation fails or you find something that doesn't work as expected,
please open an issue in the `issue tracker`_.

.. _`issue tracker`: https://github.com/shreyasbapat/astrool/issues

Contributing
============

astrool is a community project, hence all contributions are more than
welcome! For more information, head to `CONTRIBUTING.rst`_.

.. _`CONTRIBUTING.rst`: https://github.com/shreyasbapat/astrool/blob/master/CONTRIBUTING.rst

Support
=======

Release announcements and general discussion take place on our `mailing list`_.
Feel free to join!

.. _`mailing list`: https://groups.io/g/astrool-dev

https://groups.io/g/astrool-dev


License
=======

astrool is released under the MIT license, hence allowing commercial
use of the library. Please refer to the COPYING file.

FAQ
===

What's up with the name?
------------------------

astrool is made up of astro + tools. So basically, we are trying to come up with an aggregated software.


What's the future of the project?
---------------------------------

astrool is a very new project and we aim to develop it further so that it can become one
package for all in basic astronomy.
