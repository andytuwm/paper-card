paper-card
=============

A card taking design inspiration from [Polymer](https://www.polymer-project.org).

Install
===
Install through bower:

Add `"paper-card": "andytuwm/paper-card#latest"` to bower.json

Attributes
===
######zdepth    type:`int`     default:`1`

The z-depth of the shadow of the card, from 0-5.
Setting this property after element creation has no effect. Use setZ() instead.

######enableHover    type:`boolean`     default:`false`

Set to true for a shadow increase on-hover effect.

######animated    `boolean`     default:`true`

Set to true to animate the shadow transition when setting a new zdepth

Methods
===
######setZ()

Set the z-depth of the shadow. This should be used after element
creation instead of setting the z property directly.