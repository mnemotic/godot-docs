.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the EditorFileDialog.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_EditorFileDialog:

EditorFileDialog
================

**Inherits:** :ref:`ConfirmationDialog<class_confirmationdialog>` **<** :ref:`AcceptDialog<class_acceptdialog>` **<** :ref:`WindowDialog<class_windowdialog>` **<** :ref:`Popup<class_popup>` **<** :ref:`Control<class_control>` **<** :ref:`CanvasItem<class_canvasitem>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------



Member Functions
----------------

+--------------------------------------------+-----------------------------------------------------------------------------------------------------+
| void                                       | :ref:`add_filter<class_EditorFileDialog_add_filter>` **(** :ref:`String<class_string>` filter **)** |
+--------------------------------------------+-----------------------------------------------------------------------------------------------------+
| void                                       | :ref:`clear_filters<class_EditorFileDialog_clear_filters>` **(** **)**                              |
+--------------------------------------------+-----------------------------------------------------------------------------------------------------+
| :ref:`VBoxContainer<class_vboxcontainer>`  | :ref:`get_vbox<class_EditorFileDialog_get_vbox>` **(** **)**                                        |
+--------------------------------------------+-----------------------------------------------------------------------------------------------------+
| void                                       | :ref:`invalidate<class_EditorFileDialog_invalidate>` **(** **)**                                    |
+--------------------------------------------+-----------------------------------------------------------------------------------------------------+

Signals
-------

.. _class_EditorFileDialog_dir_selected:

- **dir_selected** **(** :ref:`String<class_string>` dir **)**

Emitted when a directory is selected.

.. _class_EditorFileDialog_file_selected:

- **file_selected** **(** :ref:`String<class_string>` path **)**

Emitted when a file is selected.

.. _class_EditorFileDialog_files_selected:

- **files_selected** **(** :ref:`PoolStringArray<class_poolstringarray>` paths **)**

Emitted when multiple files are selected.


Member Variables
----------------

  .. _class_EditorFileDialog_access:

- :ref:`int<class_int>` **access** - The location from which the user may select a file, including ``res://``, ``user://``, and the local file system.

  .. _class_EditorFileDialog_current_dir:

- :ref:`String<class_string>` **current_dir** - The currently occupied directory.

  .. _class_EditorFileDialog_current_file:

- :ref:`String<class_string>` **current_file** - The currently selected file.

  .. _class_EditorFileDialog_current_path:

- :ref:`String<class_string>` **current_path** - The file system path in the address bar.

  .. _class_EditorFileDialog_disable_overwrite_warning:

- :ref:`bool<class_bool>` **disable_overwrite_warning** - If ``true`` the ``EditorFileDialog`` will not warn the user before overwriting files.

  .. _class_EditorFileDialog_display_mode:

- :ref:`int<class_int>` **display_mode** - The view format in which the ``EditorFileDialog`` displays resources to the user.

  .. _class_EditorFileDialog_mode:

- :ref:`int<class_int>` **mode** - The purpose of the ``EditorFileDialog``. Changes allowed behaviors.

  .. _class_EditorFileDialog_show_hidden_files:

- :ref:`bool<class_bool>` **show_hidden_files** - If ``true`` hidden files and directories will be visible in the ``EditorFileDialog``.


Numeric Constants
-----------------

- **MODE_OPEN_FILE** = **0** --- The ``EditorFileDialog`` can select only one file. Accepting the window will open the file.
- **MODE_OPEN_FILES** = **1** --- The ``EditorFileDialog`` can select multiple files. Accepting the window will open all files.
- **MODE_OPEN_DIR** = **2** --- The ``EditorFileDialog`` can select only one directory. Accepting the window will open the directory.
- **MODE_OPEN_ANY** = **3** --- The ``EditorFileDialog`` can select a file or directory. Accepting the window will open it.
- **MODE_SAVE_FILE** = **4** --- The ``EditorFileDialog`` can select only one file. Accepting the window will save the file.
- **ACCESS_RESOURCES** = **0** --- The ``EditorFileDialog`` can only view ``res://`` directory contents.
- **ACCESS_USERDATA** = **1** --- The ``EditorFileDialog`` can only view ``user://`` directory contents.
- **ACCESS_FILESYSTEM** = **2** --- The ``EditorFileDialog`` can view the entire local file system.
- **DISPLAY_THUMBNAILS** = **0** --- The ``EditorFileDialog`` displays resources as thumbnails.
- **DISPLAY_LIST** = **1** --- The ``EditorFileDialog`` displays resources as a list of filenames.

Member Function Description
---------------------------

.. _class_EditorFileDialog_add_filter:

- void **add_filter** **(** :ref:`String<class_string>` filter **)**

Adds a comma-delimited file extension filter option to the ``EditorFileDialog`` with an optional semi-colon-delimited label.

Example: "\*.tscn, \*.scn; Scenes", results in filter text "Scenes (\*.tscn, \*.scn)".

.. _class_EditorFileDialog_clear_filters:

- void **clear_filters** **(** **)**

Removes all filters except for "All Files (\*)".

.. _class_EditorFileDialog_get_vbox:

- :ref:`VBoxContainer<class_vboxcontainer>` **get_vbox** **(** **)**

Returns the ``VBoxContainer`` used to display the file system.

.. _class_EditorFileDialog_invalidate:

- void **invalidate** **(** **)**

Notify the ``EditorFileDialog`` that its view of the data is no longer accurate. Updates the view contents on next view update.


