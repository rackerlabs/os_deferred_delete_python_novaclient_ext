========================================
os_deferred_delete_python_novaclient_ext
========================================

Adds instance deferred delete support to python-novaclient.

This extension is autodiscovered once installed. To use::

    pip install os_deferred_delete_python_novaclient_ext
    nova restore <SERVER ID>
    nova force-delete <SERVER ID>
