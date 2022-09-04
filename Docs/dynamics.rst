
###############################
Dynamic Meshes
###############################

.. role:: folder

.. _dynamics:

Dynamic Meshes are some meshes that are setup with skeleton with extra bones for use in dynamic simulation (either physics assets, anim dynamics or etc). These meshes don't use the main character skeleton but use their own skeleton in their own \*\*\*_Dynamic folder.

Dynamic Folders
===============

.. image:: /images/dynamics/dynamic-folders.jpg
	:align: center


The :abbr:`📁\*\*\*_Dynamic (Charles\\Meshes\\\*\*\*_Dynamic)` folders hold the sk mesh (\SK_\*\*\*) and skeleton (\SK_\*\*\*_Skeleton), its animation blueprint (\ABP_\*\*\*), and its physic assets (\SK_\*\*\*_Physics, if available).

Note that example *Blueprint* setup that make use of the dynamic meshes is located at :abbr:`📁Blueprints (Charles\\Blueprints)`

|

Hair1_Dynamic
-------------

These are the extra bones for < SK_Charles_Hair1_Dynamic >.

Hair1_Dynamic is simulated with Anim Dynamics nodes (Animation Blueprint) so it doesn't comes with any physics asset.

.. image:: /images/dynamics/hair1-extra-bones.jpg
	:align: center

|

List of Bones for Hair1_Dynamic
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. admonition:: Target List
	:class: refbox

	:Hair1: * hair_A_01, hair_A_02, hair_A_03, hair_A_04, hair_A_05
				* hair_B_01, hair_B_02, hair_B_03, hair_B_04, hair_B_05
				* hair_C_01, hair_C_02, hair_C_03, hair_C_04, hair_C_05, hair_C_06
				* hair_D_01, hair_D_02, hair_D_03, hair_D_04, hair_D_05
				* hair_E_01, hair_E_02, hair_E_03, hair_E_04, hair_E_05
				* hair_F_01, hair_F_02, hair_F_03, hair_F_04, hair_F_05
				* hair_G_01, hair_G_02, hair_G_03, hair_G_04, hair_G_05
				* hair_H_01, hair_H_02, hair_H_03, hair_H_04, hair_H_05
				* hair_I_01, hair_I_02, hair_I_03, hair_I_04, hair_I_05
				* hair_J_01, hair_J_02, hair_J_03, hair_J_04, hair_J_05
				* hair_K_01, hair_K_02, hair_K_03, hair_K_04, hair_K_05
				* hair_L_01, hair_L_02, hair_L_03, hair_L_04, hair_L_05
				* hair_M_01, hair_M_02, hair_M_03, hair_M_04, hair_M_05
				* hair_N_01, hair_N_02, hair_N_03, hair_N_04, hair_N_05
				* hair_O_01, hair_O_02, hair_O_03, hair_O_04, hair_O_05
				* hair_P_01, hair_P_02, hair_P_03, hair_P_04, hair_P_05
				* hair_Q_01, hair_Q_02, hair_Q_03, hair_Q_04, hair_Q_05
				* hair_R_01, hair_R_02, hair_R_03, hair_R_04, hair_R_05

|
|

Jacket1_Dynamic
---------------

These are the extra bones for < SK_Charles_Coresuit1_Jacket1_Dynamic >

.. image:: /images/dynamics/jacket1-extra-bones.jpg
	:align: center

|

Jacket1_Dynamic is simulated with RigidBody node (Animation Blueprint) so it has a physics asset.

.. image:: /images/dynamics/jacket1-physics-asset.jpg
	:align: center

|

List of Bones for Jacket1_Dynamic
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. admonition:: Target List
	:class: refbox

	:Jacket1: * jacketFront_01_l, jacketFront_02_l, jacketFront_03_l, jacketFront_04_l
				* jacketFront_01_r, jacketFront_02_r, jacketFront_03_r, jacketFront_04_r
				* jacketSide1_01_l, jacketSide1_02_l, jacketSide1_03_l, jacketSide1_04_l
				* jacketSide1_01_r, jacketSide1_02_r, jacketSide1_03_r, jacketSide1_04_r
				* jacketSide2_01_l, jacketSide2_02_l, jacketSide2_03_l, jacketSide2_04_l
				* jacketSide2_01_r, jacketSide2_02_r, jacketSide2_03_r, jacketSide2_04_r
				* jacketBack_01_l, jacketBack_02_l, jacketBack_03_l, jacketBack_04_l
				* jacketBack_01_r, jacketBack_02_r, jacketBack_03_r, jacketBack_04_r
				* hoodie_01, hoodie_02, hoodie_03, hoodie_04

|

