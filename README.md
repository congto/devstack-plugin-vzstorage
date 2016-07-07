Devstack VzStorage Plugin
================

# Goals

The plugin installs and configures Vzstorage as a Cinder volumes backend

# How to use (localrc configuration)

* Enable devstack-plugin-vzstorage plugin:

     [[local|localrc]]
     enable_plugin devstack-plugin-vzstorage https://github.com/virtuozzo/devstack-plugin-vzstorage
     CONFIGURE_VZSTORAGE_CINDER=True
     VZSTORAGE_CLUSTER_NAME=vz7-vzstorage
