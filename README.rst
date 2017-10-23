Backend.AI Client
=================

.. image:: https://img.shields.io/pypi/pyversions/backend.ai-client.svg
   :target: https://pypi.org/project/backend.ai-client/
   :alt: PHP Versions

.. image:: https://travis-ci.org/lablup/backend.ai-client-php.svg?branch=master
   :target: https://travis-ci.org/lablup/backend.ai-client-php
   :alt: Build Status (Linux)

.. image:: https://ci.appveyor.com/api/projects/status/5h6r1cmbx2965yn1/branch/master?svg=true
   :target: https://ci.appveyor.com/project/lablup/backend.ai-client-php/branch/master
   :alt: Build Status (Windows)

.. image:: https://codecov.io/gh/lablup/backend.ai-client-php/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/lablup/backend.ai-client-php
   :alt: Code Coverage

The official API client library for `Backend.AI <https://backend.ai>`_

Usage
-----

You should set the access key and secret key as environment variables to use the API.
Grab your keypair from `cloud.backend.ai <https://cloud.backend.ai>`_ or your cluster
admin.

.. code-block:: sh

   export BACKEND_ACCESS_KEY=...
   export BACKEND_SECRET_KEY=...

   # optional (for local clusters)
   export BACKEND_ENDPOINT="https://my-precious-cluster/"


Help commands?
~~~~~~~~~~~~~~

Please run ``backend.ai --help`` to see more commands.
