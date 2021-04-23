# Modular Apple Watch Dock / Charging Stand

There are versions of the bases that have holes for mounting feet or magnets on the bottom and versions with no holes. The holes were sized to fits some 3mm x 6mm neodymium magnets I have. The `foot-1.stl` part can also be pressed into the holes. If you don't want feet or magnets, or you want to use adhesive feet/pads of some sort then use the no-holes version.

Both versions of the claw have worked well for me. The jointed claw may be delicate. The jointed claw has a slightly larger gap where the cable should pass through. There is a mark (a small rounded slot) showing where the wire should go.

How to Print
---
Use whatever layer hieght you want. Infill as low as 10% has worked fine in my prototypes. I have printed all of the parts at 0.28 mm layer height and everything looked and printed fine. I print the charger mount thread side up, the base with its top side down.

You want good layer adhesion for the claw. I raised my usual print temperature a bit which made the claw less prone to breakage, but you want good cooling as well for the jointed claw so that the parts don’t fuse together too much. Some early iterations of the part were prone to breakage, but I've had no issues with the later ones, and I’ve printed quite a few. The claw is small and prints fast, in case you need to do a little trial and error or if you break it. I like to losen up the joints a bit before intalling the jointed claw, which I do by pressing inward near the joint. If you press in at the end of the finger then you are more likely to break break it.

---

There is a repo for this design on on my [Github](https://github.com/opcow?tab=repositories).

---
|Filename   |Description   | Required?  |
|---|---|---|
|`base-*.stl`|The dock base.|Yes.|
|`charger-mount.stl`|Holds the magnetic charger. The watch hangs here. |Yes.|
|`foot-1.stl`|A small foot for the base.|No.|
|`*-claw.stl`|Clamps the charger into the charger mount.|Yes.|
|`screw.stl`|Screws into the charger mount and operates the clamping mechanism.|Yes.|
|`modular-apple-watch-dock.step`|Step file contains 3D models for all of the above. No.|
|`README.md`|The documentation. |No.|

![image3](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/Images/image3.png)
![image2](https://raw.githubusercontent.com/opcow/modular-apple-watch-dock/main/Images/image2.png)
