
.. role:: folder
.. role:: bold-italic

Preview Map
===========

|

.. image:: /images/map-preview1.jpg
	:align: center

|

.. image:: /images/map-preview2.jpg
	:align: center

|

Features
========

* Follows UE4's Epic Skeleton (Mannequin)

* :ref:`Apple BlendShapes <blendshapes>`

* :ref:`Dynamic Hair and Jacket <clothes>`

* :ref:`PBR Textures <textures>`

|
|

Scale (Character Size)
======================

Charles is thought to be around 16 to 20-year-old so his body size is slightly smaller than a mature male (eg. UE4 Mannequin).

.. image:: /images/scale-reference.jpg
	:align: center

|
|

Skeleton
========

While Charles's Skeleton are different in proportions to UE mannequin's skeleton, the naming and structure of the bones are the same. For the main skeleton (< SK_Charles_Skeleton >), it has the same amount of bones (no extra bones). The orientation of the bones is slightly different but I try to match it as close to the mannequin's bone as possible.

Since the body proportion is not exactly same as UE's mannequin you will need to do some :ref:`retargeting on animations <retarget>`.

For ALS (`Advanced Locomotion System <https://www.unrealengine.com/marketplace/en-US/product/advanced-locomotion-system-v1#>`_), I had it working to some degree (please check out :ref:`my guide for ALS <als>`) however due to the difference in arm length, some work is required to fix the arms holding weapons.

.. image:: /images/skeleton.jpg
	:align: center

The picture below shows the bones orientation in Maya:

.. image:: /images/character-vs-mannequin-skeleton.jpg
	:align: center

|
|

Source Fbx Files
================

If you would like to modify the character's mesh you will find the fbx files in the :abbr:`📁Fbx (Content\\Charles\\Fbx)` folder helpful. These are the :bold-italic:`source` fbx files that I exported out of Maya and import into Unreal Engine. The folder's content appears to be empty in Unreal Engine's Content Browser but if you do "Show in Explorer" (open the folder with Windows Explorer or the explorer app of your Operating System), you will see the those fbx files.

I haven't much experience with Blender's skeleton and export workflow, it seems to me Maya is able to read the materials and blendshapes better than Blender so personally I would recommend to try Maya if you have the option.

Blender
-------
One of the issues one might face when exporting fbx out from UE and bringing it into Blender is the missing shape keys and material slots. (The :bold-italic:`source` fbx files don't have this issue)

You can use `Fbx Converter <https://www.autodesk.com/developer-network/platform-technologies/fbx-converter-archives>`_ from Autodesk (`as pointed out by TheBasti82 in this Unreal Engine forum thread <https://forums.unrealengine.com/t/export-shape-keys-morph-targets-from-ue4-to-blender-workaround/133040>`_) to convert the fbx files (from UE) before importing them into Blender.

|
|

Unreal Engine 5
===============

.. image:: /images/ue5/ue5-viewport.jpg
    :align: center

Charles has been tested briefly on UE5 and seems to be working fine. However I was working mostly on UE 4.22 so if there are any issues with other UE versions, please report back and I will try to fix them ASAP.

UE4 to UE5 Converted Projects:
    One thing I noticed when opening the preview map in UE5 (and also UE4.27) is it looks much brighter than the same map in UE4. The exposure compensation setting for PostProcessVolume has reverted back to 1.0, so turning it back to 0.0 should line up the looks with UE 4.22. 

.. image:: /images/ue5/ue5-after.jpg
    :align: center

|

.. note::
    :ref:`Retargeting Guide for UE5 <retarget_ue5>`

|
|

Viewing Image for this Document
===============================

The images of this documentation are automatically resized to fit the width of the contents area, some images actually have a higher resolution so you can try...

#. Right click on the image
#. Select "Open Image in New Tab"

to open the original image in another tab to see it better.

.. image:: /images/viewing-full-image-resolution.jpg
	:align: center

|
|

Supports
========

📧 Email
---------
You can post Questions at Unreal Marketplace or send me an email: miicaneo@gmail.com and I will try to reply to you as soon as I can.


.. Discord
   -------
    I also created a Discord Server as another option:

    https://discord.gg/WzspRd3QrG

    .. Note::
        The Discord setup is very simple for now as I don't have much experience with Discord.

|
