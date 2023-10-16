.. meta::
    :keywords: ifstatuseffect ifstatus

.. _Player Combat Checks:


**Player Combat Checks**
=========================
.. note::

  **All of the functions below only work in :doc:`Event </Doc/Manual/Events/Events>` based .json files.**

.. seealso:: 

  For checks that can be used outside of combat, see :ref:`Player Checks`.

**IfPlayerStunnedByParalysis**
-------------------------------
If player is currently stunned by paralysis, jump to the given scene.

.. code-block:: javascript

  "IfPlayerStunnedByParalysis", "SceneNameHere"

----

**IfPlayerIsUsingThisSkill**
-----------------------------
If the player is using the skill this turn, jump to the given scene. For more advanced cases where :ref:`lineTriggers` isn't flexible enough. Check Sofia for it’s usage.

.. code-block:: javascript

  "IfPlayerIsUsingThisSkill", "Demon Layer", "Scene"
