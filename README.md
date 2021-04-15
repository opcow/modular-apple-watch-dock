# Modular Apple Watch Dock / Charging Stand

There are lots of parts here, but a working base only needs 4 printed parts, a base, charger mount, a claw, and a screw.

There are 2 base versions. V2 uses an adjustable stop for the charger mount. You'll need to print this stop if using V2 or alternatively use an M4 screw with a shim to clamp the charger mount in place. There are versions of the bases that have holes for mounting feet or magnets on the bottom and versions with no holes. The holes were sized to fits some 3mm x 6mm neodymium magnets I have. The `foot-1.stl` part can also be pressed into the holes. If you don't want feet or magnets, or you want to use adhesive feet/pads of some sort then use the no-holes version.

The cradle part is optional. My 44mm v6 watch doesn't need it. Maybe it could help with the 40mm, or use V2 which can be adjusted for the size of your watch. ¯\\_(ツ)_/¯

While prototyping, I printed all of these parts using 0.28mm layers. Everything looked and worked fine using these coarse layers, even the threads, but your milage may vary. The thread fit could also be affected by your printer's flow rate.

Both versions of the claw have worked well for me. The jointed claw may be delicate. I just press inward near the joint using my thumb to loosen up the joints. The jointed claw has a slightly larger gap where the cable should pass through. There is a mark (a small rounded slot) showing where the wire should go.

How to Print
---
I recommend a 0.2 mm layer height. Infill as low as 10% has worked fine in my prototypes, with the exception of the V2 charger mount when using the shim to clamp it in place. That part has since had small holes added to the clamping areas. The holes serve as inner support and I use 4 walls on that part for added strength.

I have printed all of the parts at 0.28 mm layer height and everything looked and printed fine. I print the charger mount threaded side up, the base with its top side down (I have printed it with the feet side down using supports and that worked fine as well).

You want good layer adhesion for the claw. I raised my usual print temperature a bit which made the claw less prone to breakage, but you want good cooling as well so the parts don’t fuse together too much. Some early iterations of the part were prone to breakage, but I had no issues with the later ones, and I’ve printed quite a few. The claw is small and prints fast, in case you need to do a little trial and error or if you break it. I like to losen up the joints a bit before intalling the jointed claw, which I do by pressing inward near the joint. If you press in at the end of the finger then you are more likely to break break it.

---

As with all of my designs, there is a repo for this one on my [Github](https://github.com/opcow?tab=repositories).

---
|Filename   |Description   | Required?  |
|---|---|---|
|`base-*.stl`|The dock base.|Yes. |
|`charger-mount-*.stl`|Holds the magnetic charger. The watch hangs here. |Yes. Any one.|
|`clamp.stl`|Holds the charging base for the mini dock.|Yes for the mini.|
|`cradle-v1.stl`|Optional peice the sits between the watch and the base.|No.|
|`foot.stl`|A small foot for the base.|No.|
|`*-claw.stl`|Clamps the charger into the charger mount.|Required for V1 and V2.|
|`screw-*.stl`|Screws into the charger mount and operates the clamping mechanism.|Yes.|
|`shim-v2.stl`|Can be used instead of a stop for V2 charger mount.|No.|
|`*-slot-cover.stl`|Optional cover for the front cable pass-through slot.|No.|
|`stop-*`|A stop for the V2 charger mount.|Yes if using Charger mount V2 or use `shim.stl`.|
|`*-wire-cap.stl`|Can be pressed into the front cable slot to keep the wire in place.|No.|
|`wire-cap-plate-v1.stl`|Can be used to hold the cable into either the front or rear slot. Mounts under the base v1 with M3 screws.|No.|
|`modular-apple-watch-dock.step`|Step file contains 3D models for all of the above. No.|
|`README.md`|The documentation. |No.|

![image3](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/Images/image3.png)
![image4](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/Images/image4.png)
![image2](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/Images/image2.png)
![image1](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/Images/image1.png)
