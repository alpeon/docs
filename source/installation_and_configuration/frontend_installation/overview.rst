.. _opennebula_installation_overview:

================================================================================
Overview
================================================================================

The Frontend is the central part of an OpenNebula installation. This is the machine where the server software is installed and where you connect to manage your cloud. It can be a physical node or a virtual instance.

How Should I Read This Chapter
================================================================================

Before reading this chapter make sure you have picked the :ref:`Architecture Blueprint <architecture_blueprints>` that better fits your needs.

The aim of this chapter is to give you a quick-start guide to deploy OpenNebula. This is the simplest possible installation, but it is also the foundation for a more complex setup, with :ref:`Advanced Components <advanced_components>`.

First you should read the :ref:`Front-end Installation <frontend_installation>` section. Note that by default it uses an SQLite database that is not recommended for production. So, if this is not a small proof of concept, while following the Installation section you should use the :ref:`MySQL <mysql_setup>`.

After reading this chapter, read the :ref:`Node Installation <node_installation>` chapter next in order to add hypervisors to your cloud.

Hypervisor Compatibility
================================================================================

+-------------------------------------------------------+-----------------------------------------------+
|                        Section                        |                 Compatibility                 |
+=======================================================+===============================================+
| :ref:`Front-end Installation <frontend_installation>` | This Section applies to all hypervisors       |
+-------------------------------------------------------+-----------------------------------------------+
| :ref:`MySQL Setup <mysql_setup>`                      | This Section applies to all hypervisors       |
+-------------------------------------------------------+-----------------------------------------------+
| :ref:`Scheduler <schg>`                               | This Section applies to all hypervisors       |
+-------------------------------------------------------+-----------------------------------------------+



.. todo:: Contents from HA overview

How Should I Read This Chapter
================================================================================

The :ref:`Front-end HA Setup <frontend_ha_setup>` section will guide you through the process of setting up a high availability (HA) cluster.

If you want to enable automatic Virtual Machine recovery in case of a Host failure, or if you want to learn how to manually recover a Virtual Machine in a failed state, please read the :ref:`Virtual Machines High Availability <ftguide>` section.

Hypervisor Compatibility
================================================================================

+-----------------------------------------------------+------------------------------------------------------------------------+
|                       Section                       |                 Compatibility                                          |
+=====================================================+========================================================================+
| :ref:`Font-end HA Setup <frontend_ha_setup>`        | This Section applies to all Hypervisors.                               |
+-----------------------------------------------------+------------------------------------------------------------------------+
| :ref:`Virtual Machines High Availability <ftguide>` | This Section applies only to KVM, LXD and Firecracker.                 |
+-----------------------------------------------------+------------------------------------------------------------------------+