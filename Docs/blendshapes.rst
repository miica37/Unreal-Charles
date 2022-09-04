
.. role:: folder

.. _blendshapes:

###############################
Morph Targets (Blendshapes)
###############################

Meshes
======

Only < Head > and < Eyes > (part of Head) has blendshape.

Head
----

The Head has about 55 morph targets that are created by following the guide on `Apple's ARKit documentation <https://developer.apple.com/documentation/arkit/arfaceanchor/blendshapelocation/>`_. It should work with Unreal's Live Link Face.

.. image:: /images/blendshapes/blendshapes-preview.jpg
	:align: center

.. admonition:: Target List
	:class: refbox

	:Eyes: eyeBlinkLeft
            eyeBlinkRight
            eyeLookDownLeft
            eyeLookDownRight
            eyeLookInLeft
            eyeLookInRight
            eyeLookOutLeft
            eyeLookOutRight
            eyeLookUpLeft
            eyeLookUpRight
            eyeSquintLeft
            eyeSquintRight
            eyeWideLeft
            eyeWideRight
	:Jaw: jawForward
            jawLeft
            jawRight
            jawOpen
	:Mouth: mouthClose
            mouthFunnel
            mouthPucker
            mouthLeft
            mouthRight
            mouthSmileLeft
            mouthSmileRight
            mouthFrownLeft
            mouthFrownRight
            mouthDimpleLeft
            mouthDimpleRight
            mouthStretchLeft
            mouthStretchRight
            mouthRollLower
            mouthRollUpper
            mouthShrugUpper
            mouthShrugLower
            mouthPressLeft
            mouthPressRight
            mouthLowerDownLeft
            mouthLowerDownRight
            mouthUpperUpLeft
            mouthUpperUpRight
	:Brow: browDownLeft
            browDownRight
            browInnerUp
            browOuterUpLeft
            browOuterUpRight
	:Cheek: cheekPuff
            cheekSquintLeft
            cheekSquintRight
	:Nose: noseSneerLeft
            noseSneerRight
	:Etc: tongueOut
            mouthNarrow
            lipsSeal
            lipsPart
            tongueTipUp
            smile

Eyes
----

Eyes morph together with the eyelids (which is part of the Head), the following morph targets will move the eyes.

.. admonition:: Target List
	:class: refbox

	:Eyes: eyeBlinkLeft
            eyeBlinkRight
            eyeLookDownLeft
            eyeLookDownRight
            eyeLookInLeft
            eyeLookInRight
            eyeLookOutLeft
            eyeLookOutRight
            eyeLookUpLeft
            eyeLookUpRight
            eyeWideLeft
            eyeWideRight

|

Morph Targets Animations
========================

There is only one animation asset that has facial (morph targets) animations, it is inside the :abbr:`📁Animations\\FacialExpressions (Content\\Charles\\Animations\\FacialExpressions)` folder

.. image:: /images/blendshapes/content-anim-smile-blink.jpg
	:align: center

|

Anim_smile_blink
----------------

There is no skeletal animation data inside :guilabel:`Anim_smile_blink` so the character is not moving, but it has morph target animation of the character smiling and blinking.

The Addictive Setting for this animation asset is set to Local Space.

.. image:: /images/blendshapes/anim-smile-blink-asset-settings.jpg
	:align: center

|

You can use :guilabel:`Anim_smile_blink` inside an Animation Blueprint to add facial expressions to existing animations (blending morph target animation to skeletal animation).

.. image:: /images/blendshapes/anim-smile-blink-anim-blueprint.jpg
	:align: center

|

