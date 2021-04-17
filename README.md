# Modular Apple Watch Dock / Charging Stand

There are lots of parts here, but a working base only needs 4 printed parts, a base, charger mount, a claw, and a screw. The mini version is only 2 printed parts. Nothing else is needed.

Version 2 uses an adjustable stop for the charger mount. You'll need to print this stop if using V2 or alternatively use an M4 screw with a shim to clamp the charger mount in place. There are versions of the bases that have holes for mounting feet or magnets on the bottom and versions with no holes. The holes were sized to fits some 3mm x 6mm neodymium magnets I have. The `foot.stl` part can also be pressed into the holes. If you don't want feet or magnets, or you want to use adhesive feet/pads of some sort then use the no-holes version.

The cradle part is optional. My 44mm v6 watch doesn't need it. Maybe it could help with the 40mm, or use V2 which can be adjusted for the size of your watch. ¯\\_(ツ)_/¯

Both versions of the claw have worked well for me. The jointed claw may be delicate. The jointed claw has a slightly larger gap where the cable should pass through. There is a mark (a small rounded slot) showing where the wire should go.

How to Print
---
Use whatever layer hieght you want. Infill as low as 10% has worked fine in my prototypes, with the exception of the V2 charger mount when using the shim to clamp it in place. Small holes were added to the clamping areas. The walls for the holes serve as inner support and I use 4 walls on that part for added strength.

I have printed all of the parts at 0.28 mm layer height and everything looked and printed fine. I print the charger mount thread side up, the base with its top side down (I have printed it with the feet side down using supports and that worked fine as well).

You want good layer adhesion for the claw. I raised my usual print temperature a bit which made the claw less prone to breakage, but you want good cooling as well so the parts don’t fuse together too much. Some early iterations of the part were prone to breakage, but I've had no issues with the later ones, and I’ve printed quite a few. The claw is small and prints fast, in case you need to do a little trial and error or if you break it. I like to losen up the joints a bit before intalling the jointed claw, which I do by pressing inward near the joint. If you press in at the end of the finger then you are more likely to break break it.

---

There is a repo for this design on on my [Github](https://github.com/opcow?tab=repositories).

---
|Filename   |Description   | Required?  |
|---|---|---|
|`base-*.stl`|The dock base.|Yes.|
|`charger-mount-*.stl`|Holds the magnetic charger. The watch hangs here. |Yes. Any one.|
|`clamp.stl`|Holds the charging base for the mini dock.|Yes for the mini.|
|`cradle-v1.stl`|Optional peice the sits between the watch and the base.|No.|
|`foot.stl`|A small foot for the base.|No.|
|`*-claw.stl`|Clamps the charger into the charger mount.|Required for V1 and V2.|
|`screw-*.stl`|Screws into the charger mount and operates the clamping mechanism.|Yes.|
|`shim-v2.stl`|Can be used instead of a stop for V2 charger mount.|No.|
|`stop-*`|A stop for the V2 charger mount.|Yes if using Charger mount V2 or use `shim.stl`.|
|`modular-apple-watch-dock.step`|Step file contains 3D models for all of the above. No.|
|`README.md`|The documentation. |No.|

![image3](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/Images/image3.png)
![image4](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/Images/image4.png)
![image2](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/Images/image2.png)
![image1](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/Images/image1.png)
