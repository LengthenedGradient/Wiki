---
title: Autoloaders
parent: ACF Tutorials
nav_order: 1
---

Autoloaders fulfill the same role as loaders.

We represent the rammer of the autoloader for flexibility.

You can represent many real life autoloaders this way:

carousel type

{% include image.html src="autoloader/carousel.gif" width="25%" %}

bustle type

{% include image.html src="autoloader/bustle.gif" width="25%" %}

The requirements are simple:
- Ammo and autoloader must be parented to the same parent
- Autoloaders must be aligned with their gun within a small tolerance
- Each autoloader can only have one gun and vice versa
- Autoloaders must be atleast as large as the shell they load

# Finding the right size
You can set the size of the autoloader based on the dimensions of the shell, which are present on an ammo crate overlay or in the menu.

{% include image.html src="autoloader/ammo.png" width="50%" %}

# Alignment
You can align the autoloader using PA:

{% include clip.html src="autoloader/align.mp4" %}

Aiming at the autoloader with the menu tool will show a line between the autoloader and the gun's breech. Use this to help align them.

{% include image.html src="autoloader/overlay.png" %}

If you are using AIO, there is a setting called "Reload Angle". Set this to 0.01 (anything non zero) and the AIO will level the gun when reloading, which can be useful for autoloaders.