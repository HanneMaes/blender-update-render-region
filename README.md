# Blender Update Render Region
My Blender compositing setup that renders a region and overlays it on the full frame.<br>
So you don't have to re-render the whole frame after making small adjustments.

<img src="node tree.png">

1. ```F12``` to render the full frame and ```alt+s``` to save the image.
2. Open the saved render in the image node.
3. Select a region to update with **render region** ```ctrl+B```.
4. Now on rendering the only selected region will render and be overlayed.
5. Disable by **unchecking** ```Output Properties > Render Region```.