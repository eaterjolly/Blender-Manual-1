
*****
Inset
*****

.. admonition:: Reference
   :class: refbox

   | Mode:     Edit Mode
   | Menu:     :menuselection:`Mesh --> Faces --> Inset`
   | Hotkey:   :kbd:`I`


This tool takes the currently selected faces and creates an inset of them,
with adjustable thickness and depth. The tool is modal, such that when you activate it,
you may adjust the thickness with your mouse position. You may also adjust the depth of the
inset during the modal operation by holding :kbd:`Ctrl`.

.. list-table::

   * - .. figure:: /images/mesh_tool_inset_before.png
          :width: 320px

          Selection to inset.

     - .. figure:: /images/mesh_tool_inset_after.png
          :width: 320px

          Selection with inset.


Options
=======

.. figure:: /images/mesh_tool_inset_settings.png

   Inset Operator Settings.

Boundary
   Determines whether open edges will be inset or not.
Offset Even
   Scale the offset to give more even thickness.
Offset Relative
   Scale the offset by surrounding geometry.
Thickness
   Set the size of the inset.
Depth
   Raise or lower the newly inset faces to add depth.
Outset
   Create an outset rather than an inset.
Select Outer
   Toggle which side of the inset is selected after operation.
