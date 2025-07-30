---
title: Google Earth Studio Interface Orientation
nav: Google Earth Studio
gallery: true
---

<br>

{% include gallery-figure.html img="ges_geo_vis_12.jpg" alt="A detailed map view displays a landscape with various geographical features, including green areas, mountains, and bodies of water. On the left, there is a panel showing attributes such as longitude, latitude, and altitude, with specific values: longitude -118.112, latitude 48.537, and altitude 616 km. The panel also lists camera rotation attributes for pan and tilt. At the bottom, a timeline with numbered intervals is visible, featuring several plotted points along it." caption="Basic GES interface with single, expanded camera view." %}

The conventional orientation controls are replaced with the following geographic analogues:

- Latitude = Y position (north-south)
- Longitude = X position (east-west)
- Altitude = Z position (elevation)
- Pan = Y rotation
- Tilt = Z rotation

Movement is established by creating keyframes that manipulate these characteristics along the timeline. The quick key to generate a keyframe is `control + Enter`. One thing that takes a little getting used to is that you either have the timeline or display section selected. If you would like to add changes, you need to scroll forward, select the display, make your adjustments and then add keyframes. If you forget to add keyframes and select back into the timeline, those changes aren’t recorded. Select `File>Import>KML File` to import labels and shapes.

One important thing to keep in mind is that you need to give the viewer long enough to read the labels of destination. In the case of the single destination, we will be stopping briefly to read and for the line and polygon, we will be slowing down quite a bit for visual legibility. The easiest way to make one of these stops is simply to copy your keyframes from the timeline, move a couple of seconds down and then paste. I find that it is more natural and dynamic to have a very slight movement during these reading pauses than a completely static, robotic shot, so I will subtly pan left or right or tilt up or down by selecting the display and adjusting tilt and pan slightly with the `Shift + Arrow` keys, then `Control + Enter` to record these changes / updating your keyframe information.


