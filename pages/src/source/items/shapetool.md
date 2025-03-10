---
title: Shape Tool
layout: default
---
# Shape Tool

<div class="infobox box text-center">
    <p style="text-align:center;"><img src="../../assets/images/icons/minecolonies/shape_tool.png" alt="Shapetool"></p>
    <recipe>shapetool</recipe>
</div>
<br>

The shape tool is creative-only when using Structurize alone, but can be used in survival with MineColonies as well.

Have you ever wanted to have your {% worker_link builder %} just dig out a hole, fill in a hole, flatten terrain, or even construct a basic room or other simple shape for you? Then the shape tool may be for you.

### Step One

The first step is to craft a shape tool.
<br>

### Step Two

Then right-click any block in the world as a starting point (similar to the [Build Tool](../../source/items/buildtool)).

### Step Three

Use the GUI to configure, resize, and reposition your desired shape.

![Shape Tool GUI](../../assets/images/gui/shape_tool_gui.png)

* **CUBE**: click this to open a menu (or use the arrows to cycle between) the following different shape options:
    * **CUBE**: a full cube
    * **SPHERE**: a spherical shape of blocks (this may still resemble a cube at small sizes)
    * **HALF_SPHERE**: a dome shape -- flat on the bottom, spherical on top
    * **BOWL**: an inverse dome -- flat on top, spherical on bottom
    * **WAVE**: a 2D sine wave -- this can look very different depending on settings (it can be used to make stairs, channels, and many other things)
    * **WAVE_3D**: a 3D sine wave
    * **DIAMOND**: a diamond shape, or double-ended pyramid
    * **PYRAMID**: a pyramid shape, or top-half diamond
    * **UPSIDE_DOWN_PYRAMID**: an upside-down pyramid shape, or bottom-half diamond
    * **CYLINDER**: a cylindrical shape (circular cross-section from above)
    * **RANDOM**: a shape generated from an equation

* **Pick Main Block**: click this button (not the block itself underneath it!) to select the block that goes on the outside edges of the shape. You can select AIR if you want to dig out the shape, or select a particular block to fill in with that block.
* **Pick Fill Block**: same as above, but this defines the block that goes inside the shape (if it's solid). Not all shapes use a fill block. You can select AIR if you want to dig out the interior of the shape, or select a particular block to fill it.
* **Solid**: click this to toggle between Solid and Hollow, which controls what happens inside the shape. Note that Hollow is not the same as Solid with Fill=AIR -- it will leave any existing interior blocks alone.
* **Height/Width/Length/Frequency**: either enter a value or click the +/- buttons here to adjust the size of the shape. Different shapes may have different settings or use them slightly differently.
* **Arrows**: similar to the Build Tool, use these buttons to reposition or rotate the shape.
* **Red X**: click this to cancel the build entirely.

You can also press ESC to exit the GUI but keep the shape preview visible, so you can move around and see if it fits. Right-click the shape tool in the air to re-open the GUI.

### Step Four

Once you have the shape configured and positioned to your satisfaction, you can click the **green tick** to ask your Builder to begin construction. (They will, of course, need to be supplied with all of the necessary materials.) This is a decoration build without a hut block to control it; so if you want to cancel the build in progress, you will need to do so at the {% building_link townhall %}.

If you're in creative mode, you can alternatively click the **blue paste button** to instantly place the shape for free. This is also what happens when clicking the green tick when MineColonies is not installed.

(The undo button is also creative-only and works the same way as in the [Scan Tool](../../source/items/scantool) -- it reverts the most recent paste.)
