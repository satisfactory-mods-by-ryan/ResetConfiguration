# ResetConfiguration

This is an example implementation of a "Reset to Defaults" button used in my mods.

The button occupies the Custom Widget slot in the Configuration. When clicked, it resets all configuration values to those defined in the Configuration CDO.

Currently, it reconstructs each property in a manner similar to how the mod configuration page is opened. This can cause a brief visual blip lasting a frame or two, but overall, it functions correctly. Could look into updating the values directly rather than reconstructing them.
