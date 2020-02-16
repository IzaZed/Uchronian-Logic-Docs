inherits from: :doc:`../netlogicsockettype`, `bpy.types.NodeSocket`_.

.. _bpy.types.NodeSocket: https://docs.blender.org/api/current/bpy.types.NodeSocket.html?highlight=nodesocket#bpy.types.NodeSocket

NLSocketLoopCount
===========================================

:samp:`bge_netlogic.basicnodes.NLSocketLoopCount`

Attributes:
-----------

* :samp:`bl_idname`

* :samp:`bl_label`

* :samp:`value`
    ``bpy.props.StringProperty``

* :samp:`value_type`
    ``bpy.props.EnumProperty`` listing item in
    ``bge_netlogic.basicnodes._enum_loop_count_values``

* :samp:`integer_editor`
    ``bpy.props.IntProperty``
        ``min``: 1

Functions:
-----------

* :samp:`draw_color()`

* :samp:`draw()`

* :samp:`get_unlinked_value()`
