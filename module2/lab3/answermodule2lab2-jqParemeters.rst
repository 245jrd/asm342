Answer Module 2 Lab 2
======================

To get the name of the policy using jq

.. code-block:: bash

        curl -sk -u admin:password -X GET https://10.1.1.245/mgmt/tm/asm/policies | jq .items[0].name


