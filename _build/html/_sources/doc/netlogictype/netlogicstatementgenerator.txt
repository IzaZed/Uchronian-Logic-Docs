inherits from: :doc:`../netlogictype`

inherited by: :doc:`../nodes_basic/nlabstractnode`

NetLogicStatementGenerator
===========================================

:samp:`bge_netlogic.basicnodes.NetLogicStatementGenerator` writes
the values for the given cell used in the script run by the UPBGE.

Functions:
-----------

* :samp:`write_cell_declaration()`
    Writes the cell name (ID of the Node) and the value set for this cell.

* :samp:`write_cell_fields_initialization()`
    Writes the values for any Non-Socket Entity within a cell.

* :samp:`write_socket_field_initialization()`

* :samp:`get_nonsocket_fields()`

* :samp:`get_input_sockets_field_names()`

* :samp:`get_field_name_for_socket()`

* :samp:`get_netlogic_class_name()`

* :samp:`_index_of()`

* :samp:`get_linked_socket_field_value()`

* :samp:`get_output_socket_varnames()`

* :samp:`update()`
