
.. include:: ../../Includes.txt

=============================================================
Breaking: #72711 - Remove property strict in TypoScriptParser
=============================================================

Description
===========

The property `strict` of `\TYPO3\CMS\Core\TypoScript\Parser\TypoScriptParser` has been removed.


Impact
======

Using the property directly in any third party extension will result in a fatal error.


Affected Installations
======================

Instances which call the above mentioned property.


Migration
=========

No migration available.

.. index:: php
