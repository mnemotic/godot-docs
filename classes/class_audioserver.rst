.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the AudioServer.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_AudioServer:

AudioServer
===========

**Inherits:** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

Server interface for low level audio access.

Member Functions
----------------

+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`add_bus<class_AudioServer_add_bus>` **(** :ref:`int<class_int>` at_position=-1 **)**                                                                                            |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`add_bus_effect<class_AudioServer_add_bus_effect>` **(** :ref:`int<class_int>` bus_idx, :ref:`AudioEffect<class_audioeffect>` effect, :ref:`int<class_int>` at_position=-1 **)** |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`AudioBusLayout<class_audiobuslayout>`  | :ref:`generate_bus_layout<class_AudioServer_generate_bus_layout>` **(** **)** const                                                                                                   |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                        | :ref:`get_bus_count<class_AudioServer_get_bus_count>` **(** **)** const                                                                                                               |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`AudioEffect<class_audioeffect>`        | :ref:`get_bus_effect<class_AudioServer_get_bus_effect>` **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` effect_idx **)**                                                   |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                        | :ref:`get_bus_effect_count<class_AudioServer_get_bus_effect_count>` **(** :ref:`int<class_int>` bus_idx **)**                                                                         |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                        | :ref:`get_bus_index<class_AudioServer_get_bus_index>` **(** :ref:`String<class_string>` bus_name **)** const                                                                          |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_string>`                  | :ref:`get_bus_name<class_AudioServer_get_bus_name>` **(** :ref:`int<class_int>` bus_idx **)** const                                                                                   |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                    | :ref:`get_bus_peak_volume_left_db<class_AudioServer_get_bus_peak_volume_left_db>` **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` channel **)** const                      |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                    | :ref:`get_bus_peak_volume_right_db<class_AudioServer_get_bus_peak_volume_right_db>` **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` channel **)** const                    |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_string>`                  | :ref:`get_bus_send<class_AudioServer_get_bus_send>` **(** :ref:`int<class_int>` bus_idx **)** const                                                                                   |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                    | :ref:`get_bus_volume_db<class_AudioServer_get_bus_volume_db>` **(** :ref:`int<class_int>` bus_idx **)** const                                                                         |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`                    | :ref:`get_mix_rate<class_AudioServer_get_mix_rate>` **(** **)** const                                                                                                                 |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                        | :ref:`get_speaker_mode<class_AudioServer_get_speaker_mode>` **(** **)** const                                                                                                         |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                      | :ref:`is_bus_bypassing_effects<class_AudioServer_is_bus_bypassing_effects>` **(** :ref:`int<class_int>` bus_idx **)** const                                                           |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                      | :ref:`is_bus_effect_enabled<class_AudioServer_is_bus_effect_enabled>` **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` effect_idx **)** const                               |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                      | :ref:`is_bus_mute<class_AudioServer_is_bus_mute>` **(** :ref:`int<class_int>` bus_idx **)** const                                                                                     |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                      | :ref:`is_bus_solo<class_AudioServer_is_bus_solo>` **(** :ref:`int<class_int>` bus_idx **)** const                                                                                     |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`lock<class_AudioServer_lock>` **(** **)**                                                                                                                                       |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`move_bus<class_AudioServer_move_bus>` **(** :ref:`int<class_int>` index, :ref:`int<class_int>` to_index **)**                                                                   |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`remove_bus<class_AudioServer_remove_bus>` **(** :ref:`int<class_int>` index **)**                                                                                               |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`remove_bus_effect<class_AudioServer_remove_bus_effect>` **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` effect_idx **)**                                             |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_bus_bypass_effects<class_AudioServer_set_bus_bypass_effects>` **(** :ref:`int<class_int>` bus_idx, :ref:`bool<class_bool>` enable **)**                                     |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_bus_count<class_AudioServer_set_bus_count>` **(** :ref:`int<class_int>` amount **)**                                                                                        |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_bus_effect_enabled<class_AudioServer_set_bus_effect_enabled>` **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` effect_idx, :ref:`bool<class_bool>` enabled **)**  |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_bus_layout<class_AudioServer_set_bus_layout>` **(** :ref:`AudioBusLayout<class_audiobuslayout>` bus_layout **)**                                                            |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_bus_mute<class_AudioServer_set_bus_mute>` **(** :ref:`int<class_int>` bus_idx, :ref:`bool<class_bool>` enable **)**                                                         |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_bus_name<class_AudioServer_set_bus_name>` **(** :ref:`int<class_int>` bus_idx, :ref:`String<class_string>` name **)**                                                       |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_bus_send<class_AudioServer_set_bus_send>` **(** :ref:`int<class_int>` bus_idx, :ref:`String<class_string>` send **)**                                                       |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_bus_solo<class_AudioServer_set_bus_solo>` **(** :ref:`int<class_int>` bus_idx, :ref:`bool<class_bool>` enable **)**                                                         |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`set_bus_volume_db<class_AudioServer_set_bus_volume_db>` **(** :ref:`int<class_int>` bus_idx, :ref:`float<class_float>` volume_db **)**                                          |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`swap_bus_effects<class_AudioServer_swap_bus_effects>` **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` effect_idx, :ref:`int<class_int>` by_effect_idx **)**          |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                         | :ref:`unlock<class_AudioServer_unlock>` **(** **)**                                                                                                                                   |
+----------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Signals
-------

