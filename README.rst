trytond-customs-value
=====================

This module adds a `customs value` field to Product Variants where the
customs value of a product can be recorded. Since most businesses have the
retail price (or list price) as the customs value, the default behavior is
to use the list price as the customs value.

.. image:: https://travis-ci.org/openlabs/trytond-customs-value.svg?branch=develop
  :target: https://travis-ci.org/openlabs/trytond-customs-value
  :alt: Build Status
.. image:: https://pypip.in/download/openlabs_customs_value/badge.svg
    :target: https://pypi.python.org/pypi/openlabs_customs_value/
    :alt: Downloads
.. image:: https://pypip.in/version/openlabs_customs_value/badge.svg
    :target: https://pypi.python.org/pypi/openlabs_customs_value/
    :alt: Latest Version
.. image:: https://pypip.in/status/openlabs_customs_value/badge.svg
    :target: https://pypi.python.org/pypi/openlabs_customs_value/
    :alt: Development Status

Screenshots
-----------

To be uploaded

Why use this module
-------------------

This module was built to be a supporting module for the shipping modules
of Openlabs that integrates with carriers like FedEx, UPS and USPS. When
generating international shipment labels, the carriers expect customs
value to be electronically transferred to them.

Why not just use list price ?
-----------------------------

This works for most businesses. This is indeed the default behavior of
this module.

On the other hand, if you are wholesaler, you may not want
the retail list price being sent as the customs value for the product.

Authors and Contributors
------------------------

This module was built at `Openlabs <http://www.openlabs.co.in>`_. 

Professional Support
--------------------

This module is professionally supported by `Openlabs <http://www.openlabs.co.in>`_.
If you are looking for on-site teaching or consulting support, contact our
`sales <mailto:sales@openlabs.co.in>`_ and `support
<mailto:support@openlabs.co.in>`_ teams.
