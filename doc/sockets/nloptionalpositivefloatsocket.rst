inherits from: :doc:`../netlogicsockettype`, `bpy.types.NodeSocket`_.

.. _bpy.types.NodeSocket: https://docs.blender.org/api/current/bpy.types.NodeSocket.html?highlight=nodesocket#bpy.types.NodeSocket

NLSocketOptionalPositiveFloat
===========================================

:samp:`bge_netlogic.basicnodes.NLSocketOptionalPositiveFloat`

Attributes:
-----------

* :samp:`bl_idname`

* :samp:`bl_label`

* :samp:`value`
    ``bpy.props.StringProperty``

* :samp:`value_type`
    ``bpy.props.EnumProperty`` listing items in
    ``bge_netlogic.basicnodes._enum_optional_positive_float_value_types``

* :samp:`float_editor`
    ``bpy.props.FloatProperty``
        ``min``: 0


Functions:
-----------

* :samp:`draw_color()`

* :samp:`draw()`

* :samp:`get_unlinked_value()`
