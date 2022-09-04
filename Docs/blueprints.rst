
###############################
Blueprints
###############################

.. role:: folder

Overview
========

.. image:: /images/blueprints/content-blueprints.jpg
    :align: center

The :abbr:`📁Blueprints (Charles\\Blueprints)` folder contains character blueprints (BP_***) and animation blueprints (AnimBP_***) duplicated from third person character template of UE 4.22.

< BP_Charles > uses precombined mesh which is just a really basic setup while < BP_Charles_Modular_Dynamic > shows a modular + dynamic version by assembling two dynamic skeletal meshes: < SK_Charles_Hair1_Dynamic > and < SK_Charles_Coresuit1_Jacket1_Dynamic >

< SK_Charles_Hair1_Dynamic > and < SK_Charles_Coresuit1_Jacket1_Dynamic > are not using the main skeleton ( < SK_Charles_Skeleton > ). They have their own skeleton with extra joint chains.

Some controls added to the < BP_Charles >:
   
   *  Zoom with Mouse Wheel

   *  Pan Camera Vertically with :kbd:`Q` and :kbd:`E`

|

New Axis Mapping added to Project Settings to work with the blueprints:

.. image:: /images/blueprints/engine-input-settings.jpg
    :align: center
