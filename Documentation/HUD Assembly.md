# Roth2 HUD Assembly

The HUD consists of a number of components that are assembled by script
to ensure consistency across grids.

The script is
[r2_hud_maker.lsl](https://github.com/RuthAndRoth/Ruth2/blob/master/Scripts/r2_hud_maker.lsl)
found in the [Ruth2/Scripts](https://github.com/RuthAndRoth/Ruth2/tree/master/Scripts)
directory.  There are also a handful of additional mesh button assemblies used:

* [4x2_button.dae](https://github.com/RuthAndRoth/Ruth2/blob/master/Mesh/HUD/4x2_button.dae)
* [5x1-s_button.dae](https://github.com/RuthAndRoth/Ruth2/blob/master/Mesh/HUD/5x1-s_button.dae)
* [6x1_button.dae](https://github.com/RuthAndRoth/Ruth2/blob/master/Mesh/HUD/6x1_button.dae)
* [8x1_button.dae](https://github.com/RuthAndRoth/Ruth2/blob/master/Mesh/HUD/8x1_button.dae)

These should be uploaded as simple mesh objects with no physics.  They are also
available in the in-world Mesh Uploads distribution boxes found at the usual
RuthAndRoth areas.

There are also a number of texture UUIDs you will need.  The known UUIDs for
Second Life and OSgrid are already in the script, for other grids they need to
be added:

* **hud_texture** - the background to most of the HUD panels
* **skin_texture** - the background for the skin panel
* **alpha_button_texture** - the texture used on the alpha panel's buttons
* **alpha_doll_texture** - the texture of the alpha doll (new flat alpha panel only)

The following have different textures for Ruth2 and Roth2:

* **header_texture** - the top bar of the HUD
* **options_texture** - the background for the options panel
* **fingernails_shape_texture** - the texture for the fingernail shape buttons

The r2_hud_maker.lsl script also has a setting at the top to determine if it
builds a Ruth2 or Roth2 HUD.  Set that accordingly.

## Build the HUD from scratch

* Create a new empty box prim named 'Object'
* Take a copy of the new box into inventory and leave the original on the ground
* Rename the box on the ground "HUD maker"
* Copy the following objects into the inventory of the new box:
  * the new box created above (from inventory) named 'Object'
  * the button meshes: '4x2_button', '5x1-s_button', '6x1_button' and '8x1_button'
  * the r2_hud_maker.lsl script
* Take a copy of the HUD maker box because trying again is much simpler from this
  stage than un-doing what the script is about to do
* Light fuse (touch the HUD maker) and get away, the new HUD will be
  assembled around the box prim which will become the root prim of the HUD.
* Remove the script and the other objects from the HUD root prim and copy in:
  * r2_applier.lsl
  * rX2_hud_control.lsl
  * !CONFIG - the skin texture configuration notecard
* Rename the HUD
* Take the HUD into inventory
* Attach the HUD to a HUD attachment point.  It will position itself so the
  HUD is near the top of the screen, if you manually move it the new position
  will be remembered until the controls cripts is reset.
