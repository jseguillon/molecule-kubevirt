************************
Molecule KubeVirt Plugin
************************

.. image:: https://badge.fury.io/py/molecule-kubevirt.svg
   :target: https://badge.fury.io/py/molecule-kubevirt
   :alt: PyPI Package

.. image:: https://github.com/jseguillon/molecule-kubevirt/workflows/tox/badge.svg
   :target: https://github.com/jseguillon/molecule-kubevirt/actions

.. image:: https://img.shields.io/badge/code%20style-black-000000.svg
   :target: https://github.com/python/black
   :alt: Python Black Code Style

.. image:: https://img.shields.io/badge/license-MIT-brightgreen.svg
   :target: LICENSE
   :alt: Repository License

Molecule KubeVirt Plugin is designed to allow use [KubeVirt](https://kubevirt.io/) containers for provisioning test resources.

**Very alpha version - All configuration fields and behaviours may be subject to breaking changes**

.. _usage:

Usage
=====

Ansible molecule-kubevirt runners require:

- ansible-galaxy collection install community.general
- ansible-galaxy collection install community.crypto
- ansible-galaxy collection install community.kubernetes.git

Also need access to a Kubernetes cluster, via user kubeconfig or ServiceAccount. Minimum authorizations:

- ClusterRole [`kubevirt.io:edit`](https://kubevirt.io/user-guide/#/installation/authorization?id=kubevirt-default-rbac-clusterroles)
- POST and EGT on Services

.. _get-involved:

Get Involved
============

* Join us in the ``#ansible-molecule`` channel on `Freenode`_.
* Join the discussion in `molecule-users Forum`_.
* Join the community working group by checking the `wiki`_.
* Want to know about releases, subscribe to `ansible-announce list`_.
* For the full list of Ansible email Lists, IRC channels see the
  `communication page`_.

.. _`Freenode`: https://freenode.net
.. _`molecule-users Forum`: https://groups.google.com/forum/#!forum/molecule-users
.. _`wiki`: https://github.com/ansible/community/wiki/Molecule
.. _`ansible-announce list`: https://groups.google.com/group/ansible-announce
.. _`communication page`: https://docs.ansible.com/ansible/latest/community/communication.html

.. _license:

License
=======

The `MIT`_ License.

.. _`MIT`: https://github.com/jseguillon/molecule-kubevirt/blob/master/LICENSE

The logo is licensed under the `Creative Commons NoDerivatives 4.0 License`_.

If you have some other use in mind, contact us.

.. _`Creative Commons NoDerivatives 4.0 License`: https://creativecommons.org/licenses/by-nd/4.0/
