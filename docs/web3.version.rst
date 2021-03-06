Version API
===========

.. py:module:: web3.version
.. py:currentmodule:: web3.version

.. py:class:: Version

The ``web3.version`` object exposes methods to interact with the RPC APIs under
the ``version_`` namespace.


Properties
----------

The following properties are available on the ``web3.eth`` namespace.

.. py:method:: Version.api(self)

    Returns the current Web3 version.

    .. code-block:: python

        >>> web3.version.api
        "2.6.0"


.. py:method:: Version.node(self)

    Method is deprecated in favor of ``web3.clientVersion``.

    * Delegates to ``web3_clientVersion`` RPC Method

    Returns the current client version.

    .. code-block:: python

        >>> web3.clientVersion
        'Geth/v1.4.11-stable-fed692f6/darwin/go1.7'


.. py:method:: Version.ethereum(self)

    Method is deprecated in favor of ``web3.eth.protocolVersion``.
