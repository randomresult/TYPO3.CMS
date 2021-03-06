
.. include:: ../../Includes.txt

=====================================================================
Breaking: #75747 - EXT:form - Removed useDefaultContentObject setting
=====================================================================

Description
===========

The TypoScript option :ts:`useDefaultContentObject` of the FORM cObject has been removed.
Setting this value to 0 allowed the usage of the prehistoric content type `mailform`.


Impact
======

It is not possible to configure the rendering of the FORM cOject. The setting is not evaluated anymore.


Affected Installations
======================

Any installation that uses the TypoScript option :ts:`useDefaultContentObject = 0`.


Migration
=========

Remove the TypoScript option from any TypoScript settings. Migrate manually to use the features of EXT:form.

.. index:: typoscript
