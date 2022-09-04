
###############################
Meshes
###############################

.. role:: folder

.. _lods:

Polycount
=========

+----------------------+------+
|Precombined Meshes    |  LOD0|
+======================+======+
|SK_Charles            | 54229|
+----------------------+------+
|SK_Charles_Set_A      | 45615|
+----------------------+------+
|SK_Charles_Set_B      | 39465|
+----------------------+------+

|

+----------------------+------+
|Mesh Parts            |  LOD0|
+======================+======+
|Head1                 | 10208|
+----------------------+------+
|Body                  | 19864|
+----------------------+------+
|Arms_A (Cutout)       |  9580|
+----------------------+------+
|Arms_B (Cutout)       | 11182|
+----------------------+------+
|Legs (Cutout)         |  5628|
+----------------------+------+
|Eyebrowlashes Teeth   |   846|
+----------------------+------+
|Eyes                  |  1080|
+----------------------+------+
|Eyes_shadow           |  1080|
+----------------------+------+
|Hair1                 |  6348|
+----------------------+------+
|Coresuit1_A           |  8865|
+----------------------+------+
|Coresuit1_B (Coutout) |  8182|
+----------------------+------+
|Jacket1               |  8435|
+----------------------+------+
|Googles1              |  2266|
+----------------------+------+
|Legs_suit1_A          |  6912|
+----------------------+------+
|Legs_suit1_B (Cutout) |  6204|
+----------------------+------+

|

.. _meshes_overview:

Meshes Overview
===============

SK_Charles_Set_A and SK_Charles_Set_B
--------------------------------------

.. image:: /images/meshes/thumbnail-sets.jpg
	:align: center

These are the precombined mesh, :guilabel:`Set_A` is just like the main :guilabel:`SK_Charles` minus the Hair and Googles while :guilabel:`Set_B` is "Set_A without the Jacket".

|
|

Parts
-----

.. image:: /images/meshes/cutout-mesh-parts-thumbnails.jpg
	:align: center

|

.. image:: /images/meshes/cutout-mesh-parts.jpg
	:align: center

|

These mesh parts are cut out to be used in a modular setup so combining them doesn't cause mesh intersecting each other during animations.

To learn more about setting up a modular character from mesh parts, you can check out Unreal Engine's Official Documentation: `Working with Modular Characters <https://docs.unrealengine.com/4.27/en-US/AnimatingObjects/SkeletalMeshAnimation/WorkingwithModularCharacters/>`_

|
|

About the Design
================

Non-Spherical Eyes
------------------

Just a note that the eyes (and eyes shadow) is oval in shape.

.. image:: /images/non-spherical-eyes-01.jpg
	:align: center

|

.. image:: /images/non-spherical-eyes-02.jpg
	:align: center

|

Eyes motion is driven through morph targets (instead of bones).

.. image:: /images/blendshapes-driven-eye-motion.jpg
	:align: center

|
