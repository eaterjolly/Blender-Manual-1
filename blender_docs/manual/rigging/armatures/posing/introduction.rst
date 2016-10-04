..    TODO/Review: {{review|partial=X}}.

************
Introduction
************

Once your armature is :doc:`skinned </rigging/armatures/skinning/index>` by the needed object(s), you can start to pose it.
Basically, by transforming its bones, you deform or transform the skin object(s).
But you do not do that in *Edit Mode* - remember that in this mode, you edit *the default, base,
"rest" position of your armature*. You cannot use the *Object Mode* either,
as here you can only transform whole objects...

So, armatures in Blender have a third mode, *Pose*, dedicated to this process.
It is a sort of "object mode for bones". In rest position (as edited in *Edit Mode*),
each bone has its own position/rotation/scale to neutral values
(i.e. 0.0 for position and rotation, and 1.0 for scale).
Hence, when you edit a bone in *Pose Mode*,
you create an offset in its transform properties, from its rest position --
this is quite similar to :doc:`meshes relative shape keys </animation/shape_keys/index>`, in fact.


Posing Section Overview
=======================

In this section, we will see:

- The :doc:`visualization features </rigging/armatures/posing/visualization>` specific to *Pose Mode*.
- How to :doc:`select and edit bones </rigging/armatures/posing/editing>` in this mode.
- How to :doc:`use pose library </rigging/armatures/properties/pose_library>`.
- How to :doc:`use constraints </rigging/armatures/posing/constraints>` to control your bones' DoF (degrees of freedom).
- How to :doc:`use inverse kinematics features </rigging/armatures/posing/inverse_kinematics/index>`.
- How to :doc:`use the Spline inverse kinematics features </rigging/armatures/posing/inverse_kinematics/spline_ik>`.

Even though it might be used for completely static purposes,
posing is heavily connected with :doc:`animation features and techniques </animation/index>`.

In this part, we will try to focus on animation-independent posing, but this is not always possible.
So if you know nothing about animation in Blender,
it might be a good idea to read the :doc:`animation features and techniques </animation/index>` chapter first,
and then come back here.