# Gamepad Reader
 Inputs library for using gamepads and controllers with Blender's Geometry Nodes

 The add-on will create a unlinked, fake user, empty object in your Blend file that has custom properties representing the button presses. The add-on panel (in the "N" panel) will show all the inputs and drivers can be copied from them.

 The "Drive Nodegroup" button will create a Geometry Nodes group with drivers set up to bring controller data directly into the nodegraph for use with Geometry Node setups.

 To add or change the controls to support other controller layouts, just change the section of the init file with the comment "Controls go here". All the UI setup etc will automatically follow the list of inputs in that part of the code. Follow the same code structure as I have used.

# Licensing
 This add-on is licensed as GPL3.0 however the contents of the "Third Parties" folder contains their own license information. The Inputs library has been bundled and is licenced as BSD.