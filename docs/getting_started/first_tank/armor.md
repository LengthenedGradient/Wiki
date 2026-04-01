---
title: Armor
parent: Your First Tank
nav_order: 8
---

# Armor
You can use armor to protect your vehicle from munitions.

{% include clip.html src="armor/demo.mp4" %}

## Thickness
Higher penetration threats require thicker effective armor to defeat.

In the clip above, 100mm is more than thick enough to stop a machine gun, but it is not enough for the high penetration rounds from a cannon.

Effective armor is the "line of sight" thickness that the bullet must pass through.

{% include image.html src="armor/effective.png" %}

A thinner angled plate can have the same effective thickness as a thicker flat plate.

{% include clip.html src="armor/angle.mp4" %}

> If you are interested, you can calculate effective armor with this formula:
>
> $$
> \text{Effective Armor} = \frac{\text{Nominal Thickness}}{\sin(\theta)}
> $$

Tanks generally concentrate most of their armor at the front, then the sides, then the rear/roof/floor.

## Health (Ductility)
With the same thickness, a healthier prop will last longer under attack.

Setting the ductility of a prop can change its health at the cost of weight, or vice versa.

{% include clip.html src="armor/health.mp4" %}

# Armor Tool
Using the ACF armor tool, you can set the thickness and ductility of a prop:

{% include clip.html src="armor/tool.mp4" %}

# Armor Setup
We will begin armoring the tank we worked on. If you want to follow along, download this dupe:

{% include file.html src="checkpoint1.txt" text="Checkpoint 1" %}

The upper/lower front plates are angled at 30 degrees from horizontal. With how triangles work, this results in a height of exactly 42.

You can count the squares on the sprops to figure out their sizes. Follow along.

{% include image.html src="armor/setup1.png" %}

Make sure to parent all these props to the hull.

{% include image.html src="armor/setup2.png" %}

{% include image.html src="armor/setup3.png" %}

{% include image.html src="armor/setup4.png" %}

Then multiparent all these props to the horizontal turret ring

{% include image.html src="armor/setup5.png" %}

{% include file.html src="checkpoint1.txt" text="Checkpoint 2" %}

# Visual Clipping
Propper clipping (aka visual clipping) is a tool that lets you "clip" off parts of a prop, both visually and for acf projectiles.

`LEFT CLICK` on the plate you are clipping along, then `LEFT CLICK` on the plate you want to clip, then press `RIGHT CLICK` to complete the clip.

Try applying it to the front like so:

{% include clip.html src="armor/clipping.mp4" %}

Then apply it to the turret:

{% include image.html src="armor/setup6.png" %}

# Armoring
> Tanks generally concentrate most of their armor at the front, then the sides, then the rear/roof/floor.

I have colored the tank to reflect this, with red for the highest concentration of armor, orange for less and green for least.

{% include image.html src="armor/color.png" %}

Now try using the armor tool:

We suggest using:
- `100mm 0 ductility` on the front
- `50mm -40 ductility` on the sides
- `30mm -40 ductility` on the roof and rear

{% include clip.html src="armor/armoring.mp4" %}

{% include file.html src="checkpoint1.txt" text="Checkpoint 3" %}