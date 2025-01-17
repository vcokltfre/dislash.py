.. currentmodule:: dislash.slash_commands

SlashClient and Checks
======================

.. _slash_client:

SlashClient
-----------

.. autoclass:: SlashClient

    .. automethod:: event

    .. automethod:: command

    .. automethod:: get_global_command

    .. automethod:: get_global_command_named

    .. automethod:: get_guild_command

    .. automethod:: get_guild_command_named

    .. automethod:: get_guild_commands

    .. automethod:: fetch_global_commands

    .. automethod:: fetch_guild_commands

    .. automethod:: fetch_global_command

    .. automethod:: fetch_guild_command

    .. automethod:: register_global_slash_command

    .. automethod:: register_guild_slash_command

    .. automethod:: edit_global_slash_command

    .. automethod:: edit_guild_slash_command

    .. automethod:: delete_global_slash_command

    .. automethod:: delete_guild_slash_command

    .. automethod:: overwrite_global_commands

    .. automethod:: overwrite_guild_commands

    .. automethod:: delete_global_commands

    .. automethod:: delete_guild_commands

    .. automethod:: fetch_global_command_named

    .. automethod:: fetch_guild_command_named

    .. automethod:: edit_global_command_named

    .. automethod:: edit_guild_command_named

    .. automethod:: delete_global_command_named

    .. automethod:: delete_guild_command_named

    .. automethod:: fetch_guild_command_permissions

    .. automethod:: batch_fetch_guild_command_permissions

    .. automethod:: edit_guild_command_permissions

    .. automethod:: batch_edit_guild_command_permissions




.. _slash_checks:

Checks
------

.. autofunction:: check

.. autofunction:: check_any

.. autofunction:: cooldown

.. autofunction:: has_role

.. autofunction:: has_any_role

.. autofunction:: has_permissions

.. autofunction:: has_guild_permissions

.. autofunction:: dm_only

.. autofunction:: guild_only

.. autofunction:: is_owner

.. autofunction:: is_nsfw

.. autofunction:: bot_has_role

.. autofunction:: bot_has_any_role

.. autofunction:: bot_has_permissions

.. autofunction:: bot_has_guild_permissions