.. _class_AudioServer_bus_layout_changed:

- **bus_layout_changed** **(** **)**

Emitted when the :ref:`AudioBusLayout<class_audiobuslayout>` changes.


Numeric Constants
-----------------

- **SPEAKER_MODE_STEREO** = **0** --- Two or fewer speakers are detected.
- **SPEAKER_SURROUND_51** = **2** --- A 5.1 channel surround setup detected.
- **SPEAKER_SURROUND_71** = **3** --- A 7.1 channel surround setup detected.

Description
-----------

AudioServer is a low level server interface for audio access. It is in charge of creating sample data (playable audio) as well as its playback via a voice interface.

Member Function Description
---------------------------

.. _class_AudioServer_add_bus:

- void **add_bus** **(** :ref:`int<class_int>` at_position=-1 **)**

Adds a bus at ``at_position``.

.. _class_AudioServer_add_bus_effect:

- void **add_bus_effect** **(** :ref:`int<class_int>` bus_idx, :ref:`AudioEffect<class_audioeffect>` effect, :ref:`int<class_int>` at_position=-1 **)**

Adds an :ref:`AudioEffect<class_audioeffect>` effect to the bus ``bus_idx`` at ``at_position``.

.. _class_AudioServer_generate_bus_layout:

- :ref:`AudioBusLayout<class_audiobuslayout>` **generate_bus_layout** **(** **)** const

Generates an :ref:`AudioBusLayout<class_audiobuslayout>` using the available busses and effects.

.. _class_AudioServer_get_bus_count:

- :ref:`int<class_int>` **get_bus_count** **(** **)** const

Returns the number of available busses.

.. _class_AudioServer_get_bus_effect:

- :ref:`AudioEffect<class_audioeffect>` **get_bus_effect** **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` effect_idx **)**

Returns the :ref:`AudioEffect<class_audioeffect>` at position ``effect_idx`` in bus ``bus_idx``.

.. _class_AudioServer_get_bus_effect_count:

- :ref:`int<class_int>` **get_bus_effect_count** **(** :ref:`int<class_int>` bus_idx **)**

Returns the number of effects on the bus at ``bus_idx``.

.. _class_AudioServer_get_bus_index:

- :ref:`int<class_int>` **get_bus_index** **(** :ref:`String<class_string>` bus_name **)** const

Returns the index of the bus with the name ``bus_name``.

.. _class_AudioServer_get_bus_name:

- :ref:`String<class_string>` **get_bus_name** **(** :ref:`int<class_int>` bus_idx **)** const

Returns the name of the bus with the index ``bus_idx``.

.. _class_AudioServer_get_bus_peak_volume_left_db:

- :ref:`float<class_float>` **get_bus_peak_volume_left_db** **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` channel **)** const

Returns the peak volume of the left speaker at bus index ``bus_idx`` and channel index ``channel``.

.. _class_AudioServer_get_bus_peak_volume_right_db:

- :ref:`float<class_float>` **get_bus_peak_volume_right_db** **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` channel **)** const

Returns the peak volume of the right speaker at bus index ``bus_idx`` and channel index ``channel``.

.. _class_AudioServer_get_bus_send:

- :ref:`String<class_string>` **get_bus_send** **(** :ref:`int<class_int>` bus_idx **)** const

Returns the name of the bus that the bus at index ``bus_idx`` sends to.

.. _class_AudioServer_get_bus_volume_db:

- :ref:`float<class_float>` **get_bus_volume_db** **(** :ref:`int<class_int>` bus_idx **)** const

Returns the volume of the bus at index ``bus_idx`` in dB.

.. _class_AudioServer_get_mix_rate:

- :ref:`float<class_float>` **get_mix_rate** **(** **)** const

Returns the sample rate at the output of the audioserver.

.. _class_AudioServer_get_speaker_mode:

- :ref:`int<class_int>` **get_speaker_mode** **(** **)** const

Returns the speaker configuration.

.. _class_AudioServer_is_bus_bypassing_effects:

- :ref:`bool<class_bool>` **is_bus_bypassing_effects** **(** :ref:`int<class_int>` bus_idx **)** const

If ``true`` the bus at index ``bus_idx`` is bypassing effects.

.. _class_AudioServer_is_bus_effect_enabled:

- :ref:`bool<class_bool>` **is_bus_effect_enabled** **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` effect_idx **)** const

