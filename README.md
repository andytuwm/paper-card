paper-card
=============

A webcomponents custom card element taking design inspiration from [Polymer](https://www.polymer-project.org).

Installation
===
Install through bower:

Add `"paper-card": "andytuwm/paper-card#latest"` to bower.json

Attributes
===
######zdepth
type: `int`
default: `1`

The z-depth of the shadow of the card, from 0-5.
Setting this property after element creation has no effect. Use setZ() instead.

######enableHover
type: `boolean`
default: `false`

Set to true for a shadow increase on-hover effect.

######animated
type: `boolean`
default: `true`

Set to true to animate the shadow transition when setting a new zdepth.

######noink

Add this attribute to paper-card to prevent a ripple effect from showing on click.

######enableOverlay
type: `boolean`
default: `false`

Set to true to show a shaded overlay on mouse hover.

######overlayImage
type: `string`
default: `""`

To add an image to the overlay, specify path to an image to this attribute.
`enableOverlay` must be set to true in order for the image to show.

Methods
===
######setZ(int)

Set the z-depth of the shadow. This should be used after element
creation instead of setting the z property directly.