If ``true`` the effect at index ``effect_idx`` on the bus at index ``bus_idx`` is enabled.

.. _class_AudioServer_is_bus_mute:

- :ref:`bool<class_bool>` **is_bus_mute** **(** :ref:`int<class_int>` bus_idx **)** const

If ``true`` the bus at index ``bus_idx`` is muted.

.. _class_AudioServer_is_bus_solo:

- :ref:`bool<class_bool>` **is_bus_solo** **(** :ref:`int<class_int>` bus_idx **)** const

If ``true`` the bus at index ``bus_idx`` is in solo mode.

.. _class_AudioServer_lock:

- void **lock** **(** **)**

Locks the audio drivers mainloop. Remember to unlock it afterwards.

.. _class_AudioServer_move_bus:

- void **move_bus** **(** :ref:`int<class_int>` index, :ref:`int<class_int>` to_index **)**

Moves the bus from index ``index`` to index ``to_index``.

.. _class_AudioServer_remove_bus:

- void **remove_bus** **(** :ref:`int<class_int>` index **)**

Removes the bus at index ``index``.

.. _class_AudioServer_remove_bus_effect:

- void **remove_bus_effect** **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` effect_idx **)**

Removes the effect at index ``effect_idx`` from the bus at index ``bus_idx``.

.. _class_AudioServer_set_bus_bypass_effects:

- void **set_bus_bypass_effects** **(** :ref:`int<class_int>` bus_idx, :ref:`bool<class_bool>` enable **)**

If ``true`` the bus at index ``bus_idx`` is bypassing effects.

.. _class_AudioServer_set_bus_count:

- void **set_bus_count** **(** :ref:`int<class_int>` amount **)**

Adds and removes busses to make the number of busses match ``amount``.

.. _class_AudioServer_set_bus_effect_enabled:

- void **set_bus_effect_enabled** **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` effect_idx, :ref:`bool<class_bool>` enabled **)**

If ``true`` the effect at index ``effect_idx`` on the bus at index ``bus_idx`` is enabled.

.. _class_AudioServer_set_bus_layout:

- void **set_bus_layout** **(** :ref:`AudioBusLayout<class_audiobuslayout>` bus_layout **)**

Overwrites the currently used :ref:`AudioBusLayout<class_audiobuslayout>`.

.. _class_AudioServer_set_bus_mute:

- void **set_bus_mute** **(** :ref:`int<class_int>` bus_idx, :ref:`bool<class_bool>` enable **)**

If ``true`` the bus at index ``bus_idx`` is muted.

.. _class_AudioServer_set_bus_name:

- void **set_bus_name** **(** :ref:`int<class_int>` bus_idx, :ref:`String<class_string>` name **)**

Sets the name of the bus at index ``bus_idx`` to ``name``.

.. _class_AudioServer_set_bus_send:

- void **set_bus_send** **(** :ref:`int<class_int>` bus_idx, :ref:`String<class_string>` send **)**

Connects the output of the bus at ``bus_idx`` to the bus named ``send``.

.. _class_AudioServer_set_bus_solo:

- void **set_bus_solo** **(** :ref:`int<class_int>` bus_idx, :ref:`bool<class_bool>` enable **)**

If ``true`` the bus at index ``bus_idx`` is in solo mode.

.. _class_AudioServer_set_bus_volume_db:

- void **set_bus_volume_db** **(** :ref:`int<class_int>` bus_idx, :ref:`float<class_float>` volume_db **)**

Sets the volume of the bus at index ``bus_idx`` to ``volume_db``.

.. _class_AudioServer_swap_bus_effects:

- void **swap_bus_effects** **(** :ref:`int<class_int>` bus_idx, :ref:`int<class_int>` effect_idx, :ref:`int<class_int>` by_effect_idx **)**

Swaps the position of two effects in bus ``bus_idx``.

.. _class_AudioServer_unlock:

- void **unlock** **(** **)**

Unlocks the audiodriver's main loop. After locking it always unlock it.